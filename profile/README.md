# Friend Safari

## Projects

| Name                                                                            | Upstream                                                           | Status                                                 |
| ------------------------------------------------------------------------------- | ------------------------------------------------------------------ | ------------------------------------------------------ |
| [pokeemerald-expansion](https://github.com/friend-safari/pokeemerald-expansion) | [rhh-hideout](https://github.com/rh-hideout/pokeemerald-expansion) | Started; up to **1.16.1**                              |
| [pokeemerald](https://github.com/friend-safari/pokeemerald)                     | [pret](https://github.com/pret/pokeemerald)                        | Started; gathering contributor info                    |

## Tools

This table is a living list of software / tools used in romhacking and their policies around AI:

| Name                                                        | Description              | Notes                                                                                                                 |
| ----------------------------------------------------------- | ------------------------ | --------------------------------------------------------------------------------------------------------------------- |
| [porymap](https://github.com/huderlem/porymap)              | Gen 3 Map Editor         | None apparent; human authored and maintained                                                                          |
| [porydaw](https://github.com/huderlem/porydaw)              | Gen 3 music editor / DAW | 'Made with Claude Code'                                                                                               |
| [poryaaaa](https://github.com/huderlem/poryaaaa)            | Gen 3 audio synthesizer  | 'Made with Claude Code'                                                                                               |
| [porytiles](https://github.com/grunt-lucas/porytiles)       | Tileset compiler         | 'legacy' has no AI, v2 [accepts AI contributions](https://github.com/grunt-lucas/porytiles/blob/develop/AI_POLICY.md) |
| [tilemap-studio](https://github.com/Rangi42/tilemap-studio) | Tilemap editor           | Predates modern AI models                                                                                             |

## Q: What is this?

**A**: This is a GitHub organization for and by any person with an interest in [romhacking](https://en.wikipedia.org/wiki/ROM_hacking).

Its purpose is to preserve the human effort that has gone into the various tools and projects used in romhacking,
maintain them for active development, and provide a standardized, opinionated approach to the craft.

## Q: Who are you?

**A**: [aarant](https://github.com/aarant), also known as **merrp**.

Long ago I pioneered a new ACE method in Pokémon Emerald and made an [Any% TAS](https://tasvideos.org/4278M).

Now I make romhacks of that game. I'm also a software engineer by day, for now.

You might know me for the following pokémon, day/night lighting, Gen 6 icons, or key item wheel features I've written for `pokeemerald` [here](https://github.com/aarant/pokeemerald).

## Q: Which projects will be maintained?

**A**: Repositories I intend to have here, in decreasing priority:

- [pokeemerald-expansion](https://github.com/rh-hideout/pokeemerald-expansion), the basis for a lot of hacks
- [pokeemerald](https://github.com/pret/pokeemerald), the base PRET decomp
- porymap & porytiles v1
- other PRET repos & tools

## Q: So no AI is allowed at all?

**A**: To the greatest extent possible, yes.

I believe that programming is a craft, that code can be art, that AI use cheapens the creative experience, inhibits learning, is socially and environmentally bad, etc.

The purpose of this repo is to maintain codebases of these tools without AI for those who wish to use them.

## Q: But how can you guarantee that?

**A**: In a sense, I can't. This project is inherently best-effort.

Writing [software without AI](https://github.com/thatshubham/no-ai) is very achievable, however.

The following should be true of code hosted here, **to the best of our knowledge**:

- AI models / LLMs did not generate any line of code / text
    - This includes code that was directly signed off on in a commit by AI
    - This includes code generated elsewhere and copy-pasted, then committed by a person
- AI models did not generate any graphics, audio, or any other kind of asset

The following should be true as well, but are impractical to enforce / verify:

- AI models / LLMs were not consulted at all during the development process
- All tools / software are AI-free / organic as well

The following rules are applied, in order, when determining whether to merge a change from the upstream:

1. Is the commit actually authored by an AI agent or LLM?
    - If yes, authorship will be reset with the nearest human author.
2. Is the change trivial / irreducible?
    - Some fixes might only have one or a few valid implementations
3. Was AI usage disclosed?
    - If yes, we will develop an alternative implementation and revert the existing one
4. Does the change show hallmarks / strong indications of being AI generated/assisted?
    - This is somewhat subjective, but many LLMs use unique language that might be a giveaway.

The result is a codebase that, for our best efforts, contains no or very minimal amounts of AI-generated code.

## Q: How can I contribute?

**A**: Check out the project list above.

You can help by adding to each project's PEOPLE.md file, to help identify human contributions.

I plan to maintain and remove as much AI-use from projects as I can, but I'm only one person.

You can also help by:

- Developing alternate implementations to AI PRs where applicable
- Finding the last known AI-free commit on various projects

## Contact

- **Discord**: [discord.gg/Mc94Zs8DXK](https://discord.gg/Mc94Zs8DXK)