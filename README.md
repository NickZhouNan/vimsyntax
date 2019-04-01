# vimsyntax
Vim syntax highlighting customized.

Copy directory syntax to ~/.vim/

Append corresponding lines to ~/.vimrc


syntax file list
========

## hive.vim

Vim syntax highlighting for hiveSQL

Append these line to ~/.vimrc:

```
" for .hql files
au BufNewFile,BufRead *.hql set filetype=hive expandtab

" for .q files
au BufNewFile,BufRead *.q set filetype=hive expandtab
```
