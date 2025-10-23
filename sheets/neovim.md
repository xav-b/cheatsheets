# Neovim Cheatsheet

[Basic walkthrough](https://astronvim.com/Basic%20Usage/walkthrough)
[Default mapping](https://astronvim.com/Basic%20Usage/mappings)

## Navigation

**Toggle explorer**: `Space + e` (`Space + o` to focus)

**Quit all windows**: `Leader + Q`
**Close buffer**: `Leader + c`

**Telescope grep**: `Leader + fw`

**Toggle wrap**: `Leader + uw`

**Move to previous places**: Hit `'` and look at possible places for the second entries

## Code

**Commenting**: `Leader + /`

**Symbols Outline**: `Leader + lS`
**Search Symbols**: `Leader + ls`

**Blame Line**: `Leader + gl`

**Git Diff**: `Leader + gd`

**Disable autoformatting**: `Leader + uf`

## Terminal

**Open terminal**: `F7` or `Leader + tf`

**Horizontal Split Terminal**: `Leader + th`

**Node**: `Leader + tn`

**Python**: `Leader + tp`

**LazyGit**: `Leader + tl` | `Leader + gg`

**BTM**: `Leader + tt`


## Diagnostics

**Search symbols**: `Space + ls`
**Opening LSP symbols**: `Space + lS`

**Show line diagnostics**: `g + l`

**All Diagnostics**: `Leader + lD`

**Hover document**: `Shift + k`

**Go to definition**: `g + d`

**Code actions**: `Space + la`

**LSP Info**: `Leader + li`

**Null-ls Info**: `Leader + lI`

## Search

- **Word under cursor**: `leader fc` (live grep: `leader fW`)
- **Commands**: `leader fC`
- **Registers**: `leader fr`

## Split window

- Split horizontally: `CTRL-w s` or `\` (vertical: `|`)
- To navigate, use the usual `jk`, prefixed by CTRL-w
- Likewise, close with `CTRL-w q`
