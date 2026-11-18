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
| v1.8 | 2026-11-16 | Double-click any graph, card or stat tile to enlarge it (double-click title / Esc / click outside to close) |
| v1.9 | 2026-11-16 | Versions & roll back section in Settings; older versions viewable under `versions/`; presentation 31 slides, walkthrough screenshots refreshed |
| v1.10 | 2026-11-16 | Test user sign-in on the sign-in screen (one shared test username and password; only a salted hash is stored in the page) |
| v1.11 | 2026-11-16 | Guest access now needs one shared guest password (only a salted hash is stored in the page); older versions in `versions/` are gated the same way |
| v1.12 | 2026-11-16 | Privacy Guard (designed) listed on the 4 Models page: how text becomes numbers only, with the safety chain; chat explains it |
| v1.13 | 2026-11-16 | Easier to find: sidebar link and a Settings shortcut button open the Versions & roll back list |
| v1.14 | 2026-11-16 | Versions & roll back button in the top bar, next to Settings |
| v1.15 | 2026-11-17 | Slide show: "▶ Slides" in the top bar goes full screen and moves through the pages every 20 seconds (pause, arrow keys, Esc to stop) |
| v1.16 | 2026-11-17 | Home clean-up (Velocity items removed, 7 Pillars team-average card), bell next to the avatar, Slides speed picker and auto-run, Versions only under Settings, collapsed "Story & Platform" sidebar group, team label, greeting and manager name follow the signed-in user |
| v1.17 | 2026-11-17 | Job titles optional (⚙ Settings › Show designations, off by default), anonymous names read "Team member 1–6", 7 Pillars card can show one member as well as the team average (consent needed for individuals) |
| v2.0 | 2026-11-18 | Simulation updates the whole Home page, Team Intelligence profile and Reports heatmap (Risk Signals and story-page visuals stay static), sphere spin follows simulation speed, "Needs a check-in" bubble, Customise per page, ☰ Menu hides the left navigation bar, date/time after the user name, Settings › Account shows the signed-in user, Slides renamed Showcase |
| v2.1 | 2026-11-18 | Home de-duplicated: Team Health bubble removed, Safe Score card shows the donut and a threshold note (rows removed); ☰ Menu button moved to the left of the top bar; clock hidden under 1360 px width |

## Rolling back

- **Inside the dashboard:** open **⚙ Settings → Versions & roll back**. Each version lists what it added and what it lacks compared with the latest, and **Open** shows it read-only (pages in `versions/`, e.g. `versions/v1.7.html`). This does not change the public site. The same section has a **Copy command** button for the site owner.
- **View an old version:** on GitHub, open the repository, choose the tag from the branch/tag menu, and open `index.html`.
- **Restore an old version as the live site** (example: back to v1.6):

  ```
  git checkout v1.6 -- index.html
  git commit -m "Roll back dashboard to v1.6"
  git push
  ```

  GitHub Pages republishes in about a minute. Nothing is lost: the newer versions stay in the history and can be restored the same way.
