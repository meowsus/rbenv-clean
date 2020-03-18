# rbenv-clean
`rbenv-clean` is a plugin for rbenv that aids in removing gems from your Ruby environment. 

A "fork" of @jbernsie's work after he mysteriously disappeared from this planet.

## Installation

- `$ mkdir -p ~/.rbenv/plugins # create the plugins dir if you haven't already`
- `$ git clone https://github.com/meowsus/rbenv-clean ~/.rbenv/plugins/rbenv-clean`

## Usage

> Uninstall all non-default gems in Ruby 2.5.1 and leave every other version un-touched
```
$ rbenv clean -v 2.5.1
```

> Uninstall all non-default gems in the current global version
```
$ rbenv clean -c
```

> Nuke the entire environment
```
$ rbenv clean -a
```

> View help
```
$ rbenv clean -h
```
