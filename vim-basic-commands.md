# Basic Vim Commands

## Navigation
h         # Move left
j         # Move down
k         # Move up
l         # Move right
w         # Move to the start of the next word
b         # Move to the start of the previous word
e         # Move to the end of the current word
0         # Move to the beginning of the line
$         # Move to the end of the line
gg        # Move to the beginning of the file
G         # Move to the end of the file

## Editing
i         # Insert mode before the cursor
a         # Insert mode after the cursor
o         # Open a new line below the current line
O         # Open a new line above the current line
x         # Delete the character under the cursor
dd        # Delete the current line
yy        # Yank (copy) the current line
p         # Paste after the cursor
P         # Paste before the cursor
u         # Undo
Ctrl+r    # Redo

## Searching
/word     # Search for 'word' forward
?word     # Search for 'word' backward
n         # Repeat the last search in the same direction
N         # Repeat the last search in the opposite direction

## Substitution
:s/old/new/         # Replace 'old' with 'new' on the current line
:%s/old/new/g       # Replace 'old' with 'new' throughout the file
:%s/old/new/gc      # Replace 'old' with 'new' throughout the file with confirmation
:argdo %s/old/new/g | w   # Replace 'old' with 'new' in multiple files and save

## Visual Mode
v         # Start visual mode (character-wise)
V         # Start visual mode (line-wise)
Ctrl+v    # Start visual mode (block-wise)

## File Operations
:w        # Write (save) the file
:q        # Quit Vim
:wq       # Write and quit Vim
:q!       # Quit without saving
:e filename   # Open a file
:saveas filename  # Save the file with a new name

## Buffers
:bn       # Next buffer
:bp       # Previous buffer
:bd       # Delete (close) buffer
:ls       # List all buffers

## Tabs
:tabnew   # Open a new tab
:tabn     # Move to the next tab
:tabp     # Move to the previous tab
:tabc     # Close the current tab

## Windows/Splits
:split    # Split the window horizontally
:vsplit   # Split the window vertically
:close    # Close the current split window
Ctrl+w h  # Move to the left split
Ctrl+w j  # Move to the split below
Ctrl+w k  # Move to the split above
Ctrl+w l  # Move to the right split

## Marks
m[a-zA-Z]  # Set mark [a-zA-Z] at the cursor position
'[a-z]     # Jump to the mark [a-z]
'[A-Z]     # Jump to the mark [A-Z] in any file

## Miscellaneous
:help     # Open help documentation
:help cmd # Open help for the command 'cmd'
:!cmd     # Execute an external command 'cmd'
:set nu   # Show line numbers
:set nonu # Hide line numbers
:set hlsearch   # Highlight search results
:set nohlsearch # Disable search result highlighting
:set ignorecase # Case insensitive search
:set noignorecase # Case sensitive search
