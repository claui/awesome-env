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
    - [choose](https://github.com/daotoad/choose)
    - [SDKMAN](https://sdkman.io/)
- Bash
    - [bashvm](https://github.com/ueokande/bashvm)
- Crystal
    - [crenv](https://github.com/crenv/crenv)
- D
    - [dvm](https://github.com/jacob-carlborg/dvm)
- Elixir
    - [exenv](https://github.com/mururu/exenv)
    - [kiex](https://github.com/taylor/kiex)
- Elm
    - [elmvm](https://github.com/eirslett/elmvm)
- Erlang
    - [kerl](https://github.com/kerl/kerl)
- Feather
    - [fvm](https://github.com/ryedin/fvm)
- Go
    - [goenv](https://github.com/syndbg/goenv)
    - Other, unrelated version managers also called goenv: [crsmithdev/goenv](https://github.com/crsmithdev/goenv), [wfarr/goenv](https://github.com/wfarr/goenv), [pwoolcoc/goenv](https://github.com/pwoolcoc/goenv)
    - [goup](https://github.com/owenthereal/goup)
    - [gvm](https://github.com/moovweb/gvm)
    - Other, unrelated version managers also called gvm: [andrewkroh/gvm](https://github.com/andrewkroh/gvm)
- Groonga
    - [grnenv](https://github.com/myokoym/grnenv)
- Haxe
    - [hxenv](https://github.com/MisumiRize/hxenv)
- Java
    - [jabba](https://github.com/shyiko/jabba)
    - [jenv](https://github.com/jenv/jenv/)
- Julia
    - [juliavm](https://github.com/pmargreff/juliavm)
- Kubernetes
    - [kvm](https://github.com/buehler/kubectl-version-manager)
- MAMP
    - [mampenv](https://github.com/benallfree/mampenv)
- MongoDB
    - [mongodb-version-manager](https://github.com/mongodb-js/version-manager)
- Node.js
    - [chnode](https://github.com/tkareine/chnode)
    - [fnm](https://github.com/Schniz/fnm)
    - [gnvm](http://ksria.com/gnvm/)
    - [n](https://github.com/tj/n)
    - [nenv](https://github.com/ryuone/nenv)
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
- Pharo
    - [yogurt](https://github.com/fstephany/yogurt)
- PHP
    - [phpenv](https://github.com/phpenv/phpenv)
- Python
    - [pyenv](https://github.com/pyenv/pyenv)
- Ruby
    - [chruby](https://github.com/postmodern/chruby)
    - [frum](https://github.com/TaKO8Ki/frum/)
    - [rbenv](https://github.com/rbenv/rbenv)
    - [rvm](https://rvm.io/)
    - [vruby](https://github.com/joefiorini/vruby)
- Rust
    - [rustup](https://github.com/rust-lang/rustup)
- Solidity
    - [svm](https://github.com/web3j/svm)
- Swift
    - [swiftenv](https://github.com/kylef/swiftenv)
- Terraform and Terragrunt
    - [terraenv](https://github.com/aaratn/terraenv)
    - [tfenv](https://github.com/tfutils/tfenv)
    - [tgenv](https://github.com/cunymatthieu/tgenv)
    - [tvm](https://github.com/johnstanfield/tvm)
- Xcode
    - [xcode-select](https://developer.apple.com/library/archive/technotes/tn2339/_index.html)

## False friends

The following pieces of software all end in -`env` **but are not** runtime version managers:

- Python virtualenv managers
    - [pipenv](https://pipenv.pypa.io/en/latest/)
    - [venv](https://docs.python.org/3/library/venv.html)
    - [virtualenv](https://virtualenv.pypa.io/en/latest/)
- Process environment managers
    - [shadowenv](https://github.com/Shopify/shadowenv)

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
- [pyenv-mode-auto](https://github.com/ssbb/pyenv-mode-auto)

### Integrating with Puppet

- [puppet-rbenv](https://github.com/alup/puppet-rbenv)
- [puppet-rvm](https://github.com/blt04/puppet-rvm)

### Integrating with Vim

- [vim-rvm](https://github.com/tpope/vim-rvm)

### Integrating with zsh

- [zsh-nvm](https://github.com/lukechilds/zsh-nvm)
- [zsh-rbenv](https://github.com/mattberther/zsh-rbenv)

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md).
