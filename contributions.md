# Contributions

To add a tool and its version syntax, fork this repo, add your tool, and make a pull request.

To add a tool to the list of tools, prefix the tool name with `tools_` and add the correct version argument.

Example:

For a tool named `foo` with a version argument of `--help` write:

`tools_foo=--help`

Please make sure to insert it alphabetically within the existing list.

If the tool has a hyphen `-` character in its name, substitute an underscore `_` character instead. The script will correctly sanitize the input and look for the right tool.

Example:

A tool named `foo-bar` becomes `tools_foo_bar` in the list. Typing `hlp foo-bar` will work as expected.

If the argument is not `-h`, or `--help` then I'll definitely need to verify it. A link to an official man page would help.

## Alternately...

Just file an issue listing the tool name and the correct syntax for finding the version. I'll get to it either way.

## Errors

If you find an error, report an issue.
