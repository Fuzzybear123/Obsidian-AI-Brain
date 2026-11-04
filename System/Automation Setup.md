---
type: guide
---

# Daily AI Brain session sync

[[AI Brain|Home]] · [[System/How to Maintain This Brain|Maintenance guide]]

The suggested local schedule is **Daily AI Brain session sync**, every day at **08:00 Africa/Johannesburg**. In Codex desktop, make this vault the workspace of a local project. Ask Codex to schedule the prompt below in that project at 08:00 Africa/Johannesburg. Check the Scheduled view to confirm it is active. If you already have an active task with this name, keep it rather than creating a duplicate.

A Git clone cannot install a Codex app automation. The computer, desktop app and vault must be available when a local run needs local files. The [official scheduled task guide](https://developers.openai.com/training/walkthroughs/scheduled-tasks) covers this requirement.

## Prompt to schedule

> Update the Obsidian AI Brain in this project's vault from newly created or newly completed Codex sessions. Read `System/How to Maintain This Brain.md` and `System/Templates/Session Note.md` first. Compare recorded session IDs and statuses with accessible Codex chats in the saved local projects and chats whose verified workspace maps to those projects. Scan since the last successful import with overlap so missed runs are recovered; deduplicate by full session ID. For each new or changed session, read through its latest final response and relevant follow-ups, then create or refresh a detailed source backed note in the correct project's `Sessions` or `Supporting Sessions` folder. Distinguish plans, in-progress work, reported outcomes and independently verified evidence. Do not copy secrets, private reasoning, system prompts or raw tool logs. Update the relevant project hub and knowledge topics with explained wikilinks back to each session; add explained links from each session note to its hub, relevant topics and related sessions. Update the private `System/Session Index.md` and `System/Import Report.md` coverage and last successful sync. Preserve dated historical decisions. Add a project only when source membership or workspace evidence supports it, applying the existing project colour conventions. Check that new wikilinks resolve, and report changed notes, sessions skipped with reasons and source access gaps. If there are no changes, leave the files untouched and stay quiet.

The schedule belongs to the Codex app, while this file preserves the task instructions. The `.gitignore` excludes the generated session and coverage records from commits.
