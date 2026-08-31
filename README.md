## Matteo De Angelis

Computer Engineering, University of Miami. Most of what I build started as something I
wanted to exist and couldn't go buy — which is how a fantasy football league ends up with a
constitution, and a Sunday afternoon ends up on Cloud Run.

---

### 🏟️ Fantacarriera

Eight of us play fantasy football in a world that doesn't reset every August. Clubs carry
multi-year contracts, a wage bill, three ledgers, a stadium and a youth squad, so selling a
striker in October is still costing you in two seasons' time.

The rules are a written constitution — 41 chapters, amendable by vote — and the software is
what enforces them. That's the part I find genuinely fun: turning a document eight humans
argue about into code that can't be argued with.

Next.js 16 + FastAPI + Firestore, both services on Cloud Run. Six months, solo: 1,193
commits, ~192k lines, 347 test files, 68 architecture decisions written down before the
code that implements them.

**→ [Walk through the live app](https://fantacarriera.app)** — click *Esplora la Lega*: no
signup, real data, controls switched off.
**→ [What it is and how it's built](https://github.com/teodea/fantacarriera)**

*(The source stays private — a real league plays in there.)*

---

### The rest

| | |
|---|---|
| **[jethr-task](https://github.com/teodea/jethr-task)** | Italian gross-to-net salary calculator. Every line of the tax waterfall, each with its plain-language explanation and the law it comes from — because the interesting part of a payslip is *why*, not the total. 7,896 municipalities. [Live](https://teodea.github.io/jethr-task/) · zero dependencies · [what it deliberately leaves out](https://github.com/teodea/jethr-task/blob/main/docs/ASSUNZIONI.md) |
| **[automated-soccer-vision](https://github.com/teodea/automated-soccer-vision)** | Tactical analysis from single-camera broadcast footage — YOLOv11 detection, ByteTrack IDs, jersey-colour team assignment, camera stabilisation, and a homography to top-down pitch coordinates so the speeds come out in real metres |
| **[digital-wallet](https://github.com/teodea/digital-wallet)** · **[snake-de1soc](https://github.com/teodea/snake-game-de1soc-controlled)** | A wallet protocol over raw TCP sockets, and Snake in C driven by the accelerometer on a DE1-SoC board. The other end of the stack, from back when the fun was making the hardware blink |

---

### Habits

Write the decision down before the code, so there's something to argue with later. Prefer
the boring solution that ships. Make the money math atomic. Assume it'll run at 3am with
nobody watching — because it does.

**Italian · English · Spanish**
