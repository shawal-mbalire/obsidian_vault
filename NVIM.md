## Common vim commands

### vim motions - 
- h, j, k,l, --> moving around
- w, b --> move by word forwards and back
Augmenting motions
Add number to motion to do multiple like 6+j to move 6 down
Do `command + count + motion`
for example `d4j` delete 4 lines below

vim motion
- d --> cut
- y --> yank, copy
- c
- p --> paste
- dd --> cut line
insert mode
- i put you to left of cursor
- `esc`, `ctrl+[`
- a moves cursor to right

## horizontal motions
- `[[` --> top of file 
- `]]` --> end of file
- 0 --> top of line 
- $ --> end of line
- f --> find then ; and , to skip findings in line
- t -->moves to but before 
- I --> begin line in insert
- A --> end line insert
- o -->new line and insert
-  O --> new line above cursor insert
## vertical motions
- {,} --> top and end of paragraph, white line (not recommended)
- `ctrl+d` --> half page up
- `ctrl+u` --> half page down
- G --> to bottom
- gg --> to top
- :100 --> to line 100
- /query --> search for query n --> to next finding N to prev finding
- * --> to search for current word cycling as above