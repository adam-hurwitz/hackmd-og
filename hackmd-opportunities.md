---
title: 📄 HackMD Opportunities
tags: HackMD
description: HackMD opportunies
image: https://pbs.twimg.com/profile_banners/3540691454/1535710532/1500x500
---

Opportunities
===

## Security

- [ Native sign-in with multi-factor authentication (MFA) #319 ](https://github.com/hackmdio/hackmd-io-issues/issues/319) (P0)
    - Currently MFA is through third-parties, e.g. Twitter, GitHub, and etc.
- Backup notes based on folder architecture (P1)
    - Organize notes into folders in the app. 
    - *Settings* > *Download all notes* downloads the notes into local directories that match the app folder architecture.
    - This will make backing up a large amount of notes  user-friendly.

## Version control systems (VCS)

- Allow users with *Admin* and *Write* access to Push/Pull with GitHub a main Note they are not the owner of. (P1)
    - The Push and Pull options do not show in a shared user's Note.
    - Note overflow menu (3 dots in the top-right) > *Versions and GitHub Sync* > *Pull from GitHub* or *Push to GitHub*
    - Potential workaround: Create a public team: [Create and manage Team](https://hackmd.io/@docs/create-and-manage-team)
        - [Unable to create public team with a personal account #325](https://github.com/hackmdio/hackmd-io-issues/issues/325) (P0)
    - Potential workaround: Push a separate note.
        - User with access writes to the main Note in HackMD.
        - User with access creates a new Note, copies the entire main Note, and pushes changes to GitHub.
- GitLab integration for individual use (P1)
- [Radicle.xyz](https://radicle.xyz) integration – [Guide](https://docs.google.com/document/d/1_1h1C7IlcHJeRDy72E2ycb7br3lumpU631rN9CMpm8E/edit#heading=h.rprz9yqw2qqg) (P2)

## Editor

- More shortcut/hotkey commands to handle Markdown generation (P1)
- What you see is what you get (WYSIWYG) editor for Markdown (P1)
    - Great for beginner users to get started writing
- Spelling and grammar check
    - [LanguageTool](https://languagetool.org/) compatibility (Open-source) (P1)
    - Add new words to the spell checker dictionary (P1)
- Offline web editor and/or desktop app (P2)
- Import multiple .md files from local storage (P2)

## Other

- Mobile app for reading and editing (P2)
    - Mobile web app works well for viewing and editing.

# Research

## Enterprise

- [ ] Plan pricing

## UX
- [ ] Color, style, and theme with HTML and CSS
- [ ] Set HackMD book page's tab to a custom title.
    - Currently the book page tab title shows the link text from the book index page.
- [ ] How to build light/dark mode toggle
    - E.g. [Batch Download All Your Notes :package:](https://blog.hackmd.io/blog/2019/02/27/batch-download-all-your-notes)

## Publish

- [ ] Decentralize image hosting, e.g. Arweave and/or IPFS
- [ ] Automate saving directly to Arweave and/or IPFS: [Tweet](https://twitter.com/adamshurwitz/status/1613635255591702536) _by @adamshurwitz 2023-01-12_

<p style="text-align: center; font-style: italic">This is not technical advice. Always read the official documentation and do your own research.</p>