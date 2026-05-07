# 🛠️ Interactive Display Tools

A collection of browser-based interactive tools designed for classroom and event use. All files are self-contained single-page HTML — no dependencies, no build step. Open directly in any browser.

---

## Files

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
- Heading line 1 is also **inline-editable** by clicking directly on it

---

## Usage

Open either file directly in a browser — no server required. For a presentation display, use fullscreen mode (F11 or the ⛶ button) and consider projecting onto a second screen.

> **Tip for Parents' Evening Timer:** set the *Start Offset* to the actual start time of your event (e.g. `15:30`) so interval boundaries align exactly with your appointment schedule from the very first slot.
