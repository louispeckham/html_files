# 🛠️ Interactive Display Tools

A collection of browser-based interactive tools designed for classroom and event use. All files are self-contained single-page HTML — no dependencies, no build step. Open directly in any browser.

---

## Files


### [`name-sorter.html`](https://louispeckham.github.io/html_files/Tools/name-sorter.html)
A browser-based tool for sorting lists of names alphabetically, with options to split the output into separate columns. Designed to produce clean, paste-ready output for use in PowerPoint, Word, or similar applications.

**Use cases:** Generating alphabetical class lists, organising names for seating plans, preparing display-ready name columns for presentations.

**Key features:**
- Paste or type any number of names (one per line) — output sorts instantly as you type
- Toggle **Sort by last name** to sort alphabetically by the final word in each name
- **Columns dropdown** (1–8) splits the sorted list into separate column textareas, each independently selectable — click into any column to copy it individually, or double-click to select all names in that column
- Column distribution always fills every column, even when the name count isn't divisible by the number of columns
- **Surname → initial** button reduces each surname to its first initial (e.g. `Alice Smith` → `Alice S`), with full support for hyphenated surnames (e.g. `Alice Smith-Jones` → `Alice S-J`)
- **Copy all** button copies the full sorted list tab-separated, ready to paste as a single text block
- **Dark mode** toggle, with preference saved via `localStorage` and automatic detection of system preference
- Fully self-contained — no internet connection required

---

### [`Orbitext.html`](https://louispeckham.github.io/html_files/Tools/Orbitext.html)
An interactive word-orbit display where words and phrases orbit a central title on a starfield background. Words are added one at a time and orbit at randomised speeds, directions, radii, and colours.

**Use cases:** Brainstorming sessions, word association activities, live audience contribution displays, lesson starter activities.

**Key features:**
- Press **Enter** anywhere to add a new orbiting word
- Click the **✎** button to edit the central title (supports multi-line with Shift+Enter)
- Open the **☰ panel** (bottom-right) to rename or delete individual words
- **Export / Import CSV** to save and restore a word set between sessions
- **Starscape toggle** enables a parallax two-layer animated star background

---

### [`Parents' Evening Timer.html`](https://louispeckham.github.io/html_files/Tools/Parents'%20Evening%20Timer.html)
A countdown timer and interval chime tool for parents' evenings and similar timed-appointment events. Shows the current time and a countdown to the next slot change, with a red overlay that fills the screen as each interval elapses.

**Use cases:** Parents' evenings, speed networking, timed interview rotations, any event with fixed-length appointment slots.

**Key features:**
- Displays the **current time** and a **countdown** to the next slot change
- A **red overlay** shrinks across the screen as each interval ticks down — a clear at-a-glance signal for teachers and staff
- **Chime sound** plays automatically at every interval boundary (triple-strike bell, synthesised in-browser via Web Audio API)
- Click **⚙️** (top-right) to open Settings:
  - Customise both heading lines
  - Set interval length (1–60 minutes)
  - Set a start-time offset to align intervals to a fixed schedule (e.g. `15:30`)
  - Toggle chime on/off and adjust volume
- Click **⛶** to enter fullscreen mode
- All settings persist via `localStorage` — no need to reconfigure on reload
- Heading line 1 is also **inline-editable** by clicking directly on it, so that you can easily change the year group/classes.

---
