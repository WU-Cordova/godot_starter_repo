# CS 276 · Lab N: Lab Title

<!--
  INSTRUCTOR NOTE (delete before publishing a lab's template):
  This repo is the base starter template for CS 276 lab assignment repos
  (Classroom50). Per lab: update the title above, fill in the Overview,
  add the lab's starter Godot project at the repo root, and update the
  "What's in this repo" table. Everything else is lab-agnostic.
-->

![Godot 4.5](https://img.shields.io/badge/Godot-4.5-478cbf?logo=godotengine&logoColor=white)
![Course](https://img.shields.io/badge/CS%20276-Game%20Systems%20in%20Godot-ff2e97)

**This repository is your personal submission repo for this lab.** It was created for you when you accepted the assignment link, and it is named after the classroom, the assignment, and your GitHub username. Only you and the instructor can see it.

> **The Canvas assignment page is the authoritative spec** for this lab: full instructions, the grading rubric, and the due date all live there. This README covers the mechanics that are the same for every lab.

## Overview

*One paragraph describing this lab's goal and the system it exercises. See the Canvas assignment for the complete instructions.*

## What's in this repo

| Path | What it is |
| --- | --- |
| `project.godot` | The starter Godot project. Open this in Godot 4.5. *(Lab 0 has no starter project: you create one here.)* |
| `.gitignore` | Keeps Godot's build cache (`.godot/`) and exports out of version control. Leave it alone. |
| `README.md` | This file. |

## Requirements

- **Godot 4.5** — the standard build, not the .NET build. We pin 4.5 for the whole term; do not upgrade mid-semester, even if the editor offers.
- **git** — and a GitHub account that has accepted the course organization invite.

## Getting started

1. **Clone this repo** (from the green *Code* button, or `git clone <url>`).
2. **Open the project in Godot:** launch Godot 4.5 → *Import* → select this repo's `project.godot`. For **Lab 0**, instead create a new project *at the root of this repo* (choose this folder as the project path).
3. **Run it:** `F5` runs the project's main scene; `F6` runs whichever scene you have open. If a lab's starter project runs before you change anything, you are set up correctly.

## How to submit

**Pushing to `main` is submitting.** There is no separate upload step for the repo itself (some labs also ask for a screenshot or short reflection in Canvas — check the assignment page).

```bash
git add .
git commit -m "Describe what you changed"
git push
```

- **Commit early and often**, with messages that say what changed. Your commit history is part of the graded evidence that the work is yours and grew over time.
- Whatever is on `main` at the deadline is what gets graded. **Verify on github.com** that your latest push is actually there.
- If autograding is configured for the lab, results appear on your assignment's *My Submission* page after each push.

## Your Submission

**Complete this section before the deadline** — it is part of your graded submission. Edit this README directly.

### Screenshot

Take the screenshot the lab's Canvas page asks for, commit it to this repo (e.g. `screenshot.png`), and embed it by replacing the placeholder below:

![My screenshot](screenshot.png)

### Reflection

*Replace this line with the short reflection the lab's Canvas page asks for.*

## Repo rules

- Never commit the `.godot/` folder or exported builds; the `.gitignore` handles this, so do not delete or edit it.
- Keep the Godot project **at the root of the repo** (that is where `project.godot` belongs).
- Commit all scenes (`.tscn`), scripts (`.gd`), resources (`.tres`), and assets your project needs; a clone of your repo must open and run on the instructor's machine.

## Assets and credits

You may only use third-party art, audio, or fonts that you have the **right** to use (public domain, Creative Commons, or a license you hold). Every asset you did not create must be listed here:

| Asset | Source | License |
| --- | --- | --- |
| *(example)* `coin.png` | [Kenney](https://kenney.nl/assets) | CC0 |

Shipping uncredited or unlicensed assets is an academic honesty violation in this course. Free, safe sources are listed on the course Resources page in Canvas.

## Academic honesty

Labs are **individual**. Discussing concepts and debugging strategies is encouraged; copying code from classmates, previous semesters, or elsewhere is not. Generative AI may help you explore and study, but you must be able to **explain, reproduce, and defend** everything you submit, and any AI assistance must be **disclosed** in your submission. See the syllabus for the full policy.

## Getting help

Bring questions to class, come to **student hours** (current times and booking at [lpcordova.phd/meet](https://lpcordova.phd/meet)), or email [LPCordova@willamette.edu](mailto:LPCordova@willamette.edu). Setup problems are exactly what student hours are for — bring your laptop.
