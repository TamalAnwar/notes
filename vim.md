# Vim command line editor

Vim is pre-installed in Ubuntu linux, just type `vi` to open the editor. 
-if not, just look it up on how to install it.

To open a file, type `vi hello.py`

Vim has COMMAND mode and an INSERT mode.

i to go to INSERT mode, esc to go to COMMAND mode.

Quit vim:
Command mode
`:q` or `:q!` to discard the changes.

Line numbers:
`:set number`

Delete line, undo, redo:
Command mode:
go to that line: `dd`
Undo: `u`
Redo: `ctrl r`
delete multiple lines: `3dd` -deletes 3 lines.

Search:
`/word`

Replace:
`:%s/word/newword/`

