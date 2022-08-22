# 说明

1. **本仓库所有文件均来自于[Vim-go](https://github.com/fatih/vim-go)**

2. 本仓库目的在于为从Vim-go迁移go的高亮体系到没有安装Vim-go的配置中(比如用coc系列的补全)

# 安装

### Plug

1. 添加到.vimrc

```vim
Plug 'chenxuan520/vim-go-highlight',{'for':'go'}
```

2. :PlugInstall

# 使用

- 推荐配置(提供各种部分的高亮)

```vim
let g:go_highlight_functions = 1
let g:go_highlight_extra_types = 1
let g:go_highlight_space_tab_error = 1
let g:go_highlight_trailing_whitespace_error = 1
let g:go_highlight_operators = 1
let g:go_highlight_function_parameters = 1
let g:go_highlight_function_calls = 1
let g:go_highlight_types = 1
let g:go_highlight_build_constraints =1
let g:go_highlight_generate_tags =1
let g:go_highlight_string_spellcheck = 1
let g:go_highlight_fields = 1
let g:go_highlight_array_whitespace_error = 1
let g:go_highlight_variable_declarations = 1
let g:go_highlight_variable_assignments = 1
```




