# johnchesleyadams.github.io

John Chesley Adams's public folder, served at
<https://johnchesleyadams.github.io/>.

## Layout

- One folder per project.
- One folder per tool inside its project.
- Lowercase names with hyphens, so web addresses stay clean.

| Folder | What it is | Built from |
|---|---|---|
| `/` | Projects index | this repository |
| `gembook/` | GemBook's public tools | this repository |
| `gembook/look-tuner/` | The GemBook Look Tuner web app, plus `GemBook_Look_Tuner.html`, the same tool as one file | GemBook: `python scripts/build_look_tuner.py --site <this clone>` |

## Rules

- **Tool folders are published copies.** Never edit them here. Fix the
  source in the project's own repository, rebuild, and copy again.
- **Everything here is public.** Only what the owner chose to publish goes here.
- **Hidden from search engines** for now, through `robots.txt` and
  `noindex`. Anyone with the link can still open the pages.
