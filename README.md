# Excel Examples

Excel practice exercises, rebuilt from tutorial screenshots. Every calculated cell is a live formula, so changing an input updates the whole sheet.

| File | What it shows |
|---|---|
| `Employee_Gradebook.xlsx` | Test scores for 17 employees. Percentages (score ÷ points possible), traffic-light icon sets, red highlight under 50%, a "Fire Employee?" flag using `OR()`, Max/Min/Average rows, and bar charts per test. |
| `Career_Decisions.xlsx` | Weighted decision matrix. Each factor (Pay, Job Market, Enjoyment, My Talent, Schooling) has a weight; score × weight is summed into a total, and the best job is highlighted with conditional formatting. |
| `Employee_Payroll.xlsx` | Five weeks of January payroll for 17 employees. Hours worked, overtime hours (`MAX(0, hours-40)`), pay (wage × hours), overtime bonus (50% of wage per overtime hour), weekly totals, a January total per person, and Max/Min/Average/Total rows. The 40-hour week and 50% bonus rate are settings you can change. |

## Skills practised
- Relative vs absolute references (`C4/C$2`, `B5*C$4`)
- `MAX`, `MIN`, `AVERAGE`, `SUM`, `OR`
- Mixed references (`$C4`) to copy one formula across many weeks
- Conditional formatting: icon sets, highlight rules, formula-based rules
- Bar charts
- Page setup for printing
