# acmeagileconsulting.com

Static site for Dennis Wong / Acme Agile Consulting, hosted on GitHub Pages.

## Editing text
Open a page, click the pencil icon, and change only the words between the
`<!-- ===== EDIT: ... ===== -->` and `<!-- ===== END ... ===== -->` markers.
Commit, and the live site updates in a minute or two.

| Page | File |
|---|---|
| Home | `index.html` |
| Results | `results/index.html` |
| How it works | `howitworks/index.html` |
| About | `about/index.html` |
| Contact | `contact/index.html` |
| Nav links and footer (all pages) | `_layouts/default.html` |
| Colors and fonts | `assets/style.css` (top of file) |
| Images | `assets/img/` |

The Book a call link appears on several pages. Search for `bookings.cloud.microsoft` to find every copy.

Redirects from old page addresses (all keep ?utm_ tags):
- Folders `howiwork/`, `resources/`, `library/`, `reality-check/`, `a1-whatisittransformation/`, `a2-what-is-it-agile/`, `a8-a-long-agile-side-story/`, `c3-roi-automated-pipelines/` each redirect to a new page. Leave them.
- `404.html` catches everything else (typos like `/war ing-signs`, other old `/a#-` and `/c#-` article URLs) with a short list of rules at the top. Add a rule there for any new broken URL you see in Analytics.

Rule: no em dashes.
