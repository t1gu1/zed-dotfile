# Zed Editor - dotfile

<img width="2560" height="1440" alt="image" src="https://github.com/user-attachments/assets/f66bc248-4cc4-42e6-ab33-929f1a523504" />

## How to install

- Install Zed Editor from the official website
- Clone this repository `cp -r ~/.config/zed ~/.config/zed-old &&rm -r ~/.config/zed && git clone git@github.com:t1gu1/zed-dotfile.git ~/.config/zed/`
- Install fonts in from the `fonts` folder oh this repository

## Extensions

- Theme: `Catppuccin - Macchiato`
- Icon theme: `Soft Charmed Icons`

## AI agent info

We are in a Zed Editor config dotfile and we are editing keymap and settings.

I have the vim mode activated.

## Keybindings

Here is a list of all the custom keybindings defined in `keymap.json`.

### Context: `Workspace` (More general)

| Keybinding | Action |
|---|---|
| `ctrl-s` | `workspace::Save` |
| `escape` | `project_panel::CollapseAllEntries` |

### Context: `ProjectPanel || vim_mode == normal || EmptyPane && !menu && !Dock && !Editor`

| Keybinding | Action |
|---|---|
| `space e` | `project_panel::ToggleFocus` |
| `space E` | `["workspace::SendKeystrokes", "space e ctrl-alt-cmd-c"]` |
| `space t` | `workspace::ToggleBottomDock` |
| `space f f` | `file_finder::Toggle` |
| `space g g` | `git_panel::ToggleFocus` |
| `space g p` | `git::Pull` |
| `space g P` | `git::Push` |
| `space g s` | `git::StageAll` |
| `space g c` | `git::Commit` |
| `space a` | `agent::ToggleFocus` |
| `space f r` | `["pane::DeploySearch", { "replace_enabled": true }]` |
| `space f w` | `pane::DeploySearch` |
| `space f p` | `projects::OpenRecent` |
| `ctrl-s` | `workspace::Save` |
| `ctrl-]` | `pane::ActivateNextItem` |
| `ctrl-[` | `pane::ActivatePreviousItem` |
| `cmd-]` | `pane::ActivateNextItem` |
| `cmd-[` | `pane::ActivatePreviousItem` |
| `ctrl-{` | `pane::SwapItemLeft` |
| `ctrl-}` | `pane::SwapItemRight` |
| `cmd-{` | `pane::SwapItemLeft` |
| `cmd-}` | `pane::SwapItemRight` |
| `space c` | `pane::CloseActiveItem` |
| `ctrl-w` | `pane::CloseActiveItem` |
| `cmd-w` | `pane::CloseActiveItem` |
| `ctrl-W` | `["pane::CloseInactiveItems", { "close_pinned": false }]` |
| `cmd-W` | `["pane::CloseInactiveItems", { "close_pinned": false }]` |
| `space C` | `["pane::CloseInactiveItems", { "close_pinned": false }]` |
| `space [` | `["pane::CloseItemsToTheLeft", { "close_pinned": false }]` |
| `space ]` | `["pane::CloseItemsToTheRight", { "close_pinned": false }]` |

### Context: `vim_mode == visual || vim_mode == normal`

| Keybinding | Action |
|---|---|
| `space /` | `["editor::ToggleComments", { "advance_downwards": false }]` |
| `shift-up` | `editor::MoveLineUp` |
| `shift-down` | `editor::MoveLineDown` |
| `shift-k` | `editor::MoveLineUp` |
| `shift-j` | `editor::MoveLineDown` |
| `ctrl-a` | `editor::SelectAll` |
| `cmd-a` | `editor::SelectAll` |
| `ctrl-1` | `["pane::ActivateItem", 0]` |
| `ctrl-2` | `["pane::ActivateItem", 1]` |
| `ctrl-3` | `["pane::ActivateItem", 2]` |
| `ctrl-4` | `["pane::ActivateItem", 3]` |
| `ctrl-5` | `["pane::ActivateItem", 4]` |

### Context: `Terminal`

| Keybinding | Action |
|---|---|
| `escape` | `workspace::ToggleBottomDock` |
| `ctrl-1` | `["pane::ActivateItem", 0]` |
| `ctrl-2` | `["pane::ActivateItem", 1]` |
| `ctrl-3` | `["pane::ActivateItem", 2]` |
| `ctrl-4` | `["pane::ActivateItem", 3]` |
| `ctrl-5` | `["pane::ActivateItem", 4]` |
| `ctrl-left` | `pane::ActivatePreviousItem` |
| `ctrl-right` | `pane::ActivateNextItem` |
| `cmd-left` | `pane::ActivatePreviousItem` |
| `cmd-right` | `pane::ActivateNextItem` |
| `ctrl-t` | `workspace::NewTerminal` |
| `ctrl-h` | `pane::ActivatePreviousItem` |
| `ctrl-l` | `pane::ActivateNextItem` |
| `cmd-t` | `workspace::NewTerminal` |
| `cmd-h` | `pane::ActivatePreviousItem` |
| `cmd-l` | `pane::ActivateNextItem` |
| `ctrl-a` | `workspace::NewTerminal` |
| `ctrl-d` | `pane::CloseActiveItem` |
| `cmd-a` | `workspace::NewTerminal` |
| `cmd-d` | `pane::CloseActiveItem` |
| `ctrl-f` | `workspace::ToggleZoom` |
| `cmd-f` | `workspace::ToggleZoom` |
