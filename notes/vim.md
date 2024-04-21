Cheat Sheet

<leader> = (space)

------------------------------------------------------------------------------------------

General Vim

d                   ->      delete selected
(g + g) + (=G)      ->      Re indent the file from the current line to the end of the file


------------------------------------------------------------------------------------------

Files


CTRL + p            ->      Find files by name (find_files)
<leader> + f + g    ->      Find text from files (live_grep)

------------------------------------------------------------------------------------------

NeoTree (Solution Explorer)

a                   ->      Create a new file OR directory. Add a '/' to the end of the name to make a directory
CTRL + n            ->      Reveal Filesystem on the left (:Neotree filesystem reveal left<CR>)


------------------------------------------------------------------------------------------

LSP Config

K                   ->      Displays hover information about the symbol under the cursor
<leader> + g + d    ->      Jumps to the definition of the symbol under the cursor
<leader> + g + r    ->      Opens up references to the symbol under the cursor
<leader> + c + a    ->      Opens up Code Action menu (similar to Ctrl + . in vscode)

------------------------------------------------------------------------------------------

none-ls

<leader> + g + f    ->      Auto formatter