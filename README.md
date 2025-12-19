# commands

My useful commands and aliases.

## How to use

1. Install [Homebrew](https://brew.sh/)

```zsh=
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

2. Since most of my aliases are from [Oh My Zsh](https://github.com/ohmyzsh/ohmyzsh), install it by running:

```zsh=
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

3. Install CLI tools

```zsh=
brew install bat eza fzf git gitui node nvim python ripgrep tmux uv zoxide
```

4. Source command aliases in `~/.zshrc` file:

```zsh=
source ~/commands/general.zsh
source ~/commands/git.zsh
source ~/commands/vim.zsh
source ~/commands/flutter.zsh
source ~/commands/android.zsh
```

5. Install useless CLI tools (*Optional*)

```zsh=
brew install asciiquarium fastfetch nyancat sl
```

## Additional installations

### `general.zsh`

- `l`: aliased to [`eza`](https://github.com/eza-community/eza)
- `cd`: aliased to [`zoxide`](https://github.com/ajeetdsouza/zoxide?tab=readme-ov-file#getting-started)
- `cat`: aliased to [`bat`](https://github.com/sharkdp/bat)
- `pip`: aliased to `uv pip` of [uv](https://github.com/astral-sh/uv)

### `git.zsh`

- `g`: aliased to [`gitui`](https://github.com/extrawurst/gitui)
- `gcz`: aliased to [`gitcz`](https://github.com/streamich/git-cz)
  - Install with `npm install -g git-cz`

### `vim.zsh`

- `v`: aliased to [`nvim`](https://github.com/neovim/neovim)

### `flutter.zsh`

- `f`: aliases to [`flutter`](https://flutter.dev/)
  - You can also replace the alias if you are using [`fvm`](https://github.com/fluttertools/fvm)
