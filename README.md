<!--
SPDX-FileCopyrightText: 2025 Jason Pena <jasonpena@awkless.com>
SPDX-License-Identifier: MIT
-->

# Dash Dotfiles

Dash (POSIX shell) dotfiles.

Simple configuration I use for dash or POSIX standard shells. I use it as a
base for other shell environment configurations in order to carry over common
features and settings I want across different environments.

## Features

- Sets up default locations for XDG Base Directory environment variables.
- Connects `$PATH` to local binary paths.
    - Includes binary paths for Rust and Ruby.
- Configures application settings through environment variables.
- Configures GPG SSH agent.
- Starts up X server.
- Enables Vi mode.
- Sets up custom PS1 using [polyglot][polyglot_ps1].

## License

This dotfile configuration is placed under the MIT license using [REUSE 3.3
specification][reuse-3.3] to make license, and copyright information as clear
as possible.

[polyglot_ps1]: https://github.com/awkless/polyglot
[reuse-3.3]: https://reuse.software/spec-3.3/
