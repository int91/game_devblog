# Welcome to the [UNAMED GAME] Dev-Blog

I started development on this game on 12/17/21. It's been really fun working on the game so far and I can't wait for what's to come in the future.


## Starting development - 0.01
So far development on this game has come along great. Working on everything has been a lot of fun, especially making a game launcher that handles version control and the whole ui for the game.

Date: 12/19/21

## Implementing basic systems - 0.02
Don't have too much in the game, but I did work on the menus some and tweaked the character panel. Now you have a working mining system, inventory, and crafting system. I just have to fully implement these features and work more on polishing them as well.

I also had to essentially recode my entire codebase as I was overusing signals. Signals were leading to functions that called other signals and so on. It was too much of a mess to make a good game, plus it was super tedious to add a new signal and test it. So now I've switched to the normal function calls as opposed to a million signals.

[![Menus](https://i.gyazo.com/00c669800c6e56e8e854d2a2fd734762.gif)](https://gyazo.com/00c669800c6e56e8e854d2a2fd734762)

Menus: [https://gyazo.com/00c669800c6e56e8e854d2a2fd734762](https://gyazo.com/00c669800c6e56e8e854d2a2fd734762)

[![Early Mining UI](https://i.gyazo.com/8c5e4a4a60b039bc21759b8944ad0b02.gif)](https://gyazo.com/8c5e4a4a60b039bc21759b8944ad0b02)

Early Mining UI: [https://gyazo.com/8c5e4a4a60b039bc21759b8944ad0b02](https://gyazo.com/8c5e4a4a60b039bc21759b8944ad0b02)

[![Mining UI So Far](https://i.gyazo.com/3b31ae4142fe5e7742ff9a5810e1c9fc.gif)](https://gyazo.com/3b31ae4142fe5e7742ff9a5810e1c9fc)

Mining UI So Far: [https://gyazo.com/3b31ae4142fe5e7742ff9a5810e1c9fc](https://gyazo.com/3b31ae4142fe5e7742ff9a5810e1c9fc)

Date: 12/20/21
