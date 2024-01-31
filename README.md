# Quartz v4

> “[One] who works with the door open gets all kinds of interruptions, but [they] also occasionally gets clues as to what the world is and what might be important.” — Richard Hamming

Quartz is a set of tools that helps you publish your [digital garden](https://jzhao.xyz/posts/networked-thought) and notes as a website for free.
Quartz v4 features a from-the-ground rewrite focusing on end-user extensibility and ease-of-use.

🔗 Read the documentation and get started: https://quartz.jzhao.xyz/

[Join the Discord Community](https://discord.gg/cRFFHYye7t)

## Sponsors

<p align="center">
  <a href="https://github.com/sponsors/jackyzha0">
    <img src="https://cdn.jsdelivr.net/gh/jackyzha0/jackyzha0/sponsorkit/sponsors.svg" />
  </a>
</p>

# My Public Second Brain.

See on [suzzlo.github.io](https://suzzlo.github.io).

This is a fork of the [Quartz](https://github.com/jackyzha0/quartz) repo. I added some additional features such as:

- tagging with #publish will automatically copy the note from my private second brain in [Obsidian](https://obsidian.md/) to this public second brain. You find the python scrips in [utils](https://github.com/sspaeti/second-brain-public/blob/hugo/utils).
- It also converts the first header (`# my title`) into the frontmatter (metadata of each note) and removes it so that Quartz needs it.
