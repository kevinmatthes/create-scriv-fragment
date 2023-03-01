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

[![](https://bors.tech/images/badge_small.svg)](https://app.bors.tech/repositories/60488)
[![](https://github.com/kevinmatthes/create-scriv-fragment/workflows/ci/badge.svg)](https://github.com/kevinmatthes/create-scriv-fragment/workflows/ci)
[![](https://img.shields.io/github/license/kevinmatthes/create-scriv-fragment)](https://github.com/kevinmatthes/create-scriv-fragment)

A GitHub Action to create a blank Scriv fragment.

1. [License](#license)
1. [Description](#description)
1. [Branding Information](#branding-information)

## License

[![](https://img.shields.io/github/license/kevinmatthes/create-scriv-fragment)](https://github.com/kevinmatthes/create-scriv-fragment)

This project's license is **GPL-3.0**.  The whole license text can be found in
[`LICENSE`](LICENSE) in the main directory of this repository.  The brief
version is as follows:

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

License information about the dependencies this software requires to work
can be found in [`LICENSEs`](LICENSEs).

## Description

This GitHub Action will create a new Scriv fragment.  It assumes that Scriv is
already configured and that the fragment storage exists.  The user creating the
fragment will be the GitHub Actions bot.

It is recommended to execute this Action on a Linux runner.  This Action
requires a Bash shell environment.  The repository needs to be checked out
before the Action can be called.  After it has finished, the changeds need to
be pushed back to the repository.  There are neither inputs nor outputs.

To apply this Action, just add the following to the step section of a GitHub
Action workflow job.

```yaml
      - uses: kevinmatthes/create-scriv-fragment@v0.2.2
```

## Branding Information

The branding of this Action uses the icon `book` on a green background.  The
shall symbolise the documentation which is going to be enriched with further
information while the green colour represents the creation of the therefore
required Scriv fragment.

<!----------------------------------------------------------------------------->
