# Awesome Env [![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

Version managers in the style of chruby, rbenv and rvm.

## Contents

- [List of \*env-, ch\*- and \*vm- style version managers](#list-of-env--ch--and-vm--style-version-managers)
- [False friends](#false-friends)
- [Plugins](#plugins)
- [Integration](#integration)

## List of \*env-, ch\*- and \*vm- style version managers

The following pieces of software are **runtime version managers** in the style of chruby, rbenv and rvm:

- Multiple platforms
    - [anyenv](https://github.com/anyenv/anyenv)
    - [asdf](https://asdf-vm.com)
    - [SDKMAN](https://sdkman.io/)
- Crystal
    - [crenv](https://github.com/crenv/crenv)
- D
    - [dvm](https://github.com/jacob-carlborg/dvm)
- Elixir
    - [kiex](https://github.com/taylor/kiex)
- Erlang
    - [kerl](https://github.com/kerl/kerl)
- Go
    - [goenv](https://github.com/syndbg/goenv)
- Java
    - [jabba](https://github.com/shyiko/jabba)
    - [jenv](https://github.com/jenv/jenv/)
- Julia
    - [juliavm](https://github.com/pmargreff/juliavm)
- MongoDB
    - [mongodb-version-manager](https://github.com/mongodb-js/version-manager)
- Node.js
    - [fnm](https://github.com/Schniz/fnm)
    - [n](https://github.com/tj/n)
    - [nodebrew](https://github.com/hokaccha/nodebrew)
    - [nodenv](https://github.com/nodenv/nodenv)
    - [nodist](https://github.com/nullivex/nodist)
    - [nvm](https://github.com/nvm-sh/nvm)
    - [nvm-windows](https://github.com/coreybutler/nvm-windows)
- Perl
    - [perlbrew](https://perlbrew.pl/)
    - [plenv](https://github.com/tokuhirom/plenv)
- Perl (Windows Strawberry Perl)
    - [berrybrew](https://github.com/dnmfarrell/berrybrew)
- PHP
    - [phpenv](https://github.com/phpenv/phpenv)
- Python
    - [pyenv](https://github.com/pyenv/pyenv)
- Ruby
    - [chruby](https://github.com/postmodern/chruby)
    - [frum](https://github.com/TaKO8Ki/frum/)
    - [rbenv](https://github.com/rbenv/rbenv)
    - [rvm](https://rvm.io/)
- Rust
    - [rustup](https://github.com/rust-lang/rustup)
- Solidity
    - [svm](https://github.com/josh-richardson/svm)
- Swift
    - [swiftenv](https://github.com/kylef/swiftenv)
- Terraform and Terragrunt
    - [tfenv](https://github.com/tfutils/tfenv)
    - [tgenv](https://github.com/cunymatthieu/tgenv)
- Xcode
    - [xcode-select](https://developer.apple.com/library/archive/technotes/tn2339/_index.html)

## False friends

The following pieces of software all end in -`env` **but are not** runtime version managers:

- Python virtualenv managers: pipenv, venv, virtualenv
- Process environment managers: shadowenv

## Plugins

### Plugins for anyenv

- [anyenv-update](https://github.com/znz/anyenv-update)
- [anyenv-git](https://github.com/znz/anyenv-git)

### Plugins for asdf

A list of asdf plugins can be found at: https://asdf-vm.com/#/plugins-all?id=plugin-list

### Plugins for pyenv

- [pyenv-update](https://github.com/pyenv/pyenv-update)
- [pyenv-version-alias](https://github.com/aiguofer/pyenv-version-alias)
- [pyenv-virtualenv](https://github.com/pyenv/pyenv-virtualenv)

### Plugins for rbenv

- [rbenv-aliases](https://github.com/tpope/rbenv-aliases)
- [rbenv-bundler](https://github.com/carsomyr/rbenv-bundler)

## Integration

### Integrating with Emacs

- [pyenv.el](https://github.com/aiguofer/pyenv.el)

### Integrating with Vim

- [vim-rvm](https://github.com/tpope/vim-rvm)

### Integrating with zsh

- [zsh-nvm](https://github.com/lukechilds/zsh-nvm)
- [zsh-rbenv](https://github.com/mattberther/zsh-rbenv)

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md).
