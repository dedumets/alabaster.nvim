# alabaster.nvim

A color scheme with minimal syntax highlighting for Neovim.

## Motivation

For the original idea behind Alabaster, see the original [Sublime text theme](https://github.com/tonsky/sublime-scheme-alabaster))

My fork was created to unify my personal choice of development tools, combining the ideology of the original Alabaster theme with my preferred contrasting that the [terminal themes](https://github.com/cboone/terminal-theme-alabaster) variant provides. Despite being inspired by the same theme, these two themes are incompatible with eachother, and my fork addresses it (at least for Ghostty).

## Usage

Just like the original Neovim theme, this is designed with [nvim-treesitter](https://github.com/nvim-treesitter/nvim-treesitter) in mind.

```vim
set termguicolors
colorscheme alabaster
```

The TUI will likely detect your terminal background and set `background` accordingly. If you want to force light or dark mode, use `set background=dark` or `set background=light`

## Configuration

Two config options are provided:

- `g:alabaster_dim_comments` (default: `false`):
    - `true` - comments use a neutral, dimmed color
    - `false` - comments use a highlighted color
- `g:alabaster_floatborder` (default: `false`).
    - `true` - floating window borders have a foreground colour and background colour is the same as `Normal`.
    - `false` - floating window borders have no foreground colour and background colour is the same as popup menus.

## Themed plugins

From the original repository:

- [folke/noice.nvim](https://github.com/folke/noice.nvim)
- [lewis6991/gitsigns.nvim](https://github.com/lewis6991/gitsigns.nvim)
- [nvim-telescope/telescope.nvim](https://github.com/nvim-telescope/telescope.nvim)
- [TimUntersberger/neogit](https://github.com/TimUntersberger/neogit)
- [tpope/vim-fugitive](https://github.com/tpope/vim-fugitive)
- [mhinz/vim-startify](https://github.com/mhinz/vim-startify)
- [nvim-lualine/lualine.nvim](https://github.com/nvim-lualine/lualine.nvim)
- [andymass/vim-matchup](https://github.com/andymass/vim-matchup)
- [phaazon/hop.nvim](https://github.com/phaazon/hop.nvim)
- [ggandor/lightspeed.nvim](https://github.com/ggandor/lightspeed.nvim)
- [p00f/nvim-ts-rainbow](https://github.com/p00f/nvim-ts-rainbow)
- [mizlan/iswap.nvim](https://github.com/mizlan/iswap.nvim)
- [kristijanhusak/vim-dadbod-ui](https://github.com/kristijanhusak/vim-dadbod-ui)

## Credits

- [dchinmay2/alabaster.nvim](https://github.com/dchinmay2/alabaster.nvim) for doing most of the heavy-lifting in creating the theme
- [cboone/terminal-theme-alabaster](https://github.com/cboone/terminal-theme-alabaster) for creating the theme for Ghostty, which this theme is partially based on
