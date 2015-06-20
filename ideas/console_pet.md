# Console Pet

A command line based pet similar to [Tamagotchi][tam].

* Pet status is displayed in a separate window/tab.
* Game `tick`s are based on timing or number of commands entered
* Extract game engine
* Written in Elixir
 - Track each attribute in separate processes
 - When command is issued, connect to running central process and send message

[tam]: https://en.wikipedia.org/wiki/Tamagotchi
