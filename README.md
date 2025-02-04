# asdf-neoneovim [![GitHub Actions Status:Commit](https://github.com/ompugao/mise-neovim/workflows/Commit%20workflow/badge.svg)](https://github.com/ompugao/mise-neovim/actions?query=workflow%3A%22Commit+workflow%22) [![GitHub Actions Status:Schedule](https://github.com/ompugao/mise-neovim/workflows/Schedule%20workflow/badge.svg)](https://github.com/ompugao/mise-neovim/actions?query=workflow%3A%22Schedule+workflow%22)

neovim plugin for [asdf](https://github.com/asdf-vm/asdf) version manager.

Forked from [srivathsanmurali/asdf-cmake](https://github.com/srivathsanmurali/asdf-cmake).

## Usage

### Install

The plugin can be install using the following command.

```sh
asdf plugin-add neovim
# or asdf plugin-add neovim https://github.com/ompugao/mise-neovim.git
asdf install neovim <version>
```
### .tool-versions file

You can specify the version to install with a line like so in your .tool-versions file:
neovim <version>

### Using the CLI

You can then set the local/global version to your new version with `asdf local neovim <version>` or `asdf global neovim <version>`.

## Use

Check [asdf](https://github.com/asdf-vm/asdf) readme for instructions on how to install & manage versions of neovim.
