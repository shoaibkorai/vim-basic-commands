# Vim Command Reference

This document provides a reference to basic Vim commands, ranging from navigation to advanced file operations. Each command is accompanied by a brief description.

## Navigation
**h:** Move left.

```vim
h
```

**j:** Move down.

```vim
j
```

**k:** Move up.

```vim
k
```

**l:** Move right.

```vim
l
```

**w:** Move to the start of the next word.

```vim
w
```

**b:** Move to the start of the previous word.

```vim
b
```

**e:** Move to the end of the current word.

```vim
e
```

**0:** Move to the beginning of the line.

```vim
0
```

**$:** Move to the end of the line.

```vim
$
```

**gg:** Move to the beginning of the file.

```vim
gg
```

**G:** Move to the end of the file.

```vim
G
```

## Editing
**i:** Insert mode before the cursor.

```vim
i
```

**a:** Insert mode after the cursor.

```vim
a
```

**o:** Open a new line below the current line.

```vim
o
```

**O:** Open a new line above the current line.

```vim
O
```

**x:** Delete the character under the cursor.

```vim
x
```

**dd:** Delete the current line.

```vim
dd
```

**yy:** Yank (copy) the current line.

```vim
yy
```

**p:** Paste after the cursor.

```vim
p
```

**P:** Paste before the cursor.

```vim
P
```

**u:** Undo.

```vim
u
```

**Ctrl+r:** Redo.

```vim
Ctrl+r
```

## Searching
**/word:** Search for 'word' forward.

```vim
/word
```

**?word:** Search for 'word' backward.

```vim
?word
```

**n:** Repeat the last search in the same direction.

```vim
n
```

**N:** Repeat the last search in the opposite direction.

```vim
N
```

## Substitution
**:s/old/new/:** Replace 'old' with 'new' on the current line.

```vim
:s/old/new/
```

**:%s/old/new/g:** Replace 'old' with 'new' throughout the file.

```vim
:%s/old/new/g
```

**:%s/old/new/gc:** Replace 'old' with 'new' throughout the file with confirmation.

```vim
:%s/old/new/gc
```

**:argdo %s/old/new/g | w:** Replace 'old' with 'new' in multiple files and save.

```vim
:argdo %s/old/new/g | w
```

## Visual Mode
**v:** Start visual mode (character-wise).

```vim
v
```

**V:** Start visual mode (line-wise).

```vim
V
```

**Ctrl+v:** Start visual mode (block-wise).

```vim
Ctrl+v
```

## File Operations
**:w:** Write (save) the file.

```vim
:w
```

**:q:** Quit Vim.

```vim
:q
```

**:wq:** Write and quit Vim.

```vim
:wq
```

**:q!:** Quit without saving.

```vim
:q!
```

**:e filename:** Open a file.

```vim
:e filename
```

**:saveas filename:** Save the file with a new name.

```vim
:saveas filename
```

## Buffers
**:bn:** Next buffer.

```vim
:bn
```

**:bp:** Previous buffer.

```vim
:bp
```

**:bd:** Delete (close) buffer.

```vim
:bd
```

**:ls:** List all buffers.

```vim
:ls
```

## Tabs
**:tabnew:** Open a new tab.

```vim
:tabnew
```

**:tabn:** Move to the next tab.

```vim
:tabn
```

**:tabp:** Move to the previous tab.

```vim
:tabp
```

**:tabc:** Close the current tab.

```vim
:tabc
```

## Windows/Splits
**:split:** Split the window horizontally.

```vim
:split
```

**:vsplit:** Split the window vertically.

```vim
:vsplit
```

**:close:** Close the current split window.

```vim
:close
```

**Ctrl+w h:** Move to the left split.

```vim
Ctrl+w h
```

**Ctrl+w j:** Move to the split below.

```vim
Ctrl+w j
```

**Ctrl+w k:** Move to the split above.

```vim
Ctrl+w k
```

**Ctrl+w l:** Move to the right split.

```vim
Ctrl+w l
```

## Marks
**m[a-zA-Z]:** Set mark [a-zA-Z] at the cursor position.

```vim
m[a-zA-Z]
```

**'[a-z]:** Jump to the mark [a-z].

```vim
'[a-z]
```

**'[A-Z]:** Jump to the mark [A-Z] in any file.

```vim
'[A-Z]
```

## Miscellaneous
**:help:** Open help documentation.

```vim
:help
```

**:help cmd:** Open help for the command 'cmd'.

```vim
:help cmd
```

**:!cmd:** Execute an external command 'cmd'.

```vim
:!cmd
```

**:set nu:** Show line numbers.

```vim
:set nu
```

**:set nonu:** Hide line numbers.

```vim
:set nonu
```

**:set hlsearch:** Highlight search results.

```vim
:set hlsearch
```

**:set nohlsearch:** Disable search result highlighting.

```vim
:set nohlsearch
```

**:set ignorecase:** Case insensitive search.

```vim
:set ignorecase
```

**:set noignorecase:** Case sensitive search.

```vim
:set noignorecase
```
