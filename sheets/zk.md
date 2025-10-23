# zk - A plain text note-taking assistant

[Github](https://github.com/zk-org/zk)

My Requirements:
- Simple, local markdown
- Note filenames with dot hierarchy
- Powerful search
- Backlinks
- Notes templates (meeting minutes, standup, ...)
- Extremely fast to jump around

## Setup

```
zk init ~/Hack/zk-notebook

alias zk="zk --working-dir ~/Hack/zk-notebook"
```

## Usage

**Approach to namings**:
- Use short ids
- Title is a dot-based hiearchy, meant to be easy to autocomplete and search
- Document start with frontmatter

```yaml
---
title: life.data.detox
date: 2024-09-14 23:02:00
tags: [life, data, digital]
---
```

- Then a `# Actual pretty title`

**Create a new note**: `zk edit --interactive --match "something"` (`CTRL-E` to edit with that title)

**List notes**: `zk list --no-pager --format oneline --sort modified --interactive`

### Other useful notes

**List tags**: `zk list tags`

## Neovim integration [zk-nvim](https://github.com/zk-org/zk-nvim)

[Work in progress](https://github.com/zk-org/zk/issues/22)

- `:ZkNotes` opens a note picker
- See also `ZkBacklinks`, `ZkLinks`
- Wikilink preview: `Shift-k`
- Open a wilink: `gd` (go to definition)
- Create a new link: Highlight the text, then code action `leader + l + a`


