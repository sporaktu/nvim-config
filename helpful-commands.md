# Comprehensive List of 200 Vim Commands

This document provides an extensive list of Vim commands along with their keystrokes, purpose, and use cases. It starts with basic commands and gradually moves into more advanced topics.

## 1. Basic Movement Commands
1. **`h`** - Move left by one character.
   - *Use case*: Navigate characters in normal mode.
2. **`j`** - Move down one line.
   - *Use case*: Scroll downwards in normal mode.
3. **`k`** - Move up one line.
   - *Use case*: Scroll upwards in normal mode.
4. **`l`** - Move right by one character.
   - *Use case*: Navigate characters in normal mode.
5. **`w`** - Jump to the beginning of the next word.
   - *Use case*: Efficiently navigate between words.
6. **`b`** - Jump backward to the beginning of the previous word.
   - *Use case*: Reverse word-by-word navigation.
7. **`0`** - Move to the beginning of the line.
   - *Use case*: Quickly navigate to the start of the line.
8. **`$`** - Move to the end of the line.
   - *Use case*: Quickly navigate to the end of the line.
9. **`gg`** - Move to the top of the file.
   - *Use case*: Fast access to the beginning of the file.
10. **`G`** - Move to the end of the file.
    - *Use case*: Fast access to the end of the file.

## 2. Editing Commands
11. **`i`** - Enter insert mode before the cursor.
    - *Use case*: Begin inserting text at the cursor position.
12. **`I`** - Enter insert mode at the beginning of the line.
    - *Use case*: Add text to the start of the line.
13. **`a`** - Enter insert mode after the cursor.
    - *Use case*: Insert text immediately after the current character.
14. **`A`** - Enter insert mode at the end of the line.
    - *Use case*: Quickly append text to a line.
15. **`o`** - Open a new line below the current line and enter insert mode.
    - *Use case*: Add a new line below.
16. **`O`** - Open a new line above the current line and enter insert mode.
    - *Use case*: Add a new line above.
17. **`r`** - Replace the character under the cursor.
    - *Use case*: Correct a single character.
18. **`R`** - Enter replace mode.
    - *Use case*: Overwrite multiple characters.
19. **`x`** - Delete the character under the cursor.
    - *Use case*: Remove unwanted characters.
20. **`dd`** - Delete the current line.
    - *Use case*: Quickly delete a line.

## 3. Copy, Cut, and Paste
21. **`yy`** - Yank (copy) the current line.
    - *Use case*: Copy an entire line.
22. **`p`** - Paste the yanked or deleted text after the cursor.
    - *Use case*: Insert copied text.
23. **`P`** - Paste before the cursor.
    - *Use case*: Insert copied text before the cursor.
24. **`dw`** - Delete from the cursor to the end of the word.
    - *Use case*: Remove a word quickly.
25. **`d$`** - Delete from the cursor to the end of the line.
    - *Use case*: Clear the rest of the line.
26. **`d0`** - Delete from the cursor to the beginning of the line.
    - *Use case*: Remove text from the start to the cursor.
27. **`y$`** - Yank from the cursor to the end of the line.
    - *Use case*: Copy the rest of the line.
28. **`yw`** - Yank a word from the cursor.
    - *Use case*: Copy a word easily.
29. **`c`** - Change (delete and enter insert mode).
    - *Use case*: Quickly modify text.
30. **`cc`** - Change the entire line.
    - *Use case*: Replace the entire line.

## 4. Undo and Redo
31. **`u`** - Undo the last change.
    - *Use case*: Revert recent edits.
32. **`U`** - Undo all changes on the current line.
    - *Use case*: Fix an entire line.
33. **`Ctrl + r`** - Redo the last undone change.
    - *Use case*: Reapply an undone change.

## 5. Searching
34. **`/pattern`** - Search forward for `pattern`.
    - *Use case*: Find occurrences of a word.
35. **`?pattern`** - Search backward for `pattern`.
    - *Use case*: Search in reverse.
36. **`n`** - Repeat the last search in the same direction.
    - *Use case*: Jump to the next match.
37. **`N`** - Repeat the last search in the opposite direction.
    - *Use case*: Reverse the search direction.
38. **`*`** - Search for the word under the cursor.
    - *Use case*: Quickly find the next occurrence.
39. **`#`** - Search backward for the word under the cursor.
    - *Use case*: Quickly find the previous occurrence.

## 6. Working with Files
40. **`:w`** - Write (save) the file.
    - *Use case*: Save changes.
41. **`:q`** - Quit Vim.
    - *Use case*: Exit Vim when done.
42. **`:wq`** - Write and quit.
    - *Use case*: Save changes and exit.
43. **`:q!`** - Quit without saving changes.
    - *Use case*: Discard edits.
44. **`:e filename`** - Open `filename` for editing.
    - *Use case*: Edit a different file.
45. **`:saveas filename`** - Save the current file as `filename`.
    - *Use case*: Save under a new name.
46. **`:split`** - Split the window horizontally.
    - *Use case*: Edit multiple files side by side.
47. **`:vsplit`** - Split the window vertically.
    - *Use case*: Edit files in vertical panes.
48. **`Ctrl + w w`** - Switch between split windows.
    - *Use case*: Navigate between splits.
49. **`:close`** - Close the current split window.
    - *Use case*: Close a split view.
50. **`:n`** - Go to the next file in the argument list.
    - *Use case*: Cycle through multiple files.

## 7. Visual Mode Commands
51. **`v`** - Enter visual mode.
    - *Use case*: Select text character by character.
52. **`V`** - Enter visual line mode.
    - *Use case*: Select entire lines.
53. **`Ctrl + v`** - Enter visual block mode.
    - *Use case*: Select columns of text.
54. **`y` (in visual mode)** - Yank selected text.
    - *Use case*: Copy highlighted text.
55. **`d` (in visual mode)** - Delete selected text.
    - *Use case*: Remove highlighted text.
56. **`>`** - Indent selected text to the right.
    - *Use case*: Adjust indentation.
57. **`<`** - Indent selected text to the left.
    - *Use case*: Reduce indentation.
58. **`~`** - Toggle case of selected text.
    - *Use case*: Switch between upper and lower case.

## 8. Advanced Editing
59. **`:%s/old/new/g`** - Replace all occurrences of `old` with `new` in the file.
    - *Use case*: Perform a global search and replace.
60. **`:noh`** - Clear search highlighting.
    - *Use case*: Remove highlighted search results.
61. **`ciw`** - Change inside the word.
    - *Use case*: Replace an entire word.
62. **`cit`** - Change inside a tag.
    - *Use case*: Edit the content within HTML tags.
63. **`diw`** - Delete inside the word.
    - *Use case*: Delete a word without extra spaces.
64. **`>>`** - Indent the current line to the right.
    - *Use case*: Adjust code indentation.
65. **`<<`** - Indent the current line to the left.
    - *Use case*: Decrease indentation level.

## 9. Registers and Macros
66. **`"xy`** - Yank into register `x`.
    - *Use case*: Use multiple registers to store text.
67. **`"xp`** - Paste from register `x`.
    - *Use case*: Retrieve specific copied text.
68. **`q{letter}`** - Start recording a macro into register `{letter}`.
    - *Use case*: Record repetitive tasks.
69. **`q`** - Stop recording a macro.
    - *Use case*: End macro recording.
70. **`@{letter}`** - Play back the macro in register `{letter}`.
    - *Use case*: Automate repeated actions.
71. **`@@`** - Replay the last macro.
    - *Use case*: Quickly repeat the last recorded macro.

## 10. Marks and Navigation
72. **`m{letter}`** - Set a mark `{letter}` at the current cursor position.
    - *Use case*: Bookmark specific lines.
73. **`'{letter}`** - Jump to the beginning of the line with mark `{letter}`.
    - *Use case*: Quickly navigate to a marked location.
74. **``{letter}`** - Jump to the exact position of mark `{letter}`.
    - *Use case*: Fine-grained navigation.
75. **`:marks`** - List all marks.
    - *Use case*: View all set marks in the file.

## 11. Buffers and Windows
76. **`:ls`** - List all open buffers.
    - *Use case*: See all currently open files.
77. **`:b{number}`** - Switch to buffer `{number}`.
    - *Use case*: Navigate between open buffers.
78. **`:bd`** - Delete a buffer (close file but keep window).
    - *Use case*: Close a file without exiting Vim.
79. **`Ctrl + ^`** - Switch to the previously used buffer.
    - *Use case*: Toggle between two files.
80. **`:tabnew`** - Open a new tab.
    - *Use case*: Use tabbed editing.
81. **`gt`** - Move to the next tab.
    - *Use case*: Navigate through tabs.
82. **`gT`** - Move to the previous tab.
    - *Use case*: Reverse tab navigation.

## 12. Command-Line Mode
83. **`:`** - Enter command-line mode.
    - *Use case*: Execute commands in Vim.
84. **`:!command`** - Run an external shell command.
    - *Use case*: Run shell commands without leaving Vim.
85. **`Ctrl + f`** - Scroll the command history forward.
    - *Use case*: Find previous commands.
86. **`Ctrl + b`** - Scroll the command history backward.
    - *Use case*: Search older commands.

## 13. Advanced Navigation
87. **`%`** - Move to the matching bracket, parenthesis, or brace.
    - *Use case*: Quickly jump between matching delimiters.
88. **`fx`** - Move to the next occurrence of character `x` on the current line.
    - *Use case*: Efficient line navigation.
89. **`tx`** - Move until before character `x`.
    - *Use case*: Navigate close to a character.
90. **`;`** - Repeat the last `f`, `t`, `F`, or `T` command.
    - *Use case*: Continue searching for characters.
91. **`,`** - Repeat the last `f`, `t`, `F`, or `T` command, but in the opposite direction.
    - *Use case*: Search backward for characters.

## 14. Miscellaneous
92. **`:set nu`** - Show line numbers.
    - *Use case*: Display line numbers for easier navigation.
93. **`:set nonu`** - Hide line numbers.
    - *Use case*: Remove line numbers from view.
94. **`:set cursorline`** - Highlight the current line.
    - *Use case*: Improve cursor visibility.
95. **`:set nocursorline`** - Disable current line highlighting.
    - *Use case*: Remove cursorline highlight.
96. **`Ctrl + g`** - Display the current file name and cursor position.
    - *Use case*: View current file details.
97. **`J`** - Join the current line with the next one.
    - *Use case*: Combine lines.
98. **`gq}`** - Format the paragraph.
    - *Use case*: Reformat text to improve readability.
99. **`Ctrl + e`** - Scroll the screen down one line.
    - *Use case*: Fine-tune scrolling.
100. **`Ctrl + y`** - Scroll the screen up one line.
    - *Use case*: Fine-tune upward scrolling.

## 15. Additional Commands
101. **`:tabc`** - Close the current tab.
    - *Use case*: Close the active tab when done.
102. **`:tabo`** - Close all other tabs except the current one.
    - *Use case*: Focus on a single tab.
103. **`:tabn`** - Go to the next tab.
    - *Use case*: Navigate through tabs in sequence.
104. **`:tabp`** - Go to the previous tab.
    - *Use case*: Reverse tab navigation.
105. **`:enew`** - Open a new empty buffer.
    - *Use case*: Start editing a new file.
106. **`Ctrl + w s`** - Split the window horizontally.
    - *Use case*: Create a horizontal split quickly.
107. **`Ctrl + w v`** - Split the window vertically.
    - *Use case*: Create a vertical split quickly.
108. **`Ctrl + w c`** - Close the current split.
    - *Use case*: Close a split window.
109. **`Ctrl + w q`** - Quit the current window.
    - *Use case*: Exit the current split or tab.
110. **`:badd filename`** - Add a file to the buffer list.
    - *Use case*: Prepare to edit multiple files.
111. **`gv`** - Reselect the last visual selection.
    - *Use case*: Quickly reselect text.
112. **`g;`** - Jump to the previous change.
    - *Use case*: Navigate through recent changes.
113. **`g,`** - Jump to the next change.
    - *Use case*: Move forward through changes.
114. **`:vimgrep /pattern/ **`** - Search for `pattern` across multiple files.
    - *Use case*: Perform a project-wide search.
115. **`:copen`** - Open the quickfix window.
    - *Use case*: View search results or error lists.
116. **`:cclose`** - Close the quickfix window.
    - *Use case*: Hide the quickfix results.
117. **`ci"`** - Change inside double quotes.
    - *Use case*: Replace text within quotes.
118. **`ci'`** - Change inside single quotes.
    - *Use case*: Replace text within single quotes.
119. **`ci(`** - Change inside parentheses.
    - *Use case*: Modify text inside brackets.
120. **`ci[`** - Change inside square brackets.
    - *Use case*: Modify content inside square brackets.
121. **`viw`** - Visually select a word.
    - *Use case*: Highlight a word for editing.
122. **`vip`** - Visually select a paragraph.
    - *Use case*: Highlight a paragraph for editing.
123. **`va{`** - Visually select around curly braces.
    - *Use case*: Select content including braces.
124. **`gv`** - Reselect the last visual selection.
    - *Use case*: Repeat a previous selection.
125. **`Ctrl + a`** - Increment the number under the cursor.
    - *Use case*: Increase numbers in text.
126. **`Ctrl + x`** - Decrement the number under the cursor.
    - *Use case*: Decrease numbers in text.
127. **`gUiw`** - Make the current word uppercase.
    - *Use case*: Capitalize words.
128. **`guiw`** - Make the current word lowercase.
    - *Use case*: Convert words to lowercase.
129. **`g~iw`** - Toggle the case of the current word.
    - *Use case*: Switch between uppercase and lowercase.
130. **`>>`** - Shift the current line right.
    - *Use case*: Indent lines.
131. **`<<`** - Shift the current line left.
    - *Use case*: Unindent lines.
132. **`:t .`** - Duplicate the current line.
    - *Use case*: Create a copy of the current line.
133. **`:m +1`** - Move the current line down.
    - *Use case*: Reorganize lines.
134. **`:m -2`** - Move the current line up.
    - *Use case*: Reorganize lines.
135. **`:read !command`** - Insert the output of a command.
    - *Use case*: Include command output in text.
136. **`!}`** - Filter a paragraph through an external command.
    - *Use case*: Process text with external tools.
137. **`:%!sort`** - Sort the entire file.
    - *Use case*: Sort lines alphabetically.
138. **`:sort`** - Sort selected lines.
    - *Use case*: Sort a section of text.
139. **`gqap`** - Format a paragraph.
    - *Use case*: Reformat a paragraph to match text width.
140. **`:set wrap`** - Enable line wrapping.
    - *Use case*: Wrap long lines for readability.
141. **`:set nowrap`** - Disable line wrapping.
    - *Use case*: View long lines without wrapping.
142. **`:set list`** - Show invisible characters.
    - *Use case*: View tabs and end-of-line markers.
143. **`:set nolist`** - Hide invisible characters.
    - *Use case*: Hide formatting symbols.
144. **`zo`** - Open a folded section.
    - *Use case*: Expand folded text.
145. **`zc`** - Close a folded section.
    - *Use case*: Collapse folded text.
146. **`za`** - Toggle folding.
    - *Use case*: Open or close a fold.
147. **`zR`** - Open all folds.
    - *Use case*: Expand all folded sections.
148. **`zM`** - Close all folds.
    - *Use case*: Collapse all folded sections.
149. **`:diffthis`** - Mark a buffer for diff mode.
    - *Use case*: Compare files side by side.
150. **`:diffupdate`** - Update the diff view.
    - *Use case*: Refresh differences after changes.
151. **`Ctrl + n`** - Autocomplete words.
    - *Use case*: Speed up text entry.
152. **`Ctrl + p`** - Autocomplete words (in reverse).
    - *Use case*: Cycle through previous matches.
153. **`ga`** - Display ASCII value of character under the cursor.
    - *Use case*: Check character encoding.
154. **`gf`** - Open the file under the cursor.
    - *Use case*: Quickly edit linked files.
155. **`Ctrl + o`** - Jump to the previous cursor position.
    - *Use case*: Navigate back in the file.
156. **`Ctrl + i`** - Jump forward to the next cursor position.
    - *Use case*: Navigate forward in the file.
157. **`:retab`** - Replace tabs with spaces (or vice versa).
    - *Use case*: Adjust tab settings in a file.
158. **`:!ls`** - Run an external shell command.
    - *Use case*: Run shell commands without leaving Vim.
159. **`:{range}!sort`** - Sort a range of lines.
    - *Use case*: Sort specific sections of a file.
160. **`Ctrl + w T`** - Move the current split to a new tab.
    - *Use case*: Organize splits into separate tabs.
161. **`:cd path`** - Change the working directory.
    - *Use case*: Set a new directory for file operations.
162. **`:lcd path`** - Change the local working directory.
    - *Use case*: Change the directory for the current window only.
163. **`:tabe filename`** - Open a file in a new tab.
    - *Use case*: Open multiple files in separate tabs.
164. **`Ctrl + w H`** - Move the current split to the far left.
    - *Use case*: Reorganize split windows.
165. **`Ctrl + w J`** - Move the current split to the very bottom.
    - *Use case*: Rearrange split windows.
166. **`Ctrl + w K`** - Move the current split to the top.
    - *Use case*: Reorganize splits.
167. **`Ctrl + w L`** - Move the current split to the far right.
    - *Use case*: Adjust the layout of splits.
168. **`:normal! command`** - Execute a normal mode command.
    - *Use case*: Run commands on multiple lines.
169. **`:set spell`** - Enable spell checking.
    - *Use case*: Check for spelling errors.
170. **`:set nospell`** - Disable spell checking.
    - *Use case*: Turn off spell check.
171. **`]s`** - Jump to the next spelling error.
    - *Use case*: Quickly locate misspelled words.
172. **`[s`** - Jump to the previous spelling error.
    - *Use case*: Navigate to earlier spelling errors.
173. **`z=`** - Suggest corrections for a misspelled word.
    - *Use case*: Fix spelling mistakes.
174. **`zg`** - Add a word to the spell file.
    - *Use case*: Accept uncommon words as correct.
175. **`zw`** - Mark a word as incorrect.
    - *Use case*: Customize spell checking.
176. **`:make`** - Compile the current file.
    - *Use case*: Compile code without leaving Vim.
177. **`:cnext`** - Jump to the next compiler error.
    - *Use case*: Navigate through errors.
178. **`:cprev`** - Jump to the previous compiler error.
    - *Use case*: Reverse navigation through errors.
179. **`:grep pattern`** - Search for a pattern using grep.
    - *Use case*: Search across multiple files.
180. **`:cnfile`** - Go to the next file with compiler errors.
    - *Use case*: Navigate files with errors.
181. **`:cpfile`** - Go to the previous file with compiler errors.
    - *Use case*: Reverse navigate files with errors.
182. **`Ctrl + w x`** - Exchange current window with the next one.
    - *Use case*: Swap split positions.
183. **`Ctrl + w r`** - Rotate splits clockwise.
    - *Use case*: Rearrange window splits.
184. **`Ctrl + w R`** - Rotate splits counterclockwise.
    - *Use case*: Adjust split arrangement.
185. **`gU`** - Make text uppercase to the end of the movement.
    - *Use case*: Capitalize text easily.
186. **`gu`** - Make text lowercase to the end of the movement.
    - *Use case*: Convert text to lowercase.
187. **`gUU`** - Make the entire line uppercase.
    - *Use case*: Capitalize a full line.
188. **`guu`** - Make the entire line lowercase.
    - *Use case*: Convert a full line to lowercase.
189. **`Ctrl + t`** - Jump to the tag under the cursor.
    - *Use case*: Navigate code using tags.
190. **`Ctrl + w f`** - Open the file under the cursor in a new split.
    - *Use case*: Edit linked files in splits.
191. **`y%`** - Yank text between matching parentheses.
    - *Use case*: Copy content within brackets.
192. **`d%`** - Delete text between matching parentheses.
    - *Use case*: Remove content within brackets.
193. **`v%`** - Visually select text between matching parentheses.
    - *Use case*: Highlight content within brackets.
194. **`Ctrl + q`** - Start blockwise visual mode (alternative to `Ctrl + v`).
    - *Use case*: Select rectangular blocks of text.
195. **`:redir`** - Redirect command output.
    - *Use case*: Capture output for review.
196. **`:source`** - Run commands from a file.
    - *Use case*: Execute Vimscript files.
197. **`:bufdo command`** - Run a command in all buffers.
    - *Use case*: Apply changes across multiple open files.
198. **`:tabdo command`** - Run a command in all tabs.
    - *Use case*: Apply changes to all open tabs.
199. **`:windo command`** - Run a command in all windows.
    - *Use case*: Apply changes across all splits.
200. **`:argdo command`** - Run a command in all files in the argument list.
    - *Use case*: Apply changes to multiple files from the command line.

---

These 200 Vim commands should provide an even deeper foundation for working efficiently with Vim. From basic navigation to advanced editing, these commands will help streamline your text editing process, making Vim an incredibly powerful tool in your workflow. Practice regularly, and these commands will become second nature, significantly enhancing your productivity!
