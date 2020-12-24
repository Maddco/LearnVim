# This is document will hold key commands of VIM.

# File changes save/no save and exit VIM

## How to exit Vim without saving when not file changes deteceted.
`:q`
## How to exit Vim and not save when changes are present.
`:q!`
## How to save and quit.
`:wq`
## How to save the file and not quit.
`:w`

## How to move around file.
`j` down
`k` up
`l` right
`h` left

## Also you can place a number infront of the command above to move that many. This applies to many other actions on hear such as `}`

`20j`

## How to delete a line?
`dd`

## How to hit bottom of file.
`G`

## How to hit top of file.
`gg`

## How to skip two blocks of code?
`{` up
`}` down

## How to delete an line and undo it also redo it?
`dd` will delete
`u` will undo
`^R` redo

## how to perform same action over?
`dd` delete something
`.` delete something else

## Copy a line and paste.
`yy` copy line
`p` paste line below
`P` paste line above

## Enter visual mode use all prior commands to assit with actions
`V`

## How to insert a new line and be on insert mode?
`O` above the line
`o` below the line

## Once on a line how to quickly move across text?
`w` forward work by word
`b` back word by word
`0` all the way back
`Shift ^` will take you all the way to front of first word
`0w` will imulate Shift ^ and is easier to remember
`$` end of the sentence

## How to go to a specific line of the document?
`:20` this will take you to line 20

## Go exactly to and infront of value you seek by line
`t<your-value>` This will take you right before the letter you seek
`f<your-value>` This will take you exactly on the letter you seek
`%` this will walk structures like beginning ( and end )

## Delete a block of code.
`d%` Have this selected on the ( or { to selete group
`D` delete everything after cursor on line

## How to change a work in code?
`cw` this can be used to change a word
`dw` delete a word
`dt<your-value-to-delete-too>` This will delete value up until the character specificed.
`ct<your-value-to-change-too` This will change value up until the character specified.

## Find word appearing multiple times in doc
`*` place cursor on word and hit multiple times to find its local