# LSD-Base2

## LICENSE NOTICE

LSD-Base2 is released under GPL3, see section LICENSE in README.md and the
LICENSE in the top directory of the source tree.

## What is it?

Foundational scripts for the authors publicly released software:

- Reusable shell functions
- Reusable make rules

- A concept  and infrastructure  for hooking  packages into  the shell
  environment  in   their  source   tree  instead  of   installing  by
  copying.  The  author uses  this  extensively  for developing  small
  programs and scripts and distributing them on his computers.


## INSTALLING

At the source tree top directory type 'make install'. Then insert the
shell script fragment from dot-script/dot-bash_profile.boilerplate
somewhere in your shell profile.

All script packages are hooked under ~/.scripts and the shell script
fragment just reads and eveluates their respective profiles.

(More explanation to come: In future releases).

## LICENSE

    LSD-Base 2 
    Copyright (C) 2015 -- M E Leypold

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.

