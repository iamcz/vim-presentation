# Usage

NOTE: you can prepend almost any command with a number to specify exactly how many times you would
like it to be performed.

## Navigation
- words and Words (foo: :bar -- 4 words, 2 Words)
- Commands: w -- word, e -- end, b -- back (capitalize any to use Words)
- character searching: f -- forward search in line for character
- ^ -- beginning of line, $ -- end of line
- / -- search forward for text or regex (NOTE: incsearch is on) -- (? searches in reverse)

## Editing
- Some of the most common commands:
  - i -- enter insert mode at cursor
  - I -- enter insert mode at beginning of line
  - a -- enter insert mode after cursor
  - A -- enter insert mode at end of line
  - o -- enter insert mode on newline below
  - O -- enter insert mode on newline above
- Normally users make an edit small edit in insert mode then return to Normal mode
- delete -- d + motion (dd for line deletion)
- change -- c + motion
- paste -- p
- all deletions including ones from changes get put into the registers (I think the last 10 are
  stored -- view with `:registers`)
- yank (copy) -- y + motion
- prepend "{register_name} to specify a register to put the copied text into
- redo -- <C-r> in normal mode
- replace - r
- togglecase
- undo -- u in normal mode or <C-u> in Insert mode

## Macros

