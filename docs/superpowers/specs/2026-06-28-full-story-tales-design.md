# Design — "Full Story" memorable tales for all 5 CPS chapters

**Date:** 2026-06-28
**Goal:** The current notes are detailed but *fragmented* (story snippet + bullet list + hook, repeated per concept). The user can read them but cannot **remember** them, because there is no single connected narrative to replay. Add one flowing, vivid story per chapter so understanding (and recall) comes from the plot itself — while keeping every existing exam point.

## What we are adding (additive — nothing is removed)

For each chapter (1–5), add a new **"📖 The Full Story"** section to **both**:
- the live `N_study.html` study page, and
- the `N_memorize.md` source file.

The section contains:
1. **One continuous adventure tale** — a real plot using the chapter's existing characters
   (Robi & Cy the owl · Pip the parrot & Mira · Riku · Ada & "Volt" · Maya & Jack).
   Every plot beat introduces a concept *because the story needs it*, in **exam order**, so
   concepts are understood, not just listed. Exam-critical terms are highlighted inline.
2. **A compact "story beat → exam point" map** (a table) linking each beat back to the precise
   thing to write in the exam.

The existing sections stay untouched: skeleton Map, 🎬 Memory Movie, 📖 Lesson (story + **Write-in-exam**
cards), Flashcards, Practice Questions, Cheat-card. The deep exam bullets already live there, so
"keep exam points" needs nothing removed — the tale is the new *understand-once* layer on top.

## Placement & wiring (per `N_study.html`)

- Insert the new `<section id="story">` **between** `#map` and `#movie`
  (read the full story to understand → Movie is the compressed replay → Lesson is the exact points).
- Add a nav tab `📖 Story` to `nav.tabs`, between **Map** and **🎬 Movie**.
- Reuse existing CSS classes; add a small `.tale` style block (reading column, drop-cap, beat
  labels, highlighted terms) and ensure it prints (PDF) cleanly.

## Pedagogical flow the reader follows

**Read the Full Story once to UNDERSTAND → drill the existing exam points / flashcards / cheat-card to PASS.**

## Rollout

All 5 chapters, starting with **Ch 1 (System Engineering)** — the densest, so if the tale format
works there it works everywhere. Each chapter's tale matches its existing characters and concept order.

## Out of scope

No new factual content beyond the existing notes (exam accuracy preserved). No redesign of existing
sections. No changes to flashcards/practice/cheat-card.
