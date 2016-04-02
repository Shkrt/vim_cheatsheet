Moving around | |
--- | --- | --- |
j | move cursor down |
k | move cursor up |
l | move cursor right |
h | move cursor left |
--:|--:|
H|move cursor to the top of the view field|
L|move cursor to the bottom of the view field|
M|move cursor to the middle of the view field|
C-u|PageUp-alike|
C-d|PageDown-alike|
56G|move to the line 56|
--:|--:|
w|move to the beginning of next word|
3w|move to the beginning of 3-rd word forward|
e|move to the end of next word|
3e|move to the end of 3-rd word forward|
b|move to the beginning of previous word|
3b|move to the beginning of 3-rd word backwards|
0|move to the beginning of line|
$|move to the end of line|
fA|find the A character next in the line and move to it|
tA|find the A character next in the line and set cursor right before it|
FA|find the A character backwards in the line and move to it|
TA|find the A character backwards in the line and set cursor right before it|
;|repeat last find-and-move command|
,|repeat last find-and-move command reversed direction|

Searching | |
--- | --- | --- |
/ | search |
? | search backwards |
n | repeat last search |
N | repeat last search backwards |

Editing||
--- | --- | --- |
i |switch to insert mode|
a |switch to insert mode|
o |insert new line under cursor and switch to insert mode|
r |replace one character|
R |replace multiple characters|
u |undo|
dd |delete current line|
4dd |delete 4 lines to bottom|
dw |delete word|
4dw |delete 4 words|
cc |cut current line|
5cc |cut 5 lines to bottom|
c$ |cut current line from cursor to end|
c0 |cut current line from cursor to beginning|
yy |copy current line|
y$ |copy current line from cursor to end|
y0 |copy current line from cursor to beginning|
6yy |copy 6 lines to bottom|
p |paste from clipboard|
x |delete character|
v |select text|

Commands||
--- | --- | --- |
:q|quit|
Esc|exit from edit mode|
:w|write|
:o|open file|
:tabnew|open new tab|
q!|quit without saving|
