Vim for Dustjs
================

based on github.com/juvenn/mustache.vim.git
dustjs.vim for working with dust js templates (http://akdubya.github.com/dustjs/). 


### Install for pathogen

    cd ~/.vim/
    git submodule add git://github.com/jimmyhchan/dustjs.vim.git bundle/dustjs
    vim bundle/dustjs/example.dust


## extra stuff added for working with other plugins
* NERDCommenter
 add this:
   let g:NERDCustomDelimiters = {
     'dustjs': { 'left': '{!', 'right': '!}' }
   }

* tpope's surround
   let g:surround_{char2nr('d')} = "{\r}"
* snipmate
   copy the snippets/dustjs folder to your snippets folder

## Thanks
* [Github/juvenn](/juvenn) for the mustache.vim plugin
* [Github/akdubya](/akdubya) for dust.js


