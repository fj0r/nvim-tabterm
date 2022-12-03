 # switch terminal based on tabs

 - [ ] setup
 - [x] <c-t> toggle term
    - [x] create if non exist
 - [x] quit term when tabclose
 - [ ] term num in status line(openterm('nu', {name = ...}))
 - [ ] change to insert mode when enter term and cursor at last line
    term get actual line (vim.fn.line('$') get buffer line)
 - [x] default 1 term each tab (count arg for multiple)
 - [x] possession integration
 - [x] stdout > output to buffer
 - [x] <C-y> for paste
 - [x] nushell
    - [x] send '\n'
    - [x] auto tcd
       - [x] pin tabname manually
       - [x] smart tcd (HookPwdChanged: is git or not under git)
    - [x] open file in cli
       - [x] open file not in cwd
    - [x] opposite pwd
 - [x] default [No Name] buffer -> terminal (possession.lua)

