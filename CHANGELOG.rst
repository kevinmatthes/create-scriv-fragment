.. --------------------- GNU General Public License 3.0 --------------------- ..
..                                                                            ..
.. Copyright (C) 2023 Kevin Matthes                                           ..
..                                                                            ..
.. This program is free software: you can redistribute it and/or modify       ..
.. it under the terms of the GNU General Public License as published by       ..
.. the Free Software Foundation, either version 3 of the License, or          ..
.. (at your option) any later version.                                        ..
..                                                                            ..
.. This program is distributed in the hope that it will be useful,            ..
.. but WITHOUT ANY WARRANTY; without even the implied warranty of             ..
.. MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the              ..
.. GNU General Public License for more details.                               ..
..                                                                            ..
.. You should have received a copy of the GNU General Public License          ..
.. along with this program.  If not, see <https://www.gnu.org/licenses/>.     ..
..                                                                            ..
.. -------------------------------------------------------------------------- ..

.. -------------------------------------------------------------------------- ..
..
..  AUTHOR      Kevin Matthes
..  BRIEF       The development history of this project.
..  COPYRIGHT   GPL-3.0
..  DATE        2023
..  FILE        CHANGELOG.rst
..  NOTE        See `LICENSE' for full license.
..              See `README.md' for project details.
..
.. -------------------------------------------------------------------------- ..

.. -------------------------------------------------------------------------- ..
..
.. _changelog.d: changelog.d/
.. _Keep a Changelog: https://keepachangelog.com/en/1.0.0/
.. _Scriv: https://github.com/nedbat/scriv
..
.. -------------------------------------------------------------------------- ..

Changelog
=========

All notable changes to this project are documented in this file.  The format is
based on `Keep a Changelog`_ and optimised for maintenance with `Scriv`_.

Unreleased
----------

All pending changelog entries are stored in `changelog.d`_.

.. scriv-insert-here

.. _changelog-0.2.2:

0.2.2 — 2023-03-01
------------------

Added
.....

- documentation:  software license for ``actions/checkout``

- documentation:  software license for ``actions/setup-python``

- documentation:  software license for ``cut``

- documentation:  software license for ``echo``

- documentation:  software license for ``fregante/setup-git-user``

- documentation:  software license for Git

- documentation:  software license for ``grep``

- documentation:  software license for ``kevinmatthes/validate-boolean``

- documentation:  software license for ``py-actions/py-dependency-install``

- documentation:  software license for ``rm``

- documentation:  software license for Scriv

- README:  document new directory ``LICENSEs``

Changed
.......

- README:  adjust branding information description

- Action:  adjust indentation

- Action:  fetch configured Git name dynamically

- README:  adjust documentation of inputs and outputs

- README:  "GitHub Actions bot" instead of "GitHub Actions Bot"

Removed
.......

- GitHub Action workflows:  ``ad-m/github-push-action@v0.6.0`` as dependency

.. _changelog-0.2.1:

0.2.1 — 2023-02-09
------------------

Added
.....

- Bors:  initial setup

- README:  Bors badge

Changed
.......

- Action:  add commit message prefix ``github-actions[bot]:``

.. _changelog-0.2.0:

0.2.0 — 2023-01-22
------------------

Added
.....

- CODEOWNERS

- CI:  GitHub Action self-test

Changed
.......

- update to Python 3.11

- CI:  rename CFF validation workflow to ``ci.yml``

- README:  change CFF validation badge to CI badge

.. _changelog-0.1.2:

0.1.2 — 2023-01-13
------------------

Changed
.......

- Dependabot(deps): Bump actions/setup-python from 4.4.0 to 4.5.0

- Dependabot(deps): Bump kevinmatthes/release-bump2version-scriv

Removed
.......

- Dependabot:  Python 3 setup

.. _changelog-0.1.1:

0.1.1 — 2023-01-08
------------------

Changed
.......

- bump2version:  track moved Scriv settings file

- Scriv:  move settings to fragment storage

- use own GitHub Action for release preparations

Removed
.......

- placeholder in Scriv fragment storage

- Python 3 software requirements list

.. _changelog-0.1.0:

0.1.0 — 2023-01-06
------------------

Added
.....

- create this repository

- license:  GPL-3.0

- repository README

- list of Python 3 software requirements

- Python 3 software requirement:  bump2version

- Python 3 software requirement:  Scriv

- create Scriv fragment storage

- GitHub Action workflow:  Scriv fragment creation

- Scriv:  settings

- bump2version:  settings

- CITATION.cff

- create GitHub Action source file

- Dependabot:  GitHub Action setup

- Dependabot:  Python 3 setup

- GitHub Action workflow:  CFF validation

- GitHub Action workflow:  release

- README:  detailed description

- README:  license information

- this CHANGELOG

- copyright year:  2023

- make Scriv fragment creation workflow use this repository's Action

.. -------------------------------------------------------------------------- ..
