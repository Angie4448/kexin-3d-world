# web3d-ILE

English | [中文](README.zh.md)

When students have already read the materials but still cannot settle on a project topic, do not hand them another article.

Let them walk through a first-person 3D world in the browser: **re-experience what they have just read**, collect film reels as the director, then write a few observations and check them against the original readings.

This repository is for **high-school STEM inquiry teachers**. No coding or code editor is required: fill in the form, paste the prompt into Doubao, DeepSeek, or WorkBuddy, and generate a world for that student.

`web3d-ILE` = **Web-based 3D Interactive Learning Environment**.

---

## What’s in the repo

| Path | What it is |
|------|------------|
| [`example/index.html`](example/index.html) | A complete, double-clickable example (six science directions + finale) |
| [`prompts/00-填写这份表.md`](prompts/00-填写这份表.md) | Teacher form: pseudonym, grade, device, reading summary, interests, participant / observer |
| [`prompts/01-发给通用AI.txt`](prompts/01-发给通用AI.txt) | Paste into Doubao / DeepSeek to get a downloadable `.html` file |
| [`prompts/02-发给工作搭子.txt`](prompts/02-发给工作搭子.txt) | Paste into WorkBuddy to get a shareable cloud link |

---

## Try the example first (about 15–25 minutes)

- Play online: <https://angie4448.github.io/web3d-ILE/example/>
- Or download [`example/index.html`](example/index.html) (`Download raw file`) and open it in **Chrome / Edge**. The engine is inlined; **no network is required**.

Controls:

| Key | Action |
|-----|--------|
| Click the view | Enter first person |
| `W A S D` | Walk |
| Mouse | Look around |
| `E` | Interact / enter a world / collect a reel |
| `R` | Return to the editing room |
| `Esc` | Release the mouse |

The example theme is nano-scale surface modification. All six playable directions are kept:

1. HZSM-5 zeolite micropores
2. Copper nano-forge (photocatalysis)
3. 3 µm wafer fab (lithography)
4. Deep mine · coal liquefaction + XGBoost
5. Dragon kiln · SiC engine (EBC coating, 1700°C)
6. LEO 400 km (AO-resistant PI)

Collect all six reels to unlock the finale, “Nano-scale surface modification.” Reels are the director’s personal record: **no leaderboard, no score comparison**.

> Names in this example are pseudonyms.

---

## Make a world for your student (no coding)

### Step 1. Fill in the form

Open [`prompts/00-填写这份表.md`](prompts/00-填写这份表.md) and fill it in for that student.

Do not put a real name, school name, gradebook, chat log, or the student’s raw notes into the form. The pseudonym is only for the end credits and reel record.

### Step 2. Pick one path

**Path A: a file the student can save**

1. Open Doubao or DeepSeek in the browser.
2. Paste the completed form, then paste all of [`prompts/01-发给通用AI.txt`](prompts/01-发给通用AI.txt).
3. Save the generated code as `Name-3D-world.html` (use the pseudonym).
4. Open it in Chrome, walk through it yourself, then send it to the student.

**Path B: a cloud link**

1. Open WorkBuddy.
2. Paste the completed form, then paste all of [`prompts/02-发给工作搭子.txt`](prompts/02-发给工作搭子.txt).
3. Send the student the preview / share link.

The prompts already ask for both PC and tablet: keyboard and mouse on a computer, on-screen joystick on a tablet. One page can include both and switch by device.

### Step 3. Write after playing

The 3D world does not replace reading. After leaving the site, the student writes on paper or in a document:

- What I did in each world
- Which passages of the reading it matches / does not match
- If I could keep only one topic, which one, and why

What the teacher collects is this written record, not the number of reels.

---

## Design rules to keep

1. **Read first, then enter 3D.** The site is a second pass through known material, not a new lesson.
2. **Directions come from what the student already cares about and has already read.** Do not invent a separate set of teacher driving questions and turn those into levels.
3. **First person.** The student is a molecule, particle, material, or on-site participant. If the form says observer, follow the camera; do not make a god-view strategy game.
4. **A reel is the director’s personal footage.** No ranking, no point board, no “who collected faster.”
5. **Pseudonym.** Do not put a real student name on the page, in the link, or in the file name.
6. **One page should work on both computer and tablet when possible.**

---

## Contributors

- Jerry Deng
- Eden Zhang

---

## License

The example page inlines [Three.js](https://threejs.org/) (MIT). The rest of this repository is also MIT; see [LICENSE](LICENSE). Please adapt it and share it with colleagues.
