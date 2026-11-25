# UKPayClear Open Data (2026/27)

Open CSV datasets modelling 2026/27 HMRC and Scottish Government tax rules: the £100,000–£125,140 60% tax trap (England vs. Scotland), the Scotland vs. England income tax gap from £25,000 to £200,000, and Inside IR35 (umbrella) vs. Outside IR35 (Ltd) contractor take-home from £350 to £1,000/day.

All figures are computed directly from finalised 2026/27 HMRC and Scottish Parliament rates. Interactive calculators and methodology live at [ukpayclear.co.uk](https://ukpayclear.co.uk/).

## Datasets in this repository

| File | Coverage | Live report & calculator |
|---|---|---|
| [`data/uk-60-percent-tax-trap-2026-2027.csv`](data/uk-60-percent-tax-trap-2026-2027.csv) | 13 salary points (£90,000 to £150,000): Personal Allowance taper, England (62%) vs. Scotland (69.5%) marginal tax+NI rate, and net cost of salary sacrifice back to £100k | [UK 60% Tax Trap Report](https://ukpayclear.co.uk/reports/uk-60-percent-tax-trap-2026-2027/) / [Salary Sacrifice Calculator](https://ukpayclear.co.uk/salary-sacrifice-calculator/) |
| [`data/scotland-vs-england-tax-gap.csv`](data/scotland-vs-england-tax-gap.csv) | 15 salary points (£25,000 to £200,000): annual and monthly income tax difference, net pay, and marginal rates | [Scotland vs England Tax Gap Report](https://ukpayclear.co.uk/reports/scotland-vs-england-tax-gap/) / [Take-Home Calculator](https://ukpayclear.co.uk/) |
| [`data/inside-vs-outside-ir35-day-rates.csv`](data/inside-vs-outside-ir35-day-rates.csv) | 14 day rates (£350 to £1,000/day, 220 billing days): umbrella vs. Ltd net pay, retention %, annual Outside advantage, and permanent PAYE equivalent | [Inside vs Outside IR35 Report](https://ukpayclear.co.uk/reports/inside-vs-outside-ir35-day-rates/) / [IR35 Calculator](https://ukpayclear.co.uk/ir35-calculator/) |

---

## 1. The £100,000–£125,140 Tax Trap (England vs. Scotland)

Losing £1 of Personal Allowance (£12,570) for every £2 earned above £100,000 pushes the combined marginal Income Tax + Employee NI rate to **62.0%** in England and **69.5%** in Scotland:
- Earning **£125,140** instead of £100,000 adds only **£9,554** net in England (**£7,668** in Scotland).
- Putting the entire **£25,140** into a pension via salary sacrifice costs just **£9,553** of net take-home in England (**£7,668** in Scotland).

| Gross annual | Personal Allowance | England net | England marginal | Scotland net | Scotland marginal | Sacrifice to £100k | Net cost (England) | Net cost (Scotland) |
|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| £100,000 | £12,570 | £68,557 | **62.0%** | £65,257 | **69.5%** | £0 | £0 | £0 |
| £110,000 | £7,570 | £72,357 | **62.0%** | £68,307 | **69.5%** | £10,000 | £3,800 | £3,050 |
| £120,000 | £2,570 | £76,157 | **62.0%** | £71,357 | **69.5%** | £20,000 | £7,600 | £6,100 |
| £125,140 | £0 | £78,111 | 47.0% | £72,925 | 50.0% | £25,140 | **£9,553** | **£7,668** |
| £150,000 | £0 | £91,286 | 47.0% | £85,355 | 50.0% | £50,000 | £22,729 | £20,098 |

---

## 2. Scotland vs. England Income Tax Divergence (2026/27)

- Earners on **£25,000–£30,000** pay **£35–£40 less** income tax in Scotland.
- Above **£43,662**, Scotland's 42% Higher Rate opens a steep gap: **+£1,496/yr** (£125/mo) more tax at **£50,000**, **+£1,750/yr** at **£60,000**, **+£3,300/yr** at **£100,000**, **+£5,175/yr** at **£125,000**, and **+£7,431/yr** (£619/mo) at **£200,000**.

---

## 3. Inside vs. Outside IR35 Contractor Retention (2026/27)

With 2026/27 higher dividend tax rates and Corporation Tax marginal relief (19% to 25%):
- The Outside IR35 Ltd advantage peaks at **£600/day** (**+£4,979/yr**, 59.7% vs. 56.0% retention; equivalent to £126,535 vs. £113,983 perm PAYE) and **£650/day** (**+£4,736/yr**).
- Above £750/day, the gap narrows sharply down to **+£1,033/yr** at **£1,000/day** (51.6% vs. 51.2% retention) when full profits are extracted annually.

---

## Primary Official Sources

- HMRC: [Income Tax rates](https://www.gov.uk/income-tax-rates), [Income over £100,000](https://www.gov.uk/income-tax-rates/income-over-100000), [Tax on dividends](https://www.gov.uk/tax-on-dividends)
- HMRC: [National Insurance rates](https://www.gov.uk/national-insurance-rates-letters), [Corporation Tax](https://www.gov.uk/corporation-tax-rates), [Off-payroll working (IR35)](https://www.gov.uk/guidance/understanding-off-payroll-working-ir35)
- Scottish Government: [Scottish Income Tax 2026/27](https://www.mygov.scot/scottish-income-tax)

## Interactive Calculators and Embeds

- UK Take-Home Pay calculator: https://ukpayclear.co.uk/
- Salary Sacrifice & £100k Tax Trap calculator: https://ukpayclear.co.uk/salary-sacrifice-calculator/
- £100k Tax Trap guide: https://ukpayclear.co.uk/100k-tax-trap-explained/
- Inside vs. Outside IR35 calculator: https://ukpayclear.co.uk/ir35-calculator/
- Dividend tax & Corporation Tax calculators: https://ukpayclear.co.uk/dividend-tax-calculator/
- Lightweight iframe embeds (no sign-up): `https://ukpayclear.co.uk/embed/take-home/`, `https://ukpayclear.co.uk/embed/dividend/`, `https://ukpayclear.co.uk/embed/ir35/`

## License and Citation

Licensed under [CC-BY-4.0](LICENSE). Citation metadata is in [`CITATION.cff`](CITATION.cff).

```text
UKPayClear (2026). UKPayClear Open Data 2026/27: UK 60% Tax Trap, Scotland vs England Income Tax Gap, and Inside vs Outside IR35 Day Rates [Dataset]. https://ukpayclear.co.uk/reports/ (CC-BY-4.0).
```
