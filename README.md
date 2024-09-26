# vim-cpp2: Enhanced C and C++ syntax highlighting

Keyword and regex-based syntax highlighting for C++2 (or cpp2) in Vim.

copied from vim-cpp-modern

will be updated to do cpp2 syntax


## Optional features

```vim
" Disable function highlighting (affects both C and C++ files)
let g:cpp_function_highlight = 0

" Enable highlighting of C++11 attributes
let g:cpp_attributes_highlight = 1

" Highlight struct/class member variables (affects both C and C++ files)
let g:cpp_member_highlight = 1

" Put all standard C and C++ keywords under Vim's highlight group 'Statement'
" (affects both C and C++ files)
let g:cpp_simple_highlight = 1
```

The last option changes the highlighting of the following keywords:
- C++: `class`, `typename`, `template`, `namespace`, `concept`, `mutable`,
  `constexpr` `decltype`, `consteval`, `constinit`


## Installation

```bash
$ cd ~/.vim/pack/git-plugins/start
$ git clone --depth=1 https://github.com/bfrg/vim-cpp2
```
**Note:** The directory name `git-plugins` is arbitrary, you can pick any other
name. For more details see `:help packages`.


## License

Distributed under the same terms as Vim itself. See `:help license`.

