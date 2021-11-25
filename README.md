# Zilliqa Ecosystem

This repository is the data source for the Zilliqa Ecosystem page located at [zilliqa.com/ecosystem](https://zilliqa.com/ecosystem). Here, you can populate the latest projects being built or are active in the Zilliqa ecosystem.

# Contributing Guidelines

To add a project to our ecosystem, please structure your folder with the guidelines below and submit a pull request to our repository.

**❗️ Important!: Should your project already exist within this repo, please refrain from creating a new Markdown file in the projects directory. Instead please adapt the existing one in a new PR. This applies for changes to images, logos or description updates for your project.**

# Folder Structure

Every project will have their own named folder in the projects diretory cosisting of 2 files. A `project.md` file and a `logo_image_file`.
Name your folder with `kebab-case`.

### Structure

```
your-project-name
  - project.md
  - your-logo.png
```

### project.md

the project.md file holds the information that will be displayed and will categorise your project. Please read through the following instructions on how to structure your project.md file.

- ensure the filename is named exactly `project.md`. All lowercased with the extension .md
- create frontmatter tags by encasing tags in three dashes above and below

```
---
tags go here
---
```

- the file utilises the following tags:

```
---
(required) name: The name of the project
(required) date: The date of project addition
(required) description: The one line summary of the project and its integration to Zilliqa
(required) logo: all image files must by 100x100px
(required) categories: A comma separated list of categories describing the project
(required) status: The status of the project: [live | building]
(optional) twitter: URL to Twitter page
(optional) website: URL to the website
(optional) telegram: URL to Telegram channel
(optional) discord: URL to Discord invite
---
```

<details>
  <summary>Click for empty demo file layout</summary>
  
  
  ```
  ---
  name: 
  date: 
  description: 
  logo: 
  categories: 
  status: 
  twitter: 
  website: 
  telegram: 
  discord: 
  ---
  ```
</details>

- you can find the list of categories [here](#categories_listing)

### logo

- Ensure logo is in one of the following formats (png|jpg|svg)
- Logo has to be visible on a light gray background (#F5F5F5)
- Logo should have a 1:1 ratio. e.g. 300px x 300px.
- Don't include your project name in the logo. Include only the icon.

<a name="categories_listing"></a>

# Categories

### api

### app

### custody

#### dao

#### dapp

#### defi

#### dex

#### education

#### esport

#### exchange

#### explorer

#### fund

#### infra

#### gaming

#### meme_token

#### metaverse

#### mining

#### nft

#### on_ramp

#### opfi

#### oracle

#### payment

#### prediction

#### sdk

#### stablecoin

#### staking

#### tools

#### wallet

#### web3

**❗️ Important!: Please only use existing categories and watch out for typos!
If you think another category is needed, request the category in your PR.**

# Questions

Have any questions? Message on [Discord](https://discord.com/invite/XMRE9tt)
