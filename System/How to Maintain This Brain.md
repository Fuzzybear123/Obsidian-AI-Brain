---
type: guide
---

# How to Maintain This Brain

[[AI Brain|Home]] · [[System/Automation Setup|Daily sync]] · [[System/Templates/Session Note|Session template]]

## Add a session with evidence

Read the source chat through its latest final response and relevant follow-ups. Match it to the correct saved Codex project; when project ID is absent, use a verified workspace match. Put main work in that project's `Sessions` folder and child work in `Supporting Sessions`. Name the note with its date, source title and a unique session ID suffix.

Explain the request, discoveries, actual changes, validation and limits. Label plans and in-progress work clearly. Record what the source reported separately from checks you independently reran. Do not copy credentials, raw tool logs, private reasoning or system instructions.

Link the session to its project hub and relevant knowledge topics. Update those topics and the hub with a sentence explaining each connection. Preserve older notes as dated evidence when later sessions change an outcome.

## Keep project colours consistent

The six project colours are defined in each hub's `project_color` and `cssclasses` properties, `.obsidian/snippets/ai-brain-projects.css`, `.obsidian/graph.json`, and `AI Brain Map.canvas`. When adding or renaming a project, update those four places together. Toggle the snippet in **Settings → Appearance → CSS snippets** if Obsidian does not show it.

## Daily update

Follow [[System/Automation Setup]] to set up the 08:00 Africa/Johannesburg local task. Each run compares full session IDs, revisits in-progress notes, and checks for follow-ups to existing chats. It updates private coverage records only after a successful review. If source access fails, leave the previous success marker unchanged and report the gap. A chat with no new evidence should not create a duplicate note.

## Publication boundary

The `.gitignore` keeps session records and generated coverage files local. Project hubs and knowledge notes are tracked once added or edited, so review staged content before publishing.
