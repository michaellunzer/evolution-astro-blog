# Exercise Media — Gaps & Substitutions

Tracks where the [hasaneyldrm/exercises-dataset](https://github.com/hasaneyldrm/exercises-dataset) media
didn't have an exact match for an exercise in the workout posts. GIFs are vendored in `public/exercises/`
and referenced from the posts by slug filename.

**Scope:** Only **Weeks 1, 3, and 5** contain exercise lists and were illustrated. **Weeks 2, 4, and 6 are
reference weeks** ("do the same workout from week X, cut the rest time") — they link straight to the
illustrated week, so they were intentionally left unchanged.

## 🔴 Gaps — no suitable dataset match (need a fill-in image)

Each of these currently shows *"(demonstration image coming soon)"* in the post. Drop a `<slug>.gif` into
`public/exercises/` and add the `<img>` tag to the listed post(s).

| Exercise | Appears in | Why no match |
|----------|-----------|--------------|
| **Pec Deck** | wk1 Mon, wk3 Thu, wk5 Thu | Dataset has no machine pec-deck / pec-fly (only a pec *stretch*). |
| **Lying J Press** | wk3 Fri | Niche hybrid press; not in dataset. |
| **Body-Weight Squat** | wk5 Tue | No plain bodyweight/air-squat clip (only weighted or single-leg variants). |
| **Seated Dumbbell Swim and Row** | wk5 Thu | Niche movement; not in dataset. |
| **Bench Jump-Over** | wk5 Fri | Not in dataset (nearest is a one-leg box-jump). |

## 🟡 Substitutions — matched to a close-but-not-exact dataset movement (review)

These render fine but the animation is a near-equivalent. To swap, replace the file in `public/exercises/`
(keep the same filename — no post edits needed).

**Weeks 1 (recap):** grip-specific lat pull-downs / low rows → generic cable variants; V-bar &
straight-bar triceps extensions → cable pushdown; "Triple"/"Two-Arm"/"Rotating" dumbbell variants → the
standard movement; Reverse Lunge → dumbbell rear lunge; French Press → EZ-bar standing french press; Bar
Dip → parallel-bar triceps dip.

**Weeks 3 & 5 additions:**

| Exercise (post text) | GIF used (dataset source) | Note |
|----------------------|---------------------------|------|
| Standing Military Press | `standing-military-press.gif` — *barbell standing wide military press* | Wide-grip standing press. |
| Seated Military Press | `seated-military-press.gif` — *lever (machine) military press* | Machine, not free-bar. |
| Neutral-Grip Machine Overhead Press | `machine-overhead-press.gif` — *lever shoulder press* | Generic machine press. |
| Bulgarian Split Squat | `bulgarian-split-squat.gif` — *dumbbell single-leg split squat* | Rear-foot-elevated implied. |
| One-Leg Lunge | `lunge.gif` — *barbell lunge* | Shown with barbell. |
| Dumbbell Walking Lunge | `walking-lunge.gif` — *walking lunge* | — |
| Bench / Plyo / Narrow-Grip Push-Up variants | `push-up.gif` — *push-up* | Base push-up for all plyo/bench variants. |
| Diamond Push-Up | `diamond-push-up.gif` — *diamond push-up* | Exact. |
| Plyo / Traveling Squat Jump | `jump-squat.gif` — *jump squat* | Base jump squat. |
| Plyo / Body-Weight Step-Up | `dumbbell-step-up.gif` — *dumbbell step-up* | Base step-up. |
| Body-Weight Nosebuster / EZ-Bar Nosebuster | `nosebuster.gif` — *barbell lying triceps ext. (skull crusher)* | Skull-crusher stand-in. |
| One-Leg Bench Bridge | `glute-bridge.gif` — *glute bridge (two legs on bench)* | Two-leg version. |
| Box or Bench Jump | `box-jump.gif` — *box jump down w/ one-leg stabilization* | Closest jump clip. |
| Seated Dumbbell Row | `seated-cable-row.gif` — *cable seated row* | Cable, not dumbbell. |
| Standing Front-Lat Push-Down | `straight-arm-pulldown.gif` — *cable straight-arm pulldown* | Same movement. |
| Cable Chest Flye | `cable-chest-flye.gif` — *cable cross-over* | Standing cable fly. |
| Cable rear-delt raise / Cable Two-Arm Reverse Flye | `cable-reverse-fly.gif` — *cable cross-over reverse fly* | Shared clip. |
| Rope Front Raise | `cable-front-raise.gif` — *cable front raise* | Cable, generic attachment. |
| Dumbbell Front Raise and Lateral Raise | `dumbbell-front-raise.gif` — *dumbbell front raise* | Combo shown as front raise. |
| EZ-Bar Curl (outside/narrow grip) | `ez-bar-curl.gif` — *ez barbell curl* | Grip variants not distinguished. |
| One-Arm Lying Cross-Body Dumbbell Triceps Ext. | `one-arm-dumbbell-lying-triceps-extension.gif` | Cross-body not distinguished. |

## ✅ Strong/exact matches (no action needed)

Barbell/Dumbbell Incline & Bench Press, Pull-Up, Chin-Up, Push-Up, Deadlift, Barbell Bent-Over Row,
Dumbbell Bench Press, EZ-Bar Close-Grip Triceps Press, Overhead Rope Triceps Extension, Bench Dip,
Cable One-Arm Lateral Raise, Dumbbell Front Raise, Dumbbell Reverse Fly (rear delt), Rope Hammer Curl,
Preacher Curl, Barbell Pullover, Burpee, Barbell Reverse Curl, Arnold Press, One-Arm Cable Triceps
Extension — plus all Week 1 exact matches (bench press, squats, curls, raises, leg curl/extension, etc.).

---

**Media © [Gym visual](https://gymvisual.com/)** — see the dataset's `NOTICE.md` / `LICENSE` for media terms
before any commercial use.
