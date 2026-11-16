# ProSense AI dashboard: versions

Every change to the public dashboard is a git commit, and each release has a tag. To look at or roll back to an older version, see "Rolling back" below.

| Tag  | Date       | What changed |
|------|------------|--------------|
| v1.0 | 2026-11-14 | First public dashboard (synthetic demo data) |
| v1.1 | 2026-11-15 | Guest demo access on the sign-in screen |
| v1.2 | 2026-11-15 | Capstone presentation added; dashboard values aligned with the deck |
| v1.3 | 2026-11-15 | Chart info tooltips, enlarge view and focus mode |
| v1.4 | 2026-11-15 | Vision and models card; presentation expanded to 29 slides |
| v1.5 | 2026-11-15 | Course and instructor references removed; screenshots refreshed |
| v1.6 | 2026-11-16 | Ask ProSense in-browser assistant |
| v1.7 | 2026-11-16 | Admin Settings: dark/light appearance, full screen, focus view, anonymous names, simulation controls |

## Rolling back

- **View an old version:** on GitHub, open the repository, choose the tag from the branch/tag menu, and open `index.html`.
- **Restore an old version as the live site** (example: back to v1.6):

  ```
  git checkout v1.6 -- index.html
  git commit -m "Roll back dashboard to v1.6"
  git push
  ```

  GitHub Pages republishes in about a minute. Nothing is lost: the newer versions stay in the history and can be restored the same way.
