|Moving around ||
|--- | --- |
|j | move cursor down
|k | move cursor up
|l | move cursor right
|h | move cursor left
|H|move cursor to the top of the view field
|L|move cursor to the bottom of the view field
|M|move cursor to the middle of the view field
|C-u|PageUp-alike
|C-d|PageDown-alike
|C-w-j|move to a window at the bottom
|C-w-l|move to a window on the right
|C-w-H|move current window to the left
|3C-w--|decrease height of the current window by 3
|4C-w->|increase width of current window by 4
|C-w=|equalize all windows
|56G|move to the line 56|
|w|move to the beginning of next word|
|W|move to the word after next whitespace|
|3w|move to the beginning of 3-rd word forward|
|e|move to the end of next word|
|3e|move to the end of 3-rd word forward|
|b|move to the beginning of previous word|
|3b|move to the beginning of 3-rd word backwards|
|0|move to the beginning of line|
|$|move to the end of line|
|fA|find the A character next in the line and move to it|
|tA|find the A character next in the line and set cursor right before it|
|FA|find the A character backwards in the line and move to it|
|TA|find the A character backwards in the line and set cursor right before it|
|;|repeat last find-and-move command|
|,|repeat last find-and-move command reversed direction|
|zz|center current line at viewport|
|zt|move current line at viewport's top|
|zb|move current line at vewport's bottom|
|+| move one line bottom to first non-whitespace character on the line|
|-| move one line up to first non-whitespace character on the line|

|Searching ||
--- | --- |
|/ | search |
|? | search backwards |
|n | repeat last search |
|N | repeat last search backwards |


|Editing||
|--- | --- |
|i |switch to insert mode|
|a |switch to insert mode|
|o |insert new line under cursor and switch to insert mode|
|r |replace one character|
|R |replace multiple characters|
|u |undo|
|dd |delete current line|
|dj| delete two lines down from current|
|dk| delete two lines up from current|
|4dd |delete 4 lines to bottom|
|dw |delete word (must be in the begining of word)|
|daw |delete word, including following space|
|caw |delete word, not including following space|
|d3w| delete 3 words forward|
|d/match|delete till match|
|dap| delete a paragraph, including following empty line|
|=ap| indent a paragraph, including following empty line|
|dip| delete a paragraph|
|=ip|indent a paragraph|
|ci'|change inside single quotes|
|di"|delete inside dobule guotes|
|da}|delete with curly braces|
|dit|delete inside a tag|
|dt,|delete till comma|
|vt,|select till comma|
|4dw |delete 4 words|
|cc |cut current line|
|5cc |cut 5 lines to bottom|
|c$ |cut current line from cursor to end|
|c0 |cut current line from cursor to beginning|
|yy |copy current line|
|y$ |copy current line from cursor to end|
|y0 |copy current line from cursor to beginning|
|6yy |copy 6 lines to bottom|
|p |paste from clipboard|
|x |delete character|
|v |select text|
|> |indent to right|
|< |indent to left|
|= |change formatting|

|Commands||
|--- | --- |
|:q|quit|
|Esc|exit from edit mode|
|:w|write|
|:o|open file|
|:tabnew|open new tab|
|:tabe|open new tab|
|:tabm4|move current tab to 4-th position|
|:noh|Turn of current search results highlighting|
|:q!|quit without saving|
|:%s/word/replacement/g|search and replace globally|
|:%s/word/replacement/gi|search and replace globally|, case insensitive
|:s/word/replacement/g|search and replace on current line|
|:44,65s/word/replacement/g|search and replace between line numbers|
|:14,16d|delete lines from 14 to 16|
|.|repeat last edit|
|:new|open new window above|
|:vnew|open new window beside|
|:split|open new window above|
|:vsplit|open new window beside|
