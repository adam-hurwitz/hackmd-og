---
title: 📄 HackMD About and Features
tags: HackMD
description: About HackMD and features
image: https://pbs.twimg.com/profile_banners/3540691454/1535710532/1500x500
---

<h1 style="text-align: center;">📄 HackMD</h1>

<p style="text-align: center; font-style: italic">
    <a href="https://hackmd.io" target="_blank">hackmd.io</a>
</p>

# About

**Use** – Real-time collaboration powered by Markdown documentation.

**Guide** – [HackMD Tutorial Book](https://hackmd.io/c/tutorials/%2Fs%2Ftutorials)

#### Adoption

- Ethereum Foundation (EF)
    - Monthly EIPs Insights: [hackmd.io/@poojaranjan/EthereumImprovementProposalsInsight](https://hackmd.io/@poojaranjan/EthereumImprovementProposalsInsight)
    - AllCoreDevs bi-weekly updates: [hackmd.io/@timbeiko/acd](https://hackmd.io/@timbeiko/acd/)
- ConsenSys
    - What’s New in Eth2 series: [hackmd.io/@benjaminion](https://hackmd.io/@benjaminion)
- [Vitalik Buterin](https://notes.ethereum.org/@vbuterin)
- [How I use HackMD in Open Source projects](https://hackmd.io/@hackmd/customer-stories/https%3A%2F%2Fhackmd.io%2F%40hackmd%2Fk8s-story)

#### Team

- Size
    - Small, fast, and effective team of 8.
    - Growing up to 15 in 2023 mostly in developers.
- Location
    - Based mostly in Taiwan with a presence in San Francisco.

# Features

## About

- [Features](https://hackmd.io/c/tutorials/%2Fs%2Ffeatures)
- Enterprise
    - [hackmd.io/enterprise](https://hackmd.io/enterprise)
    - [hackmd.io/pricing](https://hackmd.io/pricing)

## Editor

- Create new page: [hackmd.io/new](https://hackmd.io/new)
- Near instant updates to the published version
- [Keyboard shortcuts for HackMD](https://hackmd.io/@docs/keyboard-shortcuts)
- Spell check: [Understanding Your Editor > 19. Spell Check](https://hackmd.io/@codimd/understanding-your-editor#19-Spell-Check) *by CodiMD*
- Test HackMD's version of Markdown vs. generic Markdown: View the markdown code in [Visual Studio Code (VS Code)](https://code.visualstudio.com/). 
- Customize themes and styles with Markdown and save to a template.
- [How to Use Template](https://hackmd.io/s/how-to-use-template)
    - [Boost Productivity with Templates](https://blog.hackmd.io/blog/2019/04/08/boost-productivity-with-templates)
- [VSCode integration](https://marketplace.visualstudio.com/items?itemName=HackMD.vscode-hackmd)
    - Use the same workflow while writing code.
    - Great for offline work.

## Share

- Make sure an email is set to receive share invites 
    - Set an account email if your sign-in is through a third-party, e.g. GitHub, Twitter, Google, and etc.
    - Menu (Bottom-left button with username) > *Settings* > *Email*
- Share edit access with specific user(s): *Share* button (Top-right) > *Note Permission* > *More (Comment, Invitee)* > *Invitee* > Add user's email > Select *Write* or *Admin*.
    - [Invite Others to a Private Note](https://hackmd.io/c/tutorials/%2Fs%2Finvite#Invite-Others-to-a-Private-Note)
    - [Features > Permissions](https://hackmd.io/s/features#Permissions)
- For Books you must share each Note with contributors.
- View shared notes: *My Workspace* ([hackmd.io/?nav=overview](https://hackmd.io/?nav=overview)) > *Collaborative Notes* ([hackmd.io/?nav=collab](https://hackmd.io/?nav=collab))
- [Live Host a Collaborative Session](https://hackmd.io/c/tutorials/%2Fs%2Flive-hosting)

## Publish

### Basics

#### Custom links

- HackMD readable custom URLs
    - Format: `hackmd.io/[@username]/[pagename]`
    - [How to Publish a Note with Permalink](https://hackmd.io/s/how-to-publish-note)
- Custom domains with enterprise: [hackmd.io/pricing](https://hackmd.io/pricing)
- Open a link in a new tab
    - [Universal method](https://docs.google.com/document/d/1ieB9vKFXWfLmRSZ3kJspgw9Y7wRWWeiCLEFnAlUEec8/edit#heading=h.1gcz6hoi61b3)
    - HackMD method: [External link](https://hackmd.io/s/how-to-create-book#External-Link)

#### Set metadata

- About
    - Sets the information that shows in the browser window/tab and link preview.
    - [Supported YAML metadata](https://hackmd.io/yaml-metadata)
- Attributes
    - Title
    - Description
    - Tags
        - Helps organize the page
        - [Tagging notes](https://hackmd.io/s/how-to-tag-notes)
    - Image
    - etc.

### Formats

#### Books

- Multi-page collections with a collapisible navigation menu
- URL format: `hackmd.io/[@username]/[bookname]-[pagename]`
- [How to Create a Book](https://hackmd.io/s/how-to-create-book)

#### Presentations

- [Make Presentation Slides with HackMD](https://hackmd.io/s/how-to-create-slide-deck)

#### Arweave

- [How to import from/export to Arweave](https://hackmd.io/@docs/export-import-arweave-en#How-to-import-fromexport-to-Arweave)

## Version control systems (VCS)

### HackMD named versions

- *See [How to Save Versions](https://hackmd.io/s/how-to-save)*
- Auto-saves every 10 minutes
- Can name auto-saved versions
- View to compare version's changes

### GitHub

#### About

- [Sync a Note with GitHub](https://hackmd.io/s/link-with-github)
- Encourage collaboration: [Add GitHub badge](https://hackmd.io/s/link-with-github#Add-GitHub-badge) to the HackMD note.

#### Enable

1. Set up GitHub permissions.

    a. Make sure your HackMD email has GitHub access.

    - GitHub account level email: Profile (Top-right button) > *Settings* > *Emails* > *Add email address*
    
        or
    
    - GitHub repository's permission settings: *Team admin*, *Team member*, or *Invitee admin*

2. Link GitHub to HackMD.
    
    a. HackMD menu (Bottom-left button with username) > *Settings* > *Integration* > Select *Link with GitHub*.
    
    b. *HackMD Hub by HackMD would like permission to: ...* > Select *Authorize HackMD Hub*    
    - Error for a user without access: `request to https://github.com/login/oauth/access_token failed, reason: read ECONNRESET`
    
    c. Manage GitHub [Hackmd Hub app](https://github.com/apps/hackmd-hub) access.

3. Enable GitHub in a Note.

    a. Note overflow menu (3 dots in the top-right) > *Versions and GitHub Sync* > *Pull from GitHub* or *Push to GitHub* > Select *Authorize more repos*
    
    b. *Install & Authorize HackMD Hub* > For enhanced security only authorize HackMD access for *Only select repositories* vs. *All repositories*. > Select *Install & Authorize*

#### Branches

- Sync with existing GitHub feature branches.
- Create and push new GitHub feature branch.

#### Push

- [Push to GitHub](https://hackmd.io/s/link-with-github#Push-to-GitHub)
- Each [HackMD named version](#HackMD-named-versions) will push as a Git commit.
    - HackMD auto-saved versions will not produce commits.
- Commit message
    - HackMD version name and description
    - Use a common commit message [style guide](https://docs.google.com/document/d/1W0pYNbK1a0teJDt96Jcli7RVEcaUpXpXoSKHbeX2VSs/edit#heading=h.xo83z7povj6l).

#### Pull

- [Pull from GitHub](https://hackmd.io/s/link-with-github#Pull-from-Github)
- Can choose the branch to pull from
- Can choose the portion of pulled branch revisions to merge into the HackMD note

### GitLab

- Available with Enterprise plan: [hackmd.io/pricing](https://hackmd.io/pricing#)
- Two-way sync push and pull: [Is GitLab two-way sync push and pull available? #321](https://github.com/hackmdio/hackmd-io-issues/issues/321)

## Security

- Data encryption and storage
    - [Transport Layer Security (TLS)](https://en.wikipedia.org/wiki/Transport_Layer_Security) encrypts the connection between the client and server.
    - [AES-256](https://en.wikipedia.org/wiki/Advanced_Encryption_Standard) encryption is used for data stored.
    - Data is mostly stored on Amazon Web Services (AWS).
    - *See [Is hackmd data encrypted in-transit and storage? #320](https://github.com/hackmdio/hackmd-io-issues/issues/320)*
- Back up data
    - Download all .md files: [Batch Download All Your Notes 📦](https://blog.hackmd.io/blog/2019/02/27/batch-download-all-your-notes)
    - [How to export to PDF](https://hackmd.io/@docs/export-to-pdf#)

## Self-hosting

#### Version control systems (VCS)
- Use continuous integration (CI)/continuous deployment (CD) with version control.
- *See [Features > version control systems (vcs)](#Version-control-systems-VCS)*

#### CodiMD
- [CodiMD - Realtime collaborative markdown notes on all platforms.](https://github.com/hackmdio/codimd#codimd)
- [CodiMD Documentation](https://hackmd.io/c/codimd-documentation/%2Fs%2Fcodimd-documentation)
- GitHub: [github.com/hackmdio/codimd](https://github.com/hackmdio/codimd#codimd)
- Questions
  - Can you migrate from HackMD to CodiMD? This would be useful for progressive decentralization.

## Developer API

- [HackMD API Book](https://hackmd.io/@docs/HackMD_API_Book/https%3A%2F%2Fhackmd.io%2F%40docs%2FHackMD_API_Book)
- [HackMD Developer Portal](https://hackmd.io/@hackmd-api/developer-portal/)

<p style="text-align: center; font-style: italic">This is not technical advice. Always read the official documentation and do your own research.</p>