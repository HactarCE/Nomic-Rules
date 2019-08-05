# Game Rules

This is the base rule set for the Quonauts 5 Nomic.

## Table of contents

* [Meta rules](#meta-rules)
    * [Precedence](#precedence)
    * [Disallowed by default](#disallowed-by-default)
    * [Rule violations](#rule-violations)
        * [Errors](#errors)
        * [Rule violation polls](#rule-violation-polls)
        * [Punitive action](#punitive-action)
    * [Bots](#bots)
* [Channels](#channels)
    * [#general](#general)
    * [#proposals](#proposals)
    * [#polls](#polls)
    * [#game-rules](#game-rules)
* [Activity](#activity)
* [Quantities](#quantities)
* [Polls](#polls)
* [Proposals](#proposals)
    * [Voting on proposals](voting-on-proposals)
    * [Closing proposals](closing-proposals)
    * [Passing and failing proposals](passing-and-failing-proposals)
* [Style conventions](#style-conventions)
    * [Content](#content)
    * [Headers and tags](#headers-and-tags)
    * [Lists](#lists)
    * [Formatting](#formatting)
* [Glossary](#glossary)

## Meta rules

This section details how the rules are to be applied to the game.

### Accuracy

This document is not guaranteed to always be up-to-date as the game rules are modified, however it is the duty of all players to keep this document accurate as game rules are modified. Where this document disagrees with the game rules, players must follow the game rules as they legally are, rather than their description in this document.

### Precedence

In the case of a contradiction between clauses, the following criteria are to be considered in turn until a clear determination can be made as to which clause takes precedence:

1. If one clause has a more limited scope than another, then the clause with the more limited scope takes precedence.
2. If one clause is negative while the other is positive, then the negative clause takes precedence.
3. The clause which appears last in the rules takes precedence.

### Disallowed by default

Unless explicitly stated in the rules, all game actions are forbidden.

### Rule violations

A rule violation is a game action that is not permitted by the rules.

A rule violation is "resolved" by reversing the immediate effects of that rule violation (not including any indirect effects permitted in reaction to the rule violation) to the extent that it is possible.

#### Errors

An error is a rule violation made by a player either mistakenly or through ignorance. If this player is resolve the error, they may do so.

If a player resolves an error within 24 hours of making that error, any rule violation poll for that error immediately fails. A rule violation poll may not begin after a player resolves an error; however, existing rule violation polls may continue if the error remained unresolved for 24 hours.

#### Rule violation polls

If any player (hereby "the accusing player") believes that another player (hereby "the accused player") has violated the rules, then the accusing player may conduct a majority poll (called a "rule violation poll") to determine whether the accused player has violated the rules.

In conducting a rule violation poll, the accusing player must describe which sections or clauses of the rules were violated and what illegal game action was taken by the accused player. Players should vote in favor of this poll if, and only if, they agree that the accused player violated the rules as described.

Any vote in such a poll cast by the accused player is not counted.

A rule violation poll must be available for voting for at least 24 hours before any action may be taken as a result.

For any potential rule violation, only one rule violation poll may be conducted.

A rule violation poll may not be started more than 7 days after the potential rule violation.

If a rule violation poll passes, then the accused player is now convicted of violating the rules as described in the poll and the rule violation must be resolved, if it has not already.

#### Punitive action

If a player (hereby "the convicted player") is convicted, then another player may conduct a majority poll (called a "puninitive action poll") to determine whether punitive action should be taken.

Players should vote in favour of this poll if, and only if, they believe the convicted player violated the rules knowingly and with malicious intent.

Any vote in such a poll cast by the convicted player is not counted.

If a punitive action poll passes, then the convicted player gains one strike.

### Timezones

Unless otherwise specified, all times and dates are specified with respect to UTC.

### Bots

Certain game functions may be performed automatically by automated "bots;" the behavior of such bots is not governed by the rules, and any function that bots may perform should be feasible, even if inconvenient, to do manually.

### Style conventions

This section and its subsections describe grammatical and stylistic conventions used throughout this ruleset.

Any player may edit the rules to conform to these style conventions. Edits made this way must otherwise be minimal; i.e. they may not change wording or meaning.

#### Content

* All rules should be written in English using proper English grammar and spelling. American and British English spelling are both acceptable.
* Where applicable, rules should be written using gender-neutral language, with "they/them/their" as a third-person pronoun, both singular and plural.
* Sentences should be separated by a single space.
* Paragraphs should be separated by a blank line.
* Each paragraph or list element must be shorter than 1000 characters.
* Rules may not contain invisible characters besides newlines, normal spaces, and (in special cases) tabs. Non-ASCII characters should be used sparingly.
* Double quotes should be preferred instead of single quotes. ASCII-compatible straight quotes should be used instead of "smart" quotes.

#### Headers and tags

* Each section must have a header and a tag.
* Headers must use [sentence case](https://en.wiktionary.org/wiki/sentence_case), and must be a short, succinct word or phrase (not a complete sentence) describing the section.
* A section tag must be a string of text begin with a lowercase letter, end with either a lowercase letter or a number, and may contain only lowercase letters `a`-`z`, digits `0`-`9`, and hyphens `-`.
* A rule's tag should resemble its header.
* Tags must be unique; no two rule sections may have the same tag.

#### Lists

* Unordered lists should use a single asterisk followed by a space (`* `) before each list element.
* Ordered lists should use a single number followed by a period and a space (`1. `) before each list element.
* The numbers of a ordered list should start at `1` and increase by `1` for each element.
* Lists should not be nested.
* Lists should be separated by the paragraphs above and below by a blank line.
* Two lists of the same type can not be adjacent. (This is treated as one list when converted to Markdown.)

Within a given list, all elements should have the same style, chosen from the following:

* Elements are words or phrases, and do not end with a period.
* Elements are clauses ending in a period (or other punctuation), and optionally followed by complete sentences.
* Elements are complete sentences ending in a period, and optionally followed by more complete sentences.

#### Formatting

From [GitHub's "Mastering Markdown" document](https://guides.github.com/features/mastering-markdown/), the following may be used:

* Emphasis (italics and bold, not including double underscore `__`)
* Unordered and ordered lists (not nested)
* Links
* Inline code
* Automatic linking for URLs
* Strikethrough

Additionally, square brackets `[]` containing a tag will be converted into links to another rule section; e.g. `[%rule-tag]`. Discord mentions (@username, @role, and #channel) may be used, however they are not readable in GitHub-flavored markdown.

### Glossary

The definitions for terms listed here take precedence over their normal English meanings, however any terms defined in a specific section of the rules override these in the section in which they are defined and any subsections of that section. A section may also define terms for use in the whole document.

* **The Game**: The instance of Nomic which is governed by this rules document.
* **Game Action**: A game action is any message or reaction in a game channel or any other manipulation of game channels or quantities which are part of the game.
* **Game State**: A specific arrangement of all game rules, proposals, polls, votes and quantities.
* **Game Channel**: A game channel is any text or voice channel listed in the GAME CHANNELS channel category of the Discord server.
* **Player**: Any participant of the game.
* **The Rules**: The rules of the game, which are described by this document.
* **Section**: A part of the rules which is contained under one header, not including any subsections.
* **Subsection**: A section of the rules which is contained under another section.
* **Clause**: A single statement in the rules

## Channels

The game rules govern only messages and reactions in the GAME CHANNELS category of the Discord server.

Each subsection of this rule section corresponds to a game channel; as these subsections are created, removed, or reordered, game channels must be created/renamed/reordered accordingly.

### #general

Players may converse freely in the #general channel.

### #proposals

The #proposals channel is governed by [%proposals].

### #polls

The #polls channel is governed by [%polls].

### #rules

The #rules channel contains this rules document.

## Roles

### Rule offender

If a player has a nonzero number of strikes, then they are given the "rule offender" role. If a player's number of strikes reaches zero, the "rule offender" role is removed.

Players with the "rule offender" role may not make any game action; i.e. they may not participate in the game.

After 24 hours with the "rule offender" role, a player's number of strikes decreases by one.

## Activity

All players that have taken some game action in the preceding 72 hours are active players. All other players are inactive players.

## Quantities

A quantity is a named property with a numerical value for each player.

By default any unique quantity added to the game:

* applies to all players.
* is instatiated at zero.
* must always be an integer.
* must never have a negative value.
* cannot be traded or exchanged.

Existing quantities:

* **Strike**: The number of rule violations that a player has committed without punishment.

## Polls

A poll is a means of gathering the opinions of players on an issue. Players may conduct a poll by providing any necessary detail and posing a question in the #polls game channel. A poll that grants power to perform a game action or otherwise makes some formal determination (e.g. [%rule-violation-polls]) are formal polls; all others are informal polls.

Players may vote in favor of a poll by reacting to the poll with :thumbsup:. Players may vote against a poll by reacting to the poll with :thumbsdown:.

Players may use any reaction they wish to respond to a poll. The player conducting the poll may interpret other reactions to the poll as they see fit, except in formal polls, where reactions may only have meaning as specified in the rules.

The player that posted a poll may edit it freely, as long as such edits do not change the meaning/intent of any existing reactions to the poll.

## Proposals

Players may submit proposals by posting their proposal to the #proposals game channel.

The first proposal is numbered #1 and each subsequent proposal's number is increased by 1. Deleted proposals retain their number.

A proposal can describe any number of actions that make changes to the game rules or otherwise alter the game state.

A proposal is either open or closed. When it is first submitted a proposal is open. A closed proposal is either passed or failed. When a player closes a proposal, they must either pass it or fail it.

### Proposal content

A proposal can describe any number of actions that make changes to the game rules or otherwise alter the game state.

If a proposal describes a modification to the rules, it must unambiguously specify the rule section(s) to be modified and how they will be modified. Text quoted between the outermost `[start]` and `[end]` symbols (brackets required; code tags optional) is to be interpreted literally. `[start]` and `[end]` symbols can be nested.

If a proposal describes the creation of a new rule section, it must specify its title, its location in relation to an existing one, and its content.

#### Conflict resolution

If multiple proposals describe the modification or addition of sections, paragraphs, or sentences to the same part of the rules, conflicts should be resolved based on the age of the proposal, such that the newer proposal's effect overrides the older one's. For example, if proposal #10 adds a new section "A" to the bottom of the rules, and proposal #11 adds a new section "B" to the bottom of the rules, and both proposals pass, then regardless of which proposal passed first, section "B" will appear below section "A" in the rules.

#### Dependency resolution

A proposal may state that it depends on other proposals. If a proposal's dependencies fail, then the proposal dependent on them also fails.

A proposals may amend an existing proposal. If a proposal A amends an existing proposal B, then the amendment has no effect if B fails. If A and B both pass, then the result of proposal B is undone or modified according to proposal A. The content of proposal B, however, does not change.

A proposal may also state incompatible proposals, in which case the later proposal will fail if any proposal it is incompatible proposal on is passed.

### Voting on proposals

Each player may cast one vote on each open proposal.

Players may vote for or against a proposal. Players may also explicitly abstain from voting.

A player may change their vote on an open proposal at any time.

### Closing proposals

Any player may close an open proposal if one or more of the following conditions is met:
 * The proposal is at least 48 hours (2 days) old.
 * All active players have cast a vote on the proposal.
 * A majority of active players have voted in favor of the proposal.
 * A majority of active players have voted against the proposal.

The player that authored a proposal may fail or delete it at any time.

When a player passes a proposal, that player must carry out the effects of that proposal and its passing to the best of their ability.

### Passing and failing proposals

When a proposal is closed, it passes if it has more votes in favour than against; otherwise, it fails.

### <a name='proposal-modification'/> Proposal modification

A player may edit a proposal they have submitted if that proposal is open for voting and has no votes cast by players other than its author.
