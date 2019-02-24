# joshuto

[ranger](https://github.com/ranger/ranger)-like terminal file manager written in Rust.
Currently a work in progress.

![Alt text](joshuto_screenshot.png?raw=true "joshuto")

## Dependencies
 - ncurses
 - [cargo](https://github.com/rust-lang/cargo/) >= 0.32.0
 - [rustc](https://www.rust-lang.org/) >= 1.32.0

Also see [Cargo.toml](https://github.com/kamiyaa/joshuto/blob/master/Cargo.toml)

## Building
```
~$ cargo build
```

## Installation
#### For single user
```
~$ cargo install --force
```
#### System wide
```
~# cargo install --root=/usr/local --force  # /usr also works
```

## Usage
```
~ $ joshuto
```

## Configuration
Place config files inside `$XDG_CONFIG_HOME/joshuto` (usually `$HOME/.config/joshuto/` for GNU/Linux).

Joshuto can currently be configured using the following files:
#### [joshuto.toml](https://github.com/kamiyaa/joshuto/blob/master/config/joshuto.toml)
 - general configurations

#### [keymap.toml](https://github.com/kamiyaa/joshuto/blob/master/config/keymap.toml)
 - for keybindings, please take a look at [keymap.rs](https://github.com/kamiyaa/joshuto/blob/master/src/joshuto/config/keymap.rs) for non-printable keys
 - for commands, please take a look at [command.rs](https://github.com/kamiyaa/joshuto/blob/master/src/joshuto/command.rs) for available commands

#### [mimetype.toml](https://github.com/kamiyaa/joshuto/blob/master/config/mimetype.toml)
 - for opening files with applications

#### [theme.toml](https://github.com/kamiyaa/joshuto/blob/master/config/theme.toml)
 - color customizations


## Contributing
Please create a pull request :)

## Features/Bugs
Please create an issue :)
