# ReNameR
A simple (and probably dirty) files mass-renamer in ruby.

This script has two functions:
 1. compact: renames a file to a CamelCase format, removing spaces and
    using capital letters to separate words. Other capital letters are
    converted to lower case.
 2. widen: renames a file adding spaces when needed.
Note that both these functions are recursive for folders.

When renaming a file, if there already is one with the destination name, a
numeric index will be appended before the file extension.

It allows per-user configuration through a YAML file located in $HOME/.rnr.

Tested on ruby version 2.3.1.

Run the script (with -h, maybe) and it will notify you of any gem it requires 
that has not been found on the system.

Every other info you may need about this script can be found either running it
with the -h flag, or by reading its source code.

