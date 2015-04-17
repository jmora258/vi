# vi

NAVIGATION
h 
j
k
l
0	-- move cursor to start of current line (the one with the cursor)
$ 	-- move cursor to end of current line
w 	-- move cursor to beginning of next word

INSERTING and ADDING TEXT 
i 	-- insert text before cursor, until <Esc> hit
a 	-- append text after cursor, until <Esc> hit
o 	-- open and put text in a new line BELOW the current line, until <Esc> hit
O 	-- open and put text in a new line ABOVE the current line, until <Esc> hit


DELETING and MANIPULATING TEXT 
x		-- delete a single character 
dd 		-- delete entire line 
J 		-- join two lines together by removing line break 
yy		-- copy (yank, cut) the current line into the buffer 
P 		-- pastes text before the cursor 
p 		-- pastes text after the cursor 
u 		-- undoes the last edit 
CTRL-R	-- redo 
U 		-- undo line: undows all the changes made on the last 
		line that was edited. Typing this command twice cancels 
		the preceeding "U1"

OTHER USEFUL COMMANDS
To save a file: <Esc> ZZ 
To enter a command: <Esc> <Shift> <semicolon> 

:e filename 		--> edit another file 
:split filename		--> split window and load another file 
ctrl-w [up-arrow]	--> move cursor up a window 
ctrl-w ctrl-w		--> move cursor to another window (cylce)
ctrl-w_				--> maximize current window 
ctrl-w=				--> make all equal size 
10 ctrl-w+			--> increase window size by 10 lines 
:vsplit file 		--> vertical split 
:sview file 		--> same as split, but readonly 
:hide				--> close current window
:only 				--> keep only this window open
:ls 				--> show current buffers
:b 2 				--> open buffer #2 in this window 