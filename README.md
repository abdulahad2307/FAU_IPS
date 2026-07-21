# IPS Exam Trainer

A free, self-contained mock-exam trainer for **Integrated Production Systems (IPS)**
(Prof. Dr.-Ing. Jörg Franke · FAPS · FAU Erlangen-Nürnberg).

- **48 questions** across all 13 lecture units + the 3 case studies
- Three question types: **written** (self-graded vs. model answer + rubric), **calculations** (OEE, Cp/Cpk, availability, margins — auto-graded), and **multiple choice** (auto-graded)
- **Andon board** that lights up your readiness per topic (green / amber / red)
- Runs **100% in the browser**. No server, no account, no cost.
- Optional AI grading if *you* add your own API key — never required.

---

## The fastest way to use it

**Just open `index.html`** in any browser (double-click it). That's it — it works offline.

To share it with friends, you have two easy options.

---

## Option A — Put it online with GitHub Pages (one link for everyone)

1. Create a free account at [github.com](https://github.com).
2. Click **New repository**. Name it e.g. `ips-exam`. Make it **Public**. Create it.
3. On the repo page, click **Add file → Upload files**. Drag in **`index.html`**, **`README.md`**, and **`IPS_Study_Notes.md`**. Commit.
4. Go to **Settings → Pages**. Under *Build and deployment → Branch*, pick **`main`** and folder **`/ (root)`**. Save.
5. Wait ~1 minute. Your link appears at the top of the Pages settings:
   **`https://YOUR-USERNAME.github.io/ips-exam/`**
6. Send that link to your friends. They just open it — no setup, no download.

Everyone's scores are saved **locally in their own browser**, so you don't share results unless you want to.

---

## Option B — Everyone runs it locally

Your friends download the repo (green **Code** button → **Download ZIP**), unzip it, and
double-click **`index.html`**. Works offline, nothing to install.

---

## How grading works

- **Calculations & multiple choice** → graded automatically, instantly, with a full worked solution shown afterward.
- **Written questions** → you get the **model answer + a rubric** (the exact points a marker looks for), then score yourself *Got it / Partial / Missed it*. Self-grading against a rubric is one of the most effective ways to actually learn the material.

### Optional: let Claude grade your written answers
If you want automated feedback on written answers:

1. Click **Set up AI grading** on the start screen.
2. Paste an Anthropic API key (from `console.anthropic.com`, uses your own credit).
3. On any written question you'll now see **Grade with AI**.

Your key is stored **only in your browser** — it is never uploaded and never committed to GitHub. Everything still works fully without a key.

> Note: browser-to-API calls can occasionally be blocked by network settings. If AI grading doesn't respond, just self-grade — the trainer is designed to work completely without it.

---

## Editing the questions

All questions live in one array called `IPS_QUESTIONS` inside `index.html`
(search the file for `window.IPS_QUESTIONS`). Each entry is commented with its fields,
so you can copy a block and add your own. Commit the change and GitHub Pages updates automatically.

---

## Files

| File | What it is |
|------|-----------|
| `index.html` | The entire trainer (app + questions, self-contained) |
| `IPS_Study_Notes.md` | Full study notes for the course (linked from the app footer) |
| `README.md` | This file |

Good luck with the exam.
