# Minimal Obsidian Vault

## Philosophy

1. Low-code & Out of the box
	- No Code, No Learn, Just Use
	- TL;DR
	- Use native *Search* plugin instead of [dataview](https://github.com/blacksmithgu/obsidian-dataview) or similar query plugin. Obsidian Search provides syntax prompts without memory requirements
	- Use *properties* instead of `::` dataview-style fields. Properties are note-scoped/file-scoped/node-scoped; inline fields are block-scoped/line-scoped/content-scoped. The former is an implementation of **Graph Database**, which is easy to understand and extend (e.g. Static Site Generator)
2. Minimal plugins and options
	- Toooo much Plugins? No, just **10 simple plugins**
	- (see auto enabled plugins below)
	- TL;DR
	- Newbies are always afraid of the learning curve and huge plugins ecosystem of [Obsidian](https://obsidian.md), but it actually DOES NOT exist
	- I took thousands of notes and tried hundreds of plugins. Finally, I realize that there is no need to install so much 3rd plugins. Only about **10** third-party plugins must be installed, other plugins are unnecessary to write down the thousands of notes, or are extremely simple to use (if the amount of plugins increases, it's *natural and painless*)
	- So I create this *minimal* obsidian vault, which meets my requirements to write done *thousands of* notes
3. Graph Database
	- Use *properties* instead of content(markdown) as more as possible
	- Each note should be a *Node*(vertex) in graph database
	- Content makes no sense for a *graph*
	- On the contrary, properties can be node *attributions* or simulate *edges* in the graph

## Hotkeys

| Hotkey     | Description                                                                 |
| ---------- | --------------------------------------------------------------------------- |
| `Alt+Up`   | Move line up                                                                |
| `Alt+Down` | Move line down                                                              |
| `Ctrl+E`   | Toggle Live Preview/Source mode. Because reading mode is almost unnecessary |

## Recommended themes

| Name   | Light/Dark |
| ------ | ---------- |
| Wombat | 🌙         |

## Core plugins

| Core Plugin   | Enable/Disable | Description                                                                                                                                          |
| ------------- | -------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------- |
| canvas        | ❌              | alternatives to [excalidraw](https://github.com/zsviczian/obsidian-excalidraw-plugin) or [draw.io](https://github.com/jensmtg/obsidian-diagrams-net) |
| slash-command | ✅              |                                                                                                                                                      |
| workspaces    | ✅              |                                                                                                                                                      |

## Community plugins

| Plugin           | Auto enable | Group      | Idea                                           | Alternatives                                                                     |
| ---------------- | ----------- | ---------- | ---------------------------------------------- | -------------------------------------------------------------------------------- |
| Plugin Groups    | ✔           |            | Grouping plugins and auto enable these plugins | `Settings - Community plugins - Manually toggle button`                          |
| Multi Properties | ✅           | Properties | Add/remove properties for multiple notes       |                                                                                  |
| FuzzyTag         | ✅           | Properties | Frontmatter autocomplete in source mode        | Obsidian comes with autocomplete in live preview mode                            |
| Quick Tagger     | ✅           | Properties | Add/remove tags for multiple notes             |                                                                                  |
| TagsMany         | ✅           | Properties | Add/remove tags for multiple notes             |                                                                                  |
| Tag Wrangler     | ✅           | Properties | Rename tag                                     |                                                                                  |
| TagsFolder       | ✅           | Properties | Note explorer by tags                          |                                                                                  |
| Tags Overview    | ✅           | Properties | Note explorer by tags                          |                                                                                  |
| Diagrams.net     | ✅           | Diagrams   | Whiteboard                                     |                                                                                  |
| Excalidraw       | ✅           | Diagrams   | Whiteboard                                     | [excalidraw-ymjr](https://github.com/Bowen-0x00/obsidian-excalidraw-plugin-ymjr) |
| Kroki            | ✅           | Diagrams   | DSL diagrams in markdown fenced block          |                                                                                  |
| MathLive         | ❌           | Math       | Input math formula without LaTeX knowledge     |                                                                                  |
| Latex Suite      | ❌           | Math       | Preview LaTeX                                  |                                                                                  |
| Completr         | ❌           | Math       | Autocomplete `\` LaTeX macros                  |                                                                                  |
| Image Toolkit    | ❌           | Image      | View image                                     |                                                                                  |
| Hider            | ❌           | Editing    | Hide status bar etc                            |                                                                                  |
| Style Settings   | ❌           | Editing    | Config for many themes                         |                                                                                  |
| Tray             | ❌           | Editing    | Close Obsidian to tray bar                     |                                                                                  |
