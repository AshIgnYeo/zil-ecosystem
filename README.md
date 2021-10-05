# Zilliqa Ecosystem

This repository is the data source for the Zilliqa Ecosystem page located at [zilliqa.com/ecosystem](https://zilliqa.com/ecosystem). Here, you can populate the latest projects being built or are active on the Zilliqa ecosystem.

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
(required) twitter: URL to Twitter page 
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
- Logo has to be visible on a solid black background


<a name="categories_listing"></a>
# Categories

### api
> How to classify as api

### app
> How to classify as app

### custody
> How to classify as custody

#### dao
> How to classify as dao

#### dapp
> How to classify as dapp

#### defi
> How to classify as defi

#### dex
> How to classify as dex

#### education
> How to classify as education

#### esport
> How to classify as esport

#### exchange
> How to classify as exchange

#### explorer
> How to classify as explorer

#### fund
> How to classify as fund

#### infra
> How to classify as infra

#### gaming
> How to classify as gaming

#### meme_token
> How to classify as meme token

#### metaverse
> How to classify as metaverse

#### mining
> How to classify as mining

#### nft
> How to classify as nft

#### opfi
> How to classify as opfi

#### oracle
> How to classify as oracle

#### payment
> How to classify as payment

#### prediction
> How to classify as prediction

#### sdk
> How to classify as sdk

#### stablecoin
> How to classify as stablecoin

#### staking
> How to classify as staking

#### tools
> How to classify as tools

#### wallet
> How to classify as wallet

#### web3
> How to classify as web3


**❗️ Important!: Please only use existing categories and watch out for typos!
If you think another category is needed, request the category in your PR.**

# Questions
Have any questions? Email X or message on Discord
