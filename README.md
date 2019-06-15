# GeneSys - Documento de Referências

Bem vindo ao documento de Referências para o GeneSys RPG.

![teste](http://grifoeditorial.com/wp-content/uploads/2015/12/GeneSys-Fast-Play-Large.jpg)


## Contexto

GeneSys é um sistema de [RPG](https://genesys-srd.thluiz.now.sh/1.introducao#o-que---rpg) Universal, ou seja, se propõe a ser genérico para que se possa desenvolver aventuras em qualquer cenário imaginável mantendo a simplicidade sob controle dos jogadores.

O nosso [Fast Play](http://grifoeditorial.com/wp-content/uploads/2015/12/GeneSys-Fast-Play-PT-BR-Index.pdf) porém desajávamos algumas atualizações após a publicação do  TODO:  [BuShin](http://link-para-bushin)  para agilizar a publicação de novos cenários.

Além disso desejamos um acesso mais imediato




## 🔥 Features
- Write using Markdown / [MDX](https://github.com/mdx-js/mdx)
- GitBook style theme
- Syntax Highlighting using Prism [`Bonus`: Code diff highlighting]
- Google Analytics Integration
- Automatically generated sidebar navigation, table of contents, previous/next
- Edit on Github
- Fully customisable
- Rich embeds and live code editor using MDX
- Easy deployment: Deploy on Netlify / Now.sh / Docker

## 🔗 Live Demo

Here's a [live demo](https://learn.hasura.io/graphql/react)

## 🚀 Quickstart

Get started by running the following commands:

```
$ git clone git@github.com:hasura/gatsby-gitbook-starter.git
$ npm install
$ npm start
```

Visit `http://localhost:8000/` to view the app.

## 🔧 Configure

Write markdown files in `content` folder.

Open `config.js` for templating variables. Broadly configuration is available for `gatsby`, `header`, `sidebar` and `siteMetadata`.

- `gatsby` config for global configuration like
    - `pathPrefix` - Gatsby Path Prefix
    - `siteUrl` - Gatsby Site URL
    - `gaTrackingId` - Google Analytics Tracking ID

- `header` config for site header configuration like
    - `title` - The title that appears on the top left
    - `githubUrl` - The Github URL for the docs website
    - `helpUrl` - Help URL for pointing to resources
    - `tweetText` - Tweet text
    - `links` - Links on the top right

- `sidebar` config for navigation links configuration
    - `forcedNavOrder` for left sidebar navigation order. It should be in the format "/<filename>"
    - `links` - Links on the bottom left of the sidebar

- `siteMetadata` config for website related configuration
    - `title` - Title of the website
    - `description` - Description of the website
    - `ogImage` - Social Media share og:image tag
    - `docsLocation` - The Github URL for Edit on Github

- For sub nesting in left sidebar, create a folder with the same name as the top level `.md` filename and the sub navigation is auto-generated. Currently it supports only one level of nesting. The sub navigation is alphabetically ordered.

## Live Code Editor

To render react components for live editing, add the `react-live=true` to the code section. For example:

```javascript react-live=true
<button>Edit my text</button>
```

In the above code, just add `javascript react-live=true` after the triple quote ``` to start rendering react components that can be edited by users.

## 🤖 SEO friendly

This is a static site and comes with all the SEO benefits. Configure meta tags like title and description for each markdown file using MDX Frontmatter

```markdown
---
title: "Title of the page"
metaTitle: "Meta Title Tag for this page"
metaDescription: "Meta Description Tag for this page"
---
```

Canonical URLs are generated automatically.

## ☁️ Deploy

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/hasura/gatsby-gitbook-starter)
