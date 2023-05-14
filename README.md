# C3.vim
Syntax highlighting for C3's programming language
Derived from [Tetralux/odin.vim](https://github.com/Tetralux/odin.vim).

### What it looks like. 
<!-- [Screenshot](odin.vimpng)-->

## Installation

Simply clone the repository into your Vim's package directory. (Vim must be installed from https://www.vim.org.)
If using [Pathogen](https://github.com/tpope/vim-pathogen), clone it into the `bundle` folder within Vim's package directory, instead.

Note that the package directory is located in `%USERPROFILE%\vimfiles` on Windows,
and `~/.vim` on Unix.

## Optional features

Not everyone wants certain features, like function call highlighting.

You can enable or disable the relevant features by searching the repository for the appropriate code tags, and commenting out the adjacent lines.
The Vim comment character is `"`.

| Description                                | Code tag to search for  |
|--------------------------------------------|-------------------------|
| Function call and declaration highlighting | `:FunctionHighlighting` |
