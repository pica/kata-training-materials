## Exiting

`:w` save the file  
`:q` quit  
`:q!` quit and throw away unsaved changes  

## Searching

`/<pattern>` find pattern  
`n` repeat the last search  
`:s/this/that/c` replace 'this' with 'that' throughout the file, with confirmation  

## Copying/Cutting/Pasting

`yiw` yank the current word into the buffer  
`yy` yank the current line into the buffer  
`p` paste  
`P` paste above  
`diw` delete current word  
`dd` delete current line  
`D` delete to the end of the line  

## Undo / Redo

`u` undo  
`<Ctrl> r` redo  

## Editing

`i` insert before the cursor  
`a` insert after the cursor  
`I` insert at the beginning of the line  
`A` insert at the end of the line  
`o` insert a line below and go into insert mode  
`O` insert a line above and go into insert mode  
`ciw` delete the current word and go into insert mode (change)  
`cc` delete the current word and go into insert mode (change)  
`J` Join line below to current line  
`==` indent current line  

## Moving around

`24G` go to line 24  
`e` Go to the end of this word  
`b` go to the beginning of this word  
'^' first character of line  
'$' end of line  
'gg' go to first line (or 0G)  
'G' go to last line  

