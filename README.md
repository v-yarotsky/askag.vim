AskAg.vim
=========

An addition to [ag.vim](https://github.com/epmatsw/ag.vim), allows interactive search-in-project, remembers previous search.
The plugin is compatible with [Pathogen](https://github.com/tpope/vim-pathogen).

suggested mappings:

    " <C-/> - show search prompt
    nmap  :AG<CR>
    " <C-/> on visual selection - search selected text in project
    vnoremap  "hy:Ag! <C-r>h<CR>

