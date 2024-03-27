# commands

My useful commands and aliases.

## How to use

1. Since most of my aliases are from [Oh My Zsh](https://github.com/ohmyzsh/ohmyzsh), install it by running:

```zsh=
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

2. Add custom aliases to your `~/.zshrc` file:

```zsh=
source ~/commands/general.zsh
source ~/commands/git.zsh
source ~/commands/vim.zsh
source ~/commands/flutter.zsh
source ~/commands/android.zsh
```

## Additional installations

### `general.zsh`

- `l`: aliased to [`eza`](https://github.com/eza-community/eza)
- `cd`: aliases to [`zoxide`](https://github.com/ajeetdsouza/zoxide?tab=readme-ov-file#getting-started)
- `cat`: aliases to [`bat`](https://github.com/sharkdp/bat)
- `fuck`: command of [`thefuck`](https://github.com/nvbn/thefuck)

### `git.zsh`

- `g`: aliased to [`gitui`](https://github.com/extrawurst/gitui)
- `gcz`: aliased to [`gitcz`](https://github.com/streamich/git-cz)

### `vim.zsh`

- `v`: aliased to [`nvim`](https://github.com/neovim/neovim)

### `flutter.zsh`

- `f`: aliases to [`flutter`](https://flutter.dev/)
  - You can also replace the alias if you are using [`fvm`](https://github.com/fluttertools/fvm)
