# ROADMAP.md — main roadmap (**read this first, every session**)

> **Layers** (the further down, the less you read):
> **L0** project memory file (auto-injected, pointer only)
> → **L1 this file** (main roadmap, hard cap **6000 chars**, **the only mandatory read**)
> → **L1.5** `ROADMAP.archive.md` (history, uncapped, reached by pointer)
> → **L2** `findings.md` / `task_plan.md` / `progress.md` (**grep to locate — never read end-to-end**)
> → **L3** daily logs (rarely read)
>
> Hitting the cap? Move sections that no longer affect the *next* decision into
> `ROADMAP.archive.md` and leave one conclusion line + pointer here.
> Verify with `python scripts/roadmap_check.py` (non-zero exit = fail).

## 0. Session ritual (do not skip)

1. **Read this file.** L2 is already huge; reading it end-to-end will crowd out the task.
2. Need detail? Follow a pointer below and **grep** L2 for that one section.
3. At wrap-up: update "Next" below, append findings, **run `roadmap_check.py`**.

## 1. Non-negotiable rules (user's hard requirements)

<!-- Keep to ~5. These are the rules you refuse to violate even if this file were missed. -->

- ...
- ...

## 2. Where things are / what may be touched

| Area | Detail lives in | Status | **Editable layer** |
|---|---|---|---|
|  |  |  |  |

## 3. Working rules (judgement-level; full text in findings.md)

<!-- One line each. Pointers (`F12`, `§18.1`) let roadmap_check.py prove they still resolve. -->

- ... → `Fxx`
- ... → `§xx`

## 4. Environment facts (measured — stop re-testing them)

- ...

## 5. Done → conclusions still in use (history: `ROADMAP.archive.md`)

| Item | Conclusion still needed | Pointer |
|---|---|---|
|  |  |  |

## 6. Next (**exactly one place to start**)

**...** — one sentence, plus where its spec lives (`task_plan.md §xx`).

## 7. Blocked / waiting on the user (do not touch)

- ...
