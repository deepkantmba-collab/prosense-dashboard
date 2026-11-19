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
| v2.2 | 2026-11-18 | Team name follows the signed-in user on the story pages, menu item, team table, avatar and Ask ProSense (no more "Priya"); Settings › Email alerts (set up + send test); Customise / Focus / Settings / Showcase moved under one ⚙ menu |
| v2.3 | 2026-11-18 | Fix: Customise / Focus / Settings / Showcase in the ⚙ menu respond to clicks; user avatar and bell on the far right |
| v2.4 | 2026-11-18 | Quality pass: keyboard and screen-reader access, text never below 10 px, reduced-motion support, Model A before Model B, menu name gap fixed |
| v2.5 | 2026-11-18 | Narrow-screen layout: left menu becomes a slide-over below 1100 px, Home and cards stack, wide tables scroll, no more 1100 px minimum width |
| v2.6 | 2026-11-18 | Ask ProSense button moves to the header (floating only in Focus view); Live Risk Signals feed scrolls in its card; cards no longer show empty space |
| v2.7 | 2026-11-18 | Full review: muted, purple and red text lightened to pass the 4.5:1 contrast check on every page; Home bottom row taller so Team Pulse shows all six members |
| v2.8 | 2026-11-18 | Design polish: Inter font and a fixed type scale, 8px spacing grid, three background layers with 1px borders, sharp charts on Retina screens, calmer globe, 150ms transitions and clear focus outlines; Team Intelligence radar and pillars fill their cards; Home scrolls on short screens |
| v2.9 | 2026-11-18 | Honest model figures: a data leak was fixed (the outcome column `attrition_risk` had been used as a feature). Random Forest AUC 0.9479 becomes 0.9021 (HGB 0.8934), trained on 6 clean features; SHAP drivers, model cards, Ask ProSense and the presentation updated; Arjun's 0.97 is labelled a composite risk score (the trained model alone rates an Arjun-like profile 0.92) |
| v2.10 | 2026-11-18 | Enlarge (the ⤢ button or double-click) now scales the widget up to fill the screen with sharp text and charts, and tall widgets scroll; account menu under the name in the top bar (Switch user, Log out); new footer line describing the training dataset; presentation and walkthrough screenshots refreshed |
| v2.11 | 2026-11-18 | Enlarge view re-flows wide, short widgets to a narrower layout and scales them up to 2.5x so text is large and focused; Home top row can no longer be shorter than its tallest column (bottom row never covers the cards above); Team Pulse header wraps cleanly |
| v2.12 | 2026-11-18 | New Slate appearance: Settings › Appearance now offers Dark, Light or Slate (neutral grey surfaces, softer borders, rounder cards, indigo accent for interactive controls). Data colours unchanged; Dark stays the default. Ask ProSense understands "switch to slate theme". |
| v2.13 | 2026-11-19 | Honest drift monitor and labels: the MLOps PSI card now shows a real PSI calculation on the synthetic data (baseline vs an injected stress test, labelled as a demo, no drift observed) instead of simulated meters; Situation figures (63%, 41%, 87%) labelled scenario figures; the 45-second scoring line is a design target; $2–4M labelled illustrative. Slate refinements: one indigo accent, bigger KPI numbers, threshold bars (amber at 80% of limit, red when over), empty states, phone-width table cards |
| v2.14 | 2026-11-19 | Slate-only Home redesign (status line, Safe Score plus four KPI tiles with baselines, 7 Pillars weakest first with a 60 line, Team Pulse, three next best actions) and Slate header/menu clean-up (page title, grouped menu, Resolution under Act); Dark and Light unchanged; themed dropdown lists (the 7 Pillars picker and other selects follow Dark, Light or Slate instead of opening white); Safe Score gauge typography fixed (number and /100 in one type style inside the ring, Critical label no longer overflows); linked presentation rebuilt as 22 slides with a summary and ask, 5-fold cross-validation and baselines, the real PSI drift check, and scenario figures labelled |
| v2.15 | 2026-11-19 | Accessibility pass (AI Insights buttons, Export PDF and Share Report, landmarks, labels, Esc closes pop-ups); Indigo appearance; Slate-only logo for testing |
| v2.16 | 2026-11-19 | Slate and Indigo Home: every number and widget is a live reference (hover shows meaning, value and source; click opens the cited page and highlights the card; banner and next best actions linked; Back to Home); Settings › Arrange and resize widgets (drag, resize, keyboard, Reset layout); translucent glowing ProSense heart logo with beating heart and running ECG; Indigo KPI tiles match the cards; Dark and Light globe tiles aligned; 7 Pillars and Team Pulse no longer clipped on short and phone screens |
| v2.17 | 2026-11-19 | Live radar-heart logo on Slate and Indigo: a heart inside a radar whose sweep turns, signals light up as it passes, the heart beats and the ECG line runs; motion stops with reduce-motion; sidebar and sign-in |
| v2.18 | 2026-11-19 | Settings › Versions & roll back grouped into two drop-downs, Version 2 (v2.0 onward, open) and Version 1 (v1.5 to v1.17, closed); linked presentation rebuilt (22 slides) with the title slide showing dashboard v2.18 and the four themes listed |
| v2.19 | 2026-11-19 | Radar-heart logo on all four appearances (Dark, Light, Slate, Indigo); Indigo-only motion and icons on every page: widgets animate in, bars fill, Safe Score ring draws, numbers count up, business emojis on every card title and metric, Team Pulse donut and Key Insights panel on Home, replays on every page open; linked presentation rebuilt (22 slides) for v2.19 |
| v2.20 | 2026-11-19 | Indigo appearance only (Dark, Light and Slate unchanged): scrollbars hidden until hover with a fixed gutter (no sideways layout shift); fade on long lists; dropdowns float above cards and flip or shift at the screen edge; search box on lists with more than 8 options; 150 ms scale-and-slide, fade only under reduced motion; linked presentation rebuilt (22 slides) for v2.20 |

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
