# FUEL
A example repository for creating your own FUELS.

# Syntax
FUEL uses the same syntax as python.

# What makes it special?
You can set properties that FyUTILS can use in the `cmd.props` file. Here is a little tutorial for every key that can be set.
- name: The command name the FUEL should be executed with, for example: `test` (string)
- use_api*: If your script needs access to FyUTILS API (boolean)

* `use_api` is deprecated, and you technically don't need it, because all FUELS automatically are having access to the API.
