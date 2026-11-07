# Linux - Core Concepts

## 1. What is Linux?

Linux is an open-source operating system used on servers,
cloud infrastructure, containers and many other systems.

It is widely used in DevOps because many production workloads,
Docker containers, Kubernetes nodes and CI/CD environments
run on Linux.

## 2. Linux Distributions

A Linux distribution is an operating system built around
the Linux kernel with additional software and tools.

Examples:

- Ubuntu
- Debian
- Red Hat Enterprise Linux
- CentOS
- Amazon Linux
- Alpine Linux

This ESC BASH course uses Ubuntu.

## 3. The Shell

A shell is a command-line program that accepts commands
from users and executes them.

Bash (Bourne Again Shell) is a commonly used shell.

## 4. Understanding the Linux Prompt

Example:

root@abc123:~#

- root: Current username
- abc123: Hostname
- ~: Current home directory
- #: Root user prompt symbol

A regular user generally sees `$` instead of `#`.

## 5. Commands and Flags

Commands perform operations in Linux.

Flags modify how commands behave or what information
they display.

Example:

uname -a

Here:
- uname is the command.
- -a is the option.

## 6. Absolute and Relative Paths

Absolute path:
A complete path beginning with /.

Example:
 /etc/hostname

Relative path:
A path interpreted from the current directory.

Example:
 notes/file.txt

## 7. Output Redirection

The > operator redirects command output into a file.

Example:

whoami > user.txt

Important:
- Creates the file if it doesn't exist.
- Overwrites existing file contents.

## 8. Tab Completion

Pressing Tab helps complete commands and file paths
automatically in the shell.

## 9. Keyboard Shortcuts

- Ctrl + C: Interrupt a running command.
- Ctrl + L: Clear the terminal screen.
- Up Arrow: Retrieve previous commands.