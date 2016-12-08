# Vim Tips
Hervé Beraud personal vim tips and memo

# Format file
- remove white spaces at line start `:%s/^\s\+//e`
- remove white spaces at end of line `:%s/\s\+$//e`

# Copy & paste
- copy and assign to buffer `"kyy` (in this example is assigned to key `k`)
- paste buffer content (assigned to `k`) `"kp`

# Mark
- set mark a at current cursor location `ma` (assign mark to key `a`)
- jump to line of mark a (first non-blank character in line) `'a`
- jump to position (line and column) of mark ````a```
- delete from current line to line of mark `d'a`
- change text from current line to line of mark `c'a`
- yank text to unnamed buffer from cursor to position of mark ```y`a```
- list all the current marks `:marks`
