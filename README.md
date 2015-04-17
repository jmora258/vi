# vi

<h2>NAVIGATION</h2> 

h 	-- left <br> 
j 	-- down <br> 
k 	-- up <br> 
l 	-- right <br> 
0	-- move cursor to start of current line (the one with the cursor)<br>
$ 	-- move cursor to end of current line<br> 
w 	-- move cursor to beginning of next word<br> 

<h2>INSERTING and ADDING TEXT </h2> 
i 	-- insert text before cursor, until <Esc> hit<br> 
a 	-- append text after cursor, until <Esc> hit<br> 
o 	-- open and put text in a new line BELOW the current line, until <Esc> hit<br> 
O 	-- open and put text in a new line ABOVE the current line, until <Esc> hit<br> 


<h2>DELETING and MANIPULATING TEXT </h2> 
x		-- delete a single character <br> 
dd 		-- delete entire line <br> 
J 		-- join two lines together by removing line break <br> 
yy		-- copy (yank, cut) the current line into the buffer <br> 
P 		-- pastes text before the cursor <br> 
p 		-- pastes text after the cursor <br> 
u 		-- undoes the last edit <br> 
CTRL-R	-- redo <br> 
U 		-- undo line: undows all the changes made on the last 
		line that was edited. Typing this command twice cancels 
		the preceeding "U1"<br> 

<h2>OTHER USEFUL COMMANDS</h2> 
To save a file: [Esc] ZZ <br> 
To enter a command: [Esc] [Colon] <br> 

:e filename 		--> edit another file <br> 
:split filename		--> split window and load another file <br> 
ctrl-w [up-arrow]	--> move cursor up a window <br> 
ctrl-w ctrl-w		--> move cursor to another window (cylce)<br> 
ctrl-w_				--> maximize current window <br> 
ctrl-w=				--> make all equal size <br> 
10 ctrl-w+			--> increase window size by 10 lines <br> 
:vsplit file 		--> vertical split <br> 
:sview file 		--> same as split, but readonly <br> 
:hide				--> close current window<br> 
:only 				--> keep only this window open<br> 
:ls 				--> show current buffers<br> 
:b 2 				--> open buffer #2 in this window <br> 
