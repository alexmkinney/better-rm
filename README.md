# better-rm
A more verbose and user-friendly implementation of `rm` for Bash. Copy it or source it in your .bashrc or .bash_aliases.

This script overrides the default `rm` command in interactive shells. Its primary purpose is not to be a safer implementation, but a more explicit and verbose one. It will not protect you from irrecoverably deleting important files. For a safer `rm`, see `trash-cli`.

When executed, this script will show a list of all files passed into it and verbosely remove them with `rm -Iv`. It maintains full compatibility with all command-line arguments of `rm`.
