# ANSI Stripper

This extension replaces ANSI escape sequences with the empty string, making
things like GitLab pipeline logs a lot more readable.

This is a modified version of the Mozilla emoji-substitution [^1] example, the
only changes are the dictionary that contains the tokens to be replaced.

For me, this is good enough. This plugin may never see significant updates.


[^1]: https://github.com/mdn/webextensions-examples/tree/main/emoji-substitution
