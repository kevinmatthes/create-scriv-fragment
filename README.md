<!---------------------- GNU General Public License 3.0 ------------------------
--                                                                            --
-- Copyright (C) 2023 Kevin Matthes                                           --
--                                                                            --
-- This program is free software: you can redistribute it and/or modify       --
-- it under the terms of the GNU General Public License as published by       --
-- the Free Software Foundation, either version 3 of the License, or          --
-- (at your option) any later version.                                        --
--                                                                            --
-- This program is distributed in the hope that it will be useful,            --
-- but WITHOUT ANY WARRANTY; without even the implied warranty of             --
-- MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the              --
-- GNU General Public License for more details.                               --
--                                                                            --
-- You should have received a copy of the GNU General Public License          --
-- along with this program.  If not, see <https://www.gnu.org/licenses/>.     --
--                                                                            --
------------------------------------------------------------------------------->

<!------------------------------------------------------------------------------
--
--  AUTHOR      Kevin Matthes
--  BRIEF       Important information regarding this project.
--  COPYRIGHT   GPL-3.0
--  DATE        2023
--  FILE        README.md
--  NOTE        See `LICENSE' for full license.
--
------------------------------------------------------------------------------->

# create-scriv-fragment

## Summary

[![](https://github.com/kevinmatthes/create-scriv-fragment/workflows/ci/badge.svg)](https://github.com/kevinmatthes/create-scriv-fragment/workflows/ci)
[![](https://img.shields.io/github/license/kevinmatthes/create-scriv-fragment)](https://github.com/kevinmatthes/create-scriv-fragment)

A GitHub Action to create a blank Scriv fragment.

1. [License](#license)
2. [Description](#description)

## License

[![](https://img.shields.io/github/license/kevinmatthes/create-scriv-fragment)](https://github.com/kevinmatthes/create-scriv-fragment)

This project's license is **GPL-3.0**.  The whole license text can be found in
`LICENSE` in the main directory of this repository.  The brief version is as
follows:

> Copyright (C) 2023 Kevin Matthes
>
> This program is free software: you can redistribute it and/or modify
> it under the terms of the GNU General Public License as published by
> the Free Software Foundation, either version 3 of the License, or
> (at your option) any later version.
>
> This program is distributed in the hope that it will be useful,
> but WITHOUT ANY WARRANTY; without even the implied warranty of
> MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
> GNU General Public License for more details.
>
> You should have received a copy of the GNU General Public License
> along with this program.  If not, see <https://www.gnu.org/licenses/>.

## Description

This GitHub Action will create a new Scriv fragment.  It assumes that Scriv is
already configured and that the fragment storage exists.  The user creating the
fragment will be the GitHub Actions Bot.

It is recommended to execute this Action on a Linux runner.  This Action
requires a Bash shell environment.  The repository needs to be checked out
before the Action can be called.  After it has finished, the changeds need to
be pushed back to the repository.

This Action does neither accept and / or require any inputs nor it returns any
outputs.

The branding settings (green background colour with the symbol `book` as icon)
were chosen due to the default use case of this Action.  The book symbolises
the documentation Scriv shall enhance.  The colour green is often associated
with the season spring which also symbolises the beginning of something new;
here, it is the creation of a new fragment.

To apply this Action, just add the following line to the step section of a
GitHub Action workflow job.

```yaml
      - uses: kevinmatthes/create-scriv-fragment@v0.1.2
```

<!----------------------------------------------------------------------------->
