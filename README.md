# My Cheatsheets

Patching CLI tools together to manage cheatsheets without getting lost.

## Installation

0. `brew install glow gum`
1. `git clone https://github.com/xav-b/cheatsheets`
2. `export CHEAT_WORKSPACE="$PWD/cheatsheets/sheets`
3. `cp cheatsheets/cheat /usr/local/bin`

## Usage

run `cheat` without argument to open the list and pick one. `cheat neovim` will open `$CHEAT_WORKSPACE/neovim.md`.

Folders are supported: `cheat python/pandas`

Simple. Enjoy and go back to work man.
