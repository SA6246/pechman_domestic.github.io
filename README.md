# Know Your Rights — Domestic Workers DEMO REPO JUST MVP FOR UI/X EXPERIENCE

A bilingual (English/Spanish) informational landing page for domestic workers in New York State, outlining wage and hour protections under federal and state law.

**Live site:** [sa6246.github.io/pechman_domestic.github.io](https://sa6246.github.io/pechman_domestic.github.io/)

## Overview

This site provides accessible, plain-language information about the legal rights of domestic workers — including housekeepers, nannies, home health aides, personal assistants, au pairs, chauffeurs, cooks, and landscapers — under the following frameworks:

- **FLSA** — Fair Labor Standards Act (federal)
- **NYLL** — New York Labor Law (state)
- **NY Domestic Workers' Bill of Rights** — NY CLS Labor § 161

## Features

- **Bilingual toggle** — Full English/Spanish support via a single-page language switcher
- **Category-based navigation** — Workers can identify their role and see applicable rights
- **Wage calculator** — Estimates regular and overtime pay with a legal disclaimer
- **Contact form** — Intake form for scheduling a confidential legal consultation
- **Accessibility** — Colorblind-safe palette using blue/orange/teal instead of red/green, text labels on all status indicators
- **Responsive** — Mobile-first layout, works on all screen sizes
- **Single file** — Entire site is one self-contained `index.html` with no external dependencies beyond Google Fonts

## Worker Categories Covered

| Category | Key Protections |
|----------|----------------|
| Housekeepers (live-in) | $17/hr NYC, OT after 44hrs, 24hr rest, 3 paid days/year |
| Housekeepers (daily) | $17/hr NYC, OT after 40hrs, 24hr rest, 3 paid days/year |
| Nannies / Babysitters | Full-time vs casual basis determination, 20hr threshold |
| Home Health Aides | Companion exemption (20% rule), agency disclosure requirements |
| Au Pairs | 10hr/day cap, 45hr/week cap, 2 weeks paid vacation |
| Personal Assistants | On-call compensability rules |
| Chauffeurs / Cooks / Landscapers | Employee vs independent contractor distinction |

## Legal Disclaimer

This site is provided for **educational purposes only** and does not constitute legal advice. An attorney-client relationship is not created by visiting this website.

## Development

No build step required. Edit `index.html` directly.

```bash
# Clone and serve locally
git clone https://github.com/SA6246/pechman_domestic.github.io.git
cd pechman_domestic.github.io
open index.html
# or
python3 -m http.server 8000
