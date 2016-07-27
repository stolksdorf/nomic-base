# nomic
Github-based game of [Nomic](https://en.wikipedia.org/wiki/Nomic)

# what is nomic

> Nomic is a game in which changing the rules is a move. In that respect it differs from almost every other game. The primary activity of Nomic is proposing changes in the rules, debating the wisdom of changing them in that way, voting on the changes, deciding what can and cannot be done afterwards, and doing it. Even this core of the game, of course, can be changed.

_— Peter Suber, The Paradox of Self-Amendment_

# how to play

All you need is a github account. All rules will always be recorded in the [rules.md] and all scores/players/reosurces and turn order will be recorded in the [players.md].

### propose a rule change

1. Click the `README.md` ![](http://i.imgur.com/gtWUHWd.jpg)
2. Click the lil' pencil icon to edit the file ![](http://i.imgur.com/rGYJ88i.jpg)
3. Write your proposed change in [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet). Give a short title to your change, and an more in-depth reasoning behind it. Then click `propose file change`. ![](http://i.imgur.com/3rlMJVc.jpg)
4. Click `Create Pull Request` twice and you're done!

### comment and vote on changes

1. Click the Pull requests tab off to the left. ![](http://i.imgur.com/eP2OUwe.jpg)
2. Find the open pull request (there should usually only be one)
3. Write your comment or vote. For voting, start your comment with "AGREED" or "DECLINE", followed by X/Y, which stands for how many people are in favour / how many people have voted. This gives us a easily check-able state of voting at a glance. ![](http://i.imgur.com/F1j6NF0.jpg)

### transfers
To initiate  a transfer of any kind between two players, one of those players submits a pull request for the [players.md](players.md) outlining the exchange. The other participant must approve the proposed exchange in the comments. Once approved a Mod will merge the change in. Please mark any transfer pull request by starting the pull request name with 'TRANSFER'.


### implicit rules
There are some aspects of the game that will not be listed as a changable rule, but still will take effect. Most of these will be obvious, but we'll list them here for reference.

* Players will obey the rules at all times
* Players are considered playing the game unless explicitly stated
* It is assumed that when you propose a rule change, you are in favour of it. If you wish to vote against your own rule, you must state that within the pull request of the proposal.

### moderators

Each moderator will be set as a `collaborator` on the github repo, all other players will be `contributors`. Their job is to merge in approved pull requests, close disapproved ones, and update scores if need be. We will have two moderators


### the arbiter
The arbiter is an impartial non-player who, if need be, can be used for the game. eg. Determining the starting player order.
