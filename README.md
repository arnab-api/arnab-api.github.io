# arnab-api.github.io

Personal website of Arnab Sen Sharma: plain HTML and CSS, no build step.

| path | what |
|---|---|
| `index.html` | the whole site: about, news, publications, experience |
| `style.css` | all styling (light and dark themes) |
| `images/` | profile photo, favicons, publication thumbnails (`images/papers/`) |
| `files/Arnab_Sen_Sharma.pdf` | CV |
| `goalscope/` | standalone GoalScope demo (not indexed) |
| `research/`, `experience/`, `cv/`, `about/`, `publications/`, `about.html` | redirects from the old Jekyll URLs |
| `404.html`, `robots.txt`, `sitemap.xml` | served as is by GitHub Pages |

`.nojekyll` tells GitHub Pages to serve the files as they are, without running Jekyll.

**Editing.** Add a news item as an `<li>` at the top of the `News` list in `index.html` (move old ones into
*Older news*). Add a publication by copying an `<article class="paper">` block and putting its thumbnail in
`images/papers/`.

**Preview locally.** `python3 -m http.server 8000 --bind 127.0.0.1`, then open <http://127.0.0.1:8000/>.

**Hosting.** GitHub Pages, deployed from the default branch root (Settings ▸ Pages ▸ "Deploy from a branch").
