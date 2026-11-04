# Obsidian AI Brain

An Obsidian vault starter for organising Codex work by **project → knowledge topic → session**. It opens with six colour coded project hubs, a project map, note templates, and a repeatable daily session sync workflow. Obsidian core plugins are enough; no community plugin or API key is required.

## Open the vault

1. Clone this repository, or download and extract its ZIP.
2. In Obsidian, choose **Open folder as vault** and select the repository folder.
3. Open [AI Brain](AI%20Brain.md) or [the project map](AI%20Brain%20Map.canvas). If the colours do not appear, enable **Settings → Appearance → CSS snippets → ai-brain-projects**.
4. Open a project hub and replace its starter text with your own purpose and current state. Use the templates in `System/Templates` for knowledge and session notes.

The checked in Obsidian settings enable Graph, Backlinks, Canvas and Templates. Template folder: `System/Templates`. Your window layout stays local.

## Project colours

| Project | Colour |
| --- | --- |
| Project A | `#A78BFA` |
| Project B | `#06B6D4` |
| Project C | `#3B82F6` |
| Project D | `#F97316` |
| Project E | `#22C55E` |
| Project F | `#14B8A6` |

The same colours are set in each hub's `project_color` and `cssclasses` properties, the CSS snippet, the Graph groups and the Canvas map. To add or rename a project, update all four places; see [How to Maintain This Brain](System/How%20to%20Maintain%20This%20Brain.md).

## Daily session sync

A suggested local setup runs **Daily AI Brain session sync** at **08:00 Africa/Johannesburg** in a Codex project with this vault as its workspace. A clone does **not** install an app automation. Follow [Automation Setup](System/Automation%20Setup.md) to create or confirm the schedule using the included prompt. The local computer, Codex desktop app and vault must be available for local file updates. [OpenAI's scheduled task guide](https://developers.openai.com/training/walkthroughs/scheduled-tasks) explains the local availability requirement.

## Privacy

Session notes and supporting session notes are ignored by Git, along with generated session indexes, import reports, local Obsidian workspace state, backups and credential files. The starter contains no imported chat records, source IDs, local paths or secrets. Review `git status` and the staged diff before every push. Project hubs and knowledge notes are ordinary tracked files if you edit them, so review their content before publishing. The scheduled sync can update these tracked summaries.

## Layout

- `AI Brain.md` — home and project index.
- `AI Brain Map.canvas` — coloured project map.
- `Projects/<name>/<name>.md` — project hubs; create `Knowledge` and `Sessions` as needed.
- `System/Templates/` — note templates.
- `System/How to Maintain This Brain.md` — source and linking conventions.
- `System/Automation Setup.md` — local schedule and sync prompt.
- `.obsidian/` — shared Obsidian settings, Graph groups and CSS.
