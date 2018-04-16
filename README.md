# Local Dotfiles

These are my local dotfile overrides which sit on top of thoughtbot's dotfiles. To use these, first install the base [thoughtbot
dotfiles](https://github.com/stevehanson/dotfiles). Then, clone this repo into
`~/dotfiles-local` and run `rcup`. 

## Dependencies

These dotfiles require some other software to be installed. 

### Quick Install

```shell
brew install diff-so-fancy zsh-autosuggestions zsh-syntax-highlighting rbenv
```

Then, install NVM as directed [on GitHub](https://github.com/creationix/nvm).

### Step-by-Step Install

If desired, follow the detailed instructions below in lieu of the quick install.

#### diff-so-fancy

Makes git diffs more human-readable.

```shell
brew install diff-so-fancy
```

Source: [GitHub](https://github.com/so-fancy/diff-so-fancy)

#### zsh-autosuggestions

Adds auto-suggestion for zsh commands.

```shell
brew install zsh-autosuggestions
```

Source: [Github](https://github.com/zsh-users/zsh-autosuggestions)

#### zsh-syntax-highlighting

Adds command syntax highlighting to zsh.

```shell
brew install zsh-syntax-highlighting
```

Source: [GitHub](https://github.com/zsh-users/zsh-syntax-highlighting)

#### NVM

A node version manager. To install, just run the install script as instructed on GitHub. No need to update the dotfiles after.

Source: [GitHub](https://github.com/creationix/nvm)

#### rbenv

A Ruby version manager.

```
brew install rbenv
```

Source: [GitHub](https://github.com/rbenv/rbenv)