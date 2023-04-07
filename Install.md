# Install AstroNvim on Win10

New NVim 0.8 Install in
C:\Program Files (x86)\nvim-win64

Install python3 for nvim:
Run
:checkhealth in nvim
if python3 missing, add to init.vim next line:
let g:python3_host_prog = 'C:\Users\t_bertoncelj\AppData\Local\Programs\Python\Python39\python.exe'
Then go to cmd and run:
C:\Users\t_bertoncelj\AppData\Local\Programs\Python\Python39\python.exe pip install --user --upgrade pynvim
Restart nvim, check if :checkhealth python3 works

For TODO pluging https://github.com/folke/todo-comments.nvim
you must install manual "ripgrep" on Win10 from here (https://sourceforge.net/projects/ripgrep.mirror/) and add it to $PATH
Then command :TodoQuickFix will show up

For LazyGit -> Usage <leader>gg
Install -> https://github.com/jesseduffield/lazygit/releases
For Win10 and add it to $PATH
