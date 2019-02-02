<!-- AUTO-GENERATED-CONTENT:START (STARTER) -->
<p align="center">
  <a href="https://blissful-euler-14b462.netlify.com/">
    <img alt="Gatsby" src="https://www.gatsbyjs.org/monogram.svg" width="60" />
  </a>
</p>
<h1 align="center">
  Gatsby Starter Wiki Theme
</h1>

A gatsby wiki starter / theme for markdown driven documentation sites using [Gatsby](https://github.com/gatsbyjs/gatsby/).

## Motivation

I wanted a gatsby driven documentation platform that is dead-simple to contribute to (provided that you know how to use git and markdown 😬).

This project is primarily developer focused but it is open to contributions and suggestions from anyone who wants to use a gatsby-powered documentation site!

## How is this different from a normal gatsby starter?

This project is a [Gatsby Starter](https://www.gatsbyjs.org/starters/?v=2) that implements [gatsby theming](https://www.gatsbyjs.org/blog/2018-11-11-introducing-gatsby-themes/).

This means that all of the core functionality of this starter can be _updated_ via npm whenever it gains new features!

Gatsby starters typically hold all of the feature code, which means that when you create a Gatsby site from a starter you diverge from the master branch. This makes it really hard to get the new features of a starter when they are updated without doing complicated merges.

## Demo

[Netlify Hosted Demo](https://blissful-euler-14b462.netlify.com/)

## Features

- Gatsby V2 Support
- Main features implemented via Gatsby Theming ([What does this mean?](https://www.gatsbyjs.org/blog/2018-11-11-introducing-gatsby-themes/))
- Gatsby blog starter structure
  - With modifications, detailed below
- Markdown post support
- Hierarchical post navigation
  - Automatically generated from the filesystem (your posts!)
  - Displayed via [Kendo UI TreeView](https://www.telerik.com/kendo-react-ui/components/treeview/)

## Todo (in no particular order)

[See sister theme repository (all of the Gatsby code lives here!)](https://github.com/cephalization/gatsby-wiki)

## Getting Started

```
# Install gatsby-cli
npm install --global gatsby-cli

# Create a new Gatsby site from this starter
# (Change `my-new-wiki` to whatever you want your wiki to be called)
gatsby new my-new-wiki https://github.com/cephalization/gatsby-starter-wiki-theme

# Run the wiki locally
npm run start
```

You can now host this template via your favorite hosting service (or yourself!), push to your own git<hub|lab|etc> repo, and customize to your heart's content!

## Adding new articles

1. Create md file in `wiki/<topic>/<post>.md`

   - Keep in mind, whatever directory structure you make here will be the link of the post!

2. Setup frontmatter (special markdown header) at the top of the file like so:

```
---
title: 'My First Post!'
path: '/<topic>/<post>.md'
---

```

3. Add post content 👌

```
---
title: 'My First Post!'
path: '/<topic>/<post>.md'
---

# How to add posts
First you must read the README...
```

4. Restart your server

## Customizing Gatsby Theme

More detailed instructions will come later, for now, refer to [this](https://github.com/ChristopherBiscardi/gatsby-theme-examples)
