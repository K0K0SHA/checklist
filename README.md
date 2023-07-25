# checklist
simple checklist to-do TUI app
run it in terminal, command-prompt, or Powershell
cross-OS compatible; tested and developed primarily on Linux

## installation
Only requirements are python3, pip3, and the following libraries installable on Mac, Android, Linux, or any other system with curses support by using:
pip3 install <lib>

## libs needed:
import os
import json
import curses

## For Windows users:
Since Python for Windows has no support for curses, try using UniCurses port:
https://pypi.org/project/UniCurses
