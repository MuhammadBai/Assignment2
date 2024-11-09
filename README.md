# Assignment2 : Shell Scripting

## Overview
In this assignment, i have developed two shell scripting projects which automates system setup tasks and user managment on an Arch Linux environment. The scripts follows the best practices, focusing on error handling, documentation, and utilizing 'getopts' for command=line options.

---

## Project 1: System Setup Scripts

### Purpose
This project automates the installation of essential software packages and creates symbolic links to configuration files stored in a remote Git repository. It speeds uo the sustem setup process, making it fast and repeatable.

1. `packages_list`
 This script generates a list of software packages that will be installed during setup which are kakoune and tmux.
 
 * **Purpose**: This automates the creation of a list (`pkgs.txt`) which contains names of software packages to install.\n
 * **Function**: This adds each specified package to `pkgs.txt` and prints the package name on the console for confirmation.
 * **Its use**: `./packages_list`
 * It creates a lists of packages inside pkgs.txt.
