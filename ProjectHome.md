dbus-tools is a set of tools to help developers playing with DBus. Take a simple example: you are making a brand new DBus interface for your project and want to test it. You have three solutions for that:
  * Write your own program. Just for a simple test, that's pretty annoying
  * Use dbus-send. Well, but dbus-send is a crappy unusable tool
  * Having fun with dbus-cli

Right now, dbus-tool is a **really** little project containing two elements - but if you have more ideas, just do (or propose) it :)
  * dbus-cli, a tool similar to kde's dcop tool but for dbus
  * _dbus, ZSH completion for_dbus cli