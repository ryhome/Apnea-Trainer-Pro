# Apnea Trainer Pro — User Guide

A static apnea (dry breath-hold) trainer for freedivers, swimmers, and beginners. Train your breath-hold on land with guided protocols, progress tracking, and offline support.

**Live app:** [apnea.home1ab.com](https://apnea.home1ab.com)

---

## ⚠️ Read This First — Safety

Breath-hold training carries real risks. Please follow these rules:

- **Train on dry land only.** This app is for *static apnea on land* — sitting or lying down. **Never** do breath-holds in or near water without a trained, attentive buddy. Shallow-water blackout can be fatal and gives no warning.
- **Never train alone in water.** Even strong swimmers black out silently.
- **Stop if you feel dizzy, lightheaded, or see spots.** These are warning signs — end the hold immediately and breathe normally.
- **Don't hyperventilate** before a hold. Rapid deep breathing lowers your urge to breathe and dramatically increases blackout risk.
- **Stay seated or lying down** during holds, in case you become faint.
- **Consult a doctor** before starting if you have heart conditions, high/low blood pressure, are pregnant, or have any respiratory condition.

This app is a training aid, not a substitute for proper freediving instruction. If you're serious about freediving, take a certified course (e.g. AIDA, SSI, PADI Freediver).

---

## Installing the App

Apnea Trainer Pro is a **PWA** (Progressive Web App), so it installs straight from your browser — no app store needed.

### iPhone / iPad (Safari)

1. Open [apnea.home1ab.com](https://apnea.home1ab.com) in **Safari**.
2. Tap the **Share** button (the square with an arrow).
3. Scroll down and tap **Add to Home Screen**.
4. Tap **Add**.

The app now launches full-screen from your home screen, just like a native app.

> **Important:** Installing to your Home Screen isn't just for convenience — on iPhone it also protects your training data. Data for a site you only visit in Safari can be cleared automatically after 7 days of not opening it. Installed apps keep their data. **Always install to Home Screen if you want to keep your history.**

### Android (Chrome)

1. Open [apnea.home1ab.com](https://apnea.home1ab.com) in **Chrome**.
2. Tap the **⋮** menu (top right).
3. Tap **Install app** or **Add to Home screen**.

### Desktop (Chrome / Edge)

1. Open [apnea.home1ab.com](https://apnea.home1ab.com).
2. Click the **install icon** in the address bar (a monitor with a down-arrow), or open the **⋮** menu and choose **Install**.

### Works Offline

Once loaded, the app caches itself and works **completely offline** — no internet needed for training. Your data is stored locally on your device.

---

## The Five Tabs

The bottom navigation bar has five sections:

| Tab | What it's for |
|-----|---------------|
| **Home** | Your dashboard — personal best, level, quick-start, recent dives |
| **Train** | Choose and start a training protocol |
| **Stats** | Full statistics, activity heatmap, and dive log |
| **Awards** | Achievements and your downloadable certificate |
| **Settings** | Audio, haptics, backup, and reset |

---

## Training Modes

Open the **Train** tab and pick one of four modes.

### 🌊 Beginner

A guided progression system that builds your hold time gradually.

- **30 levels**, starting at **30 seconds** and rising in 5-second steps up to **3 minutes** (180s).
- To advance, you must **successfully complete a level's hold 3 times**. After 3 passes, the next level unlocks.
- Locked levels show a 🔒. The dots at the bottom of each level tile show your progress (e.g. 2 of 3 passes).
- Tap any unlocked level to select it, then **Start**.

This is the recommended starting point if you're new.

### 💨 CO₂ Table

Trains your **tolerance to carbon dioxide** — the discomfort that makes you *want* to breathe.

- Hold times stay constant; **rest times get shorter** each round.
- Choose a preset: **Beginner**, **Intermediate**, or **Advanced**.
- Or pick **Custom** to set your own Hold Time, Rest Time, and number of Rounds.

> **Note:** CO₂ tables are demanding. Don't do them every day — your body needs recovery. 2–3 times per week is plenty.

### 🫁 O₂ Table

Trains your body to **function on less oxygen**.

- Rest times stay constant; **hold times get longer** each round.
- Same preset options (Beginner / Intermediate / Advanced) plus **Custom**.

### ⏱ Free Hold

A simple, open-ended stopwatch for a single breath-hold.

- Tap **Start**, hold your breath, then tap **Stop & Save** when you're done.
- Use this for max-attempt tests or casual practice.
- Tap the **✕** to discard without saving.

---

## During a Session

When you start, you'll see the **breath-hold ring**:

- A **3-second countdown** begins each session.
- The large center number is the **time remaining** in the current phase.
- The ring **fills as the phase progresses**, with a gentle breathing pulse animation.
- The phase label tells you what to do:
  - **PREPARE** — get ready, take your final breath
  - **HOLD** — hold your breath
  - **RECOVER** — breathe and recover before the next round
- The **Next** tag previews the upcoming phase.
- The counter at top right (e.g. `03 / 08`) shows which round you're on.

**Controls:**

- **Pause / Resume** — pause the timer mid-session.
- **✕** (top left) — exit the session early.

**Audio & haptic cues** fire on the final 3 seconds of a hold, on phase changes, and at the start — so you can train with your eyes closed.

### Screen Stays On

The app keeps your screen awake during a session (using the Wake Lock feature), so it won't dim or sleep mid-hold. Timing is also clock-accurate — even if you switch away and come back, the timer stays correct.

---

## Tracking Your Progress

### Home Dashboard

- **Personal Best** — your longest hold ever, shown large.
- **Level dial** — current level and progress toward the next.
- **Quick stats** — streak, success rate, total sessions, average hold.
- **Recent Dives** — your last few sessions at a glance.

### Stats Tab

- A full grid of metrics: personal best, streak, sessions, success rate, average hold, total training time, weekly sessions, and current level.
- An **activity heatmap** showing the last 16 weeks — darker squares mean more sessions that day.
- A complete **dive log** of your sessions.

A green bar on a session means you hit your target; a red bar means a partial hold.

### Awards Tab

- **Achievements** unlock automatically as you progress (first hold, 1-minute club, 7-day streak, 100 sessions, and more).
- **Certificate** — once you've logged a session, tap **Download Certificate** to save a shareable PNG showing your personal best, level, streak, and stats.

---

## Backup & Restore

Your data lives **on your device only** — there's no cloud account, which keeps it private. That also means **you're responsible for backups.**

### Export a Backup

1. Go to **Settings → Backup → Export Backup**.
2. A `.json` file downloads with all your settings, history, achievements, and stats.
3. Keep it somewhere safe (cloud drive, email to yourself, etc.).

### Restore a Backup

1. Go to **Settings → Backup → Import Backup**.
2. Select your saved `.json` file.
3. Your data is restored.

> **Recommendation:** Export a backup every few weeks, and always before clearing your browser, switching phones, or reinstalling. This is the only way to guarantee you never lose your progress.

---

## Settings

- **Sound Cues** — toggle countdown and phase tones.
- **Mute Mode** — silence all audio quickly.
- **Haptic Feedback** — toggle vibration (supported devices only).
- **Export / Import Backup** — see above.
- **Reset All Data** — permanently erases everything. Use with care.

---

## Frequently Asked Questions

**Will I lose my data if I close the app?**
No. Your data persists between sessions. The main risks are: clearing your browser data, using private/incognito mode, or (on iPhone Safari) not opening the site for 7+ days *without* having installed it to your Home Screen. Install to Home Screen and export backups to stay safe.

**Does it work without internet?**
Yes. After the first load, the app runs fully offline.

**Can I sync between devices?**
Not automatically — there's no cloud account. To move data between devices, use **Export Backup** on one device and **Import Backup** on the other.

**Is my data private?**
Yes. Everything stays on your device. Nothing is sent to a server.

**How often should I train?**
Beginner holds can be done most days. CO₂ tables are intense — limit them to 2–3 times a week and rest between sessions. Listen to your body.

**The timer beeped a lot when I came back to the app — why?**
The timer stays accurate even when the app is in the background. If you return after the screen was off, it catches up to the correct time. This is normal.

---

## A Final Word

Progress in apnea comes from **consistency and relaxation**, not from pushing hard. Stay calm, breathe well between holds, and never sacrifice safety for a bigger number. Train smart and enjoy the dive.

*Apnea Trainer Pro — offline-first, no backend, your data stays yours.*
