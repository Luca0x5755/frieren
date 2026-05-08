# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this repository is

This is a **Traditional Chinese (Taiwan) fanfiction project** — not a code repository. It rewrites the 177 AI/ML technologies on the iPAS AI 應用規劃師 exam (科目一+科目三) as "lost ancient magic" inside the world of *Sousou no Frieren* (《葬送的芙莉蓮》). Output is prose `.md` files. There is no build, test, or lint pipeline; "running" the project means writing the next chapter to spec.

Output language is **繁體中文（台灣）**. Internal reasoning should be in Japanese to stay close to the source work's語感. Technology names stay in English (e.g. `Transformer`, `BERT`) — they ARE the in-world spell true-names.

## Authoritative files (precedence order — never violate)

1. **`todo-list.md`** — single execution entry point. Contains the full rule corpus (§A.1–§A.11), per-chapter writing checklists (§B.1–§B.4), grep-style validation rules (§C), and the Phase 0–11 task list. Read §A whenever writing or reviewing a chapter.
2. **`novel/00_十季時間軸總覽.md`** — authoritative chapter↔technology↔character map across S1–S10, plus tech dependency lineage and breath-chapter (呼吸章) placement.
3. **`novel/00_情感伏線表.md`** — cross-season emotional foreshadowing register (F-001…F-006). Maintained **independently** from the technical dependency chain. Per `§A.10`, emotional callbacks outweigh technical callbacks for cross-chapter resonance.
4. **`科目一技術表.md` / `科目三技術表.md`** — the merged 177-technology pool. The "考試重點" column is the **心像封印關鍵條件** (mental-image seal conditions). Treat both files as a single pool; do not invent technologies outside them.

If these conflict, escalate rather than guess.

## Per-season folder layout

Each season is an independent work unit; you can start/ship a season without others being done. Folder name pattern: `novel/S{N}_{季別標題}\` (e.g. `S1_萬法之祖`, `S2_檢定與資訊`, `S5_中古復興上`).

Inside each season folder:
- `00_S{N}_章節大綱.md` — planning-version outline (per `§A.11`); rewritten to a finished-summary version in Phase 11-3.
- `99_S{N}_心像真名索引.md` — true-name index for that season's technologies. Trial chapters and breath chapters do **not** add new entries — trial chapters annotate "整合自 S{x}E{y}" in the notes column; breath chapters are absent from the index entirely.
- `S{N}E{M}_{中文技術名稱}.md` — chapter body. Multi-technology composite chapters use `・` to join names.
- `S{N}E{M}_{中文技術名稱}_片尾.md` — required end-credits skit (200–600 字, dialogue-driven, must contain the technology's English true-name and skewer its most-mistaken exam point). Breath chapters are exempt.
- `S{N}E{M}_息吹_{場景關鍵字}.md` — breath chapter (one per season, 800–1500 字, no technology, exempt from the seven-material rule).

## The 4-step write-in flow (`§A.11`)

For every chapter:
1. Write the chapter body `.md`.
2. Write the `_片尾.md` skit (skip for breath chapters; trial/silence chapters use a "整合回顧型" recap skit).
3. Update that season's `99_S{N}_心像真名索引.md` (skip for trial/breath chapters).
4. If the chapter plants or recovers an emotional foreshadow, update `00_情感伏線表.md` §1's "強化／回收節點" column.

Then report `已寫入 {path}` plus a short summary in the conversation — never paste the full chapter back.

## Hard rules that are easy to break

These are the violations that recur most often. Full rules live in `todo-list.md §A`.

- **Magic-user rigidity (`§A.2`, `§A.10`)**: Stark (修塔爾克, warrior) and Himmel (辛美爾, hero, in flashback) **never cast magic**. Their sections must show體術／戰士直覺／勇者判例 instead. Don't write "咒紋浮現" or "魔力軌跡" in their POV.
- **No spell incantation (`§A.2`)**: Frieren-world magic is silent心像 (mental image). The English technology name is spoken at confirmation only (e.g. `「⋯⋯Transformer。」`). Don't invent German/古語 names alongside the English true-name.
- **Body-text starting rule (`§A.8.1`)**: chapter body opens **directly into story** — scene, action, or dialogue. The chapter title is the only allowed heading. **No** `情感伏線：…` / `首發型｜芙｜…` metadata lines, **no** `(a)`–`(g)` markers, **no** seven-material section headers, **no** explicit subheadings, **no** `---` separators. Metadata only lives in `00_S{N}_章節大綱.md` and `99_S{N}_心像真名索引.md`.
- **Word-count floors (`§A.8`)**: technical chapter ≥3,500 字 (composite ≥4,500); trial/finale ≥5,000; breath chapter 800–1500. Treat shortfalls as violations — pad with emotional/sensory beats, not extra exposition.
- **Math density (`§A.8.1`)**: ≤2 explicit formulas per chapter; each must have ≥1 emotional/action/scene buffer段 within 200 字 on either side.
- **Two-layer naked-problem opening (`§A.6.1`)**: chapter must expose both a現象難題 and a結構難題 before the technology's true-name is spoken. The結構難題 must be voiced by a character (usually Fern), not narrated.
- **Socratic beat (`§A.6.2`)**: before the true-name is named, Frieren must deliver ≥1 question-form correction (ends in `？`), not just declarative ones.
- **Structural self-proof loop (`§A.6.3`)**: after the true-name, ≥1 "現場觀察 → 公式結構回扣" passage where on-the-ground detail retroactively justifies the formula's shape. Pure forward application doesn't count.
- **Skipped-concept ledger (`§A.6.4`)**: if Frieren's lazy "沒事" / "就那樣" skips a concept, the chapter outline's 踩坑覆蓋清單 must register where it gets recovered (a重識章 or伏線回收章 in the same season). Don't leave concepts permanently dangling.
- **Dialogue ratio (`§A.9` table)**: 一般技術章 ≥60%, 戰鬥／試煉 ≥55%, 修行章 ≥40%, 回憶章 ≥30%, 呼吸章 unconstrained. Each speech turn ≤3 sentences; monologues ≤4 lines.

## Character voices (`§A.9`, do not blur)

- **芙莉蓮**: very short sentences, 慵懶毒舌, frequent `⋯⋯` pauses. Demonstrates once or drops one corrective line; never lectures.
- **費倫**: polite, precise, the reader-stand-in. She asks "為什麼" / "可是如果⋯⋯呢" and is the one who actually steps on the trap before being corrected.
- **修塔爾克**: 外強中怯, retreats verbally ("這個⋯⋯不會出事吧？"), blushes at 費倫. Not a hot-blooded idiot. Demonstrates engineering concepts via體術／戰斧／隊形.
- **辛美爾 (回憶)**: warm, idealistic. "當年我們⋯⋯" frame. Carries ethics/regulation/security via human choices, not magic.

## Validation knobs (`§C`)

Before declaring a chapter done, the §C grep-style checks are the cheapest way to catch violations: presence of the English true-name, absence of `---`, absence of `(a)`–`(g)`, absence of metadata header lines, formula count ≤2, character-magic prohibitions for Stark/Himmel sections, word-count floor, and matching `_片尾.md` existence. Run these mentally before reporting completion.

## Current state (as of 2026-05-08)

Phase 0 (skeleton: timeline, foreshadow table, per-season大綱／索引 骨架) is complete. **S1E01〈貝氏定理〉is the only finished chapter**; S1E02–S1E10 and S2–S10 are all open. Always check the latest commit and the unchecked `[ ]` items in `todo-list.md` Phase N to know what's next, rather than assuming from this file.
