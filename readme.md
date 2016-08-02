# nomic
Github-based game of [Nomic](https://en.wikipedia.org/wiki/Nomic), a game where the only move is to change the rules of the game.

## what is nomic

> Nomic is a game in which changing the rules is a move. In that respect it differs from almost every other game. The primary activity of Nomic is proposing changes in the rules, debating the wisdom of changing them in that way, voting on the changes, deciding what can and cannot be done afterwards, and doing it. Even this core of the game, of course, can be changed.

_— Peter Suber, The Paradox of Self-Amendment_

## how to play
All you need is a github account. All rules will always be recorded in the [rules.md](./rules.md) and all information about players and resources will be recorded in the [players.md](./players.md).

### propose a rule amendment
1. Click `rules.md`
2. Click the pencil icon to edit the file.
3. Write your proposed change in [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet). Give a short title to your change, and an more in-depth reasoning behind it. Then click `propose file change`.
4. Click "Propose file change" then "Create Pull Request".

### comment and vote on amendments
1. Click the 'Pull requests' along the top.
2. Click on the pull request you wish to vote or comment on.
3. Write your comment or vote. For voting, use the reactions on the top comment to vote. :+1: to vote for it and :-1: to vote against.
4. Only mods can merge in approved pull requests. Once a pull request is approved following the rules, add a message to the pull request using `@username` to notify the mod it's ready to be merged.

### conflicting pull requests
Sometimes two pull requests may both be modifying the same part of the rules. If one is merged in before the other, the outstanding pull request may become _conflicted_. Github will display a grey message on the pull request indicating this. The proposer will have to close the conflicted pull request, create a new one that is not conflicting, and begin the voting process again.

## implicit rules
There are some aspects of the game that will not be listed as a changable rule, but still will take effect. Most of these will be obvious, but we'll list them here for reference.

1. Players will obey the rules at all times
1. Players are considered playing the game unless explicitly stated
1. No rule-change may take effect earlier than the moment of the completion of the vote that adopted it, even if its wording explicitly states otherwise. No rule-change may have retroactive application.
1. If ever there is a disagreement over the intepretation of the rules that can not be resolved by the players, the arbiter may be called upon to cast judgment on the intepretation.
1. Amendments are to be merged in chronoloigcal order of when they are accepted.

### transfers
To initiate  a transfer of any kind between two players, one of those players submits a pull request for the [players.md](players.md) outlining the exchange. The other participant must approve the proposed exchange in the comments. Once approved a Mod will merge the change in. Please mark any transfer pull request by starting the pull request name with 'TRANSFER'.

### moderators
Each moderator will be set as a `collaborator` on the github repo, all other players will be `contributors`. Their job is to merge in approved pull requests, close disapproved ones, and update resources if need be. There should be a minimum of two moderators.

### the arbiter
The arbiter is an impartial non-player who, if need be, can be used for the game. eg. Determining ambigous rules, producing random numbers/results.
