# India Cost Index 2026: what middle-class milestones cost

What the milestones of a middle-class Indian life cost, from Kota coaching to a flat's down payment to a retirement corpus, in one CSV. **40 items** across education and careers, family, festivals, home and vehicles, retirement, and starting a business. Every figure is a range with its exact scope, and every row links to the full breakdown behind it.

**Live version with the breakdowns:** https://paisatools.co.in/cost-index

## The data

`data/paisatools-cost-index-2026.csv`, one row per milestone:

| Column | Meaning |
|---|---|
| `group` | Category (Education and careers, Family, Festivals, Home and vehicles, Retirement, Starting something) |
| `item_id` / `label` | Short id and readable name |
| `scope` | Exactly what the range covers (read this before using a figure) |
| `range_as_published` | The range as written, e.g. "₹6–10 lakh" |
| `low_inr` / `high_inr` | The range in rupees |
| `basis` | Whether the range is a total, per year, per month, etc. |
| `government_or_public_route` | A cheaper public or government option where one exists |
| `source_url` | The full cost guide the range comes from |
| `edition`, `edition_date`, `publisher`, `license` | Provenance |

## How it's built

- **Copied, not re-estimated.** Each range comes from a PaisaTools cost guide, researched from published fee schedules, regulator rules and current market quotes. The index copies the guide's own figure and scope; it doesn't average or re-estimate anything.
- **Typical, not quotes.** Ranges describe what most families will see in 2026. A specific city, institution or clinic can sit outside them.
- **Information, not financial advice.**

## Citation

> PaisaTools (2026). *The PaisaTools Cost Index 2026: Middle-Class Milestones.* https://paisatools.co.in/cost-index

## Licence

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/): free to use, including commercially, with attribution to PaisaTools and a link to https://paisatools.co.in/cost-index.
