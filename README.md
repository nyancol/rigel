# Rigel ✨

24bit colorscheme based on the star [Rigel](https://en.wikipedia.org/wiki/Rigel) - the bright blue star in the constellation of Orion

<img width="1103" alt="vim" src="https://user-images.githubusercontent.com/12150276/60734656-8cc9ae00-9f48-11e9-9bbb-7020d8f9130f.png">

Install

- [Vim](#vim)
- [Terminal](#terminal)
- [Slack](#slack)

## Vim

```vim
"""" install
" install with vim-plug
Plug 'Rigellute/rigel'

" or with NeoBundle
" NeoBundle 'Rigellute/rigel'
" or with Vundle
" Plugin 'Rigellute/rigel'

"""" enable 24bit true color
set termguicolors

"""" enable the theme
syntax enable
colorscheme rigel
```

#### Airline

![Airline](https://user-images.githubusercontent.com/12150276/60734661-8e937180-9f48-11e9-9aca-90c7a5d40dbf.png)

```vim
let g:rigel_airline = 1
let g:airline_theme = 'rigel'
```

#### Lightline

TODO: create lightline theme

## Terminal

<img width="1064" alt="terminal" src="https://user-images.githubusercontent.com/12150276/60734655-8cc9ae00-9f48-11e9-994e-70f055945cfb.png">

The terminal screenshot above is using [Pure](https://github.com/sindresorhus/pure) prompt and [Fira Code](https://github.com/tonsky/FiraCode) font (size 16) in Alacritty.

#### Alacritty

1. Copy [alacritty.yml](./alacritty.yml) and paste into `~/.config/alacritty/alacritty.yml`

#### iTerm2

1. Download [`rigel.itermcolors`](./rigel.itermcolors)
1. In iTerm2 access the _Preferences_ pane on the _Profiles_ tab.
1. Under the _Colors_ tab import the [`rigel.itermcolors`](./rigel.itermcolors) file via the _Load Presets_ drop-down at the bottom right.

## Slack

1. Go to Slack's `Preferences` → `Sidebar Theme`
1. Scroll to the bottom and paste these colors: `#002635,#00384D,#F08E48,#E6E6DC,#00384D,#B7CFF9,#00FFFF,#FF5A67`
