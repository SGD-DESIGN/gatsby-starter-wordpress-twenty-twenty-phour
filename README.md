<!-- AUTO-GENERATED-CONTENT:START (STARTER) -->
<p align="center">
  <a href="https://www.gatsbyjs.com">
    <img alt="Gatsby" src="https://www.gatsbyjs.com/Gatsby-Monogram.svg" width="60" />
  </a>
</p>
<h1 align="center">
  Gatsby WordPress blog starter -- Modified *
</h1>

Kick off your wordpress gatsby project with this blog boilerplate. This starter ships with the main Gatsby Wordpress configuration files you might need to get up and running blazing fast with the blazing fast app generator for React.

_Have another more specific idea? You may want to check out our vibrant collection of [official and community-created starters](https://www.gatsbyjs.com/docs/gatsby-starters/)._

## 🚀 Quick start

To get your project started or to just try it out, you can **follow the [Gatsby Wordpress Quickstart](https://github.com/gatsbyjs/gatsby-source-wordpress-experimental/blob/master/docs/getting-started.md#quick-start)** instructions

## 🧐 What's inside?

A quick look at the top-level files and directories you'll see in a Gatsby project.

    .
    ├── node_modules
    ├── src
    ├── .gitignore
    ├── .prettierrc
    ├── gatsby-browser.js
    ├── gatsby-config.js
    ├── gatsby-node.js
    ├── gatsby-ssr.js
    ├── LICENSE
    ├── package-lock.json
    ├── package.json
    └── README.md

1.  **`/node_modules`**: This directory contains all of the modules of code that your project depends on (npm packages) are automatically installed.

2.  **`/src`**: This directory will contain all of the code related to what you will see on the front-end of your site (what you see in the browser) such as your site header or a page template. `src` is a convention for “source code”.

3.  **`.gitignore`**: This file tells git which files it should not track / not maintain a version history for.

4.  **`.prettierrc`**: This is a configuration file for [Prettier](https://prettier.io/). Prettier is a tool to help keep the formatting of your code consistent.

5.  **`gatsby-browser.js`**: This file is where Gatsby expects to find any usage of the [Gatsby browser APIs](https://www.gatsbyjs.com/docs/browser-apis/) (if any). These allow customization/extension of default Gatsby settings affecting the browser.

6.  **`gatsby-config.js`**: This is the main configuration file for a Gatsby site. This is where you can specify information about your site (metadata) like the site title and description, which Gatsby plugins you’d like to include, etc. (Check out the [config docs](https://www.gatsbyjs.com/docs/gatsby-config/) for more detail). **\*Wordpress Users:** This is where you configure your wordpress URL, and provide other plugin settings.\*

7.  **`gatsby-node.js`**: This file is where Gatsby expects to find any usage of the [Gatsby Node APIs](https://www.gatsbyjs.com/docs/node-apis/) (if any). These allow customization/extension of default Gatsby settings affecting pieces of the site build process. **\*Wordpress Users:** This is where you customize how gatsby consumes your wordpress graphql schema, and generates your gatsby content schema. The starter will handle post and blog types.\*

8.  **`gatsby-ssr.js`**: This file is where Gatsby expects to find any usage of the [Gatsby server-side rendering APIs](https://www.gatsbyjs.com/docs/ssr-apis/) (if any). These allow customization of default Gatsby settings affecting server-side rendering.

9.  **`LICENSE`**: This Gatsby starter is licensed under the 0BSD license. This means that you can see this file as a placeholder and replace it with your own license.

10. **`package-lock.json`** (See `package.json` below, first). This is an automatically generated file based on the exact versions of your npm dependencies that were installed for your project. **(You won’t change this file directly).**

11. **`package.json`**: A manifest file for Node.js projects, which includes things like metadata (the project’s name, author, etc). This manifest is how npm knows which packages to install for your project.

12. **`README.md`**: A text file containing useful reference information about your project.

## 🎓 Learning Gatsby

Looking for more guidance? Full documentation for Gatsby lives [on the website](https://www.gatsbyjs.com/). Here are some places to start:

- **For most developers, we recommend starting with our [in-depth tutorial for creating a site with Gatsby](https://www.gatsbyjs.com/tutorial/).** It starts with zero assumptions about your level of ability and walks through every step of the process.

- **To dive straight into code samples, head [to our documentation](https://www.gatsbyjs.com/docs/).** In particular, check out the _Guides_, _API Reference_, and _Advanced Tutorials_ sections in the sidebar.

## 🛠️ \*Modified Version

Gatsby WP Blog Starter merged with Gatsby Starter WP Twenty Twenty Starter ( A port of the WordPress Twenty Twenty theme to Gatsby. )

#### WordPress Setup

1. Make sure to install the two required WP plugins [wp-gatsby](https://github.com/gatsbyjs/wp-gatsby) and [wp-graphql](https://github.com/wp-graphql/wp-graphql)
2. Best you install and activate the default WordPress Twenty Twenty theme
3. Make sure you have Menus with the following slugs:
   - `primary` - Thats the top menu
   - `extended` - That is the menu that opens on the right side as drawer
   - `social-links-menu` - For the Social menu in the footer and in the expanded drawer
     - For the social Icons you need to adjust `SocialMenu.js`. There is a `SocialIcon` function that parses svgs depending on the Link label
4. Rename `.env.example` file to `.env` and edit it with your domain variables. Make sure to fill all variables properly.
   - `WPGRAPHQL_URL` - Your GraphQL endpoint
   - `SITE_URL` - Your frontend domain (without ending slash) to stitch together SEO relevant image urls.

#### Limitations

- Comments are not implemented yet.
- The monthly archive pages are not implemented.
- Tags are not implemented (only Categories).
- Surely there is more. Feel free to suggest things as issues.

#### Links

- [gatsby-source-wordpress (v5)](https://github.com/gatsbyjs/gatsby/blob/master/packages/gatsby-source-wordpress/README.md)
- [WPGatsby - WordPress Plugin](https://github.com/gatsbyjs/wp-gatsby)
- [Twenty Twenty - WordPress Theme](https://de.wordpress.org/themes/twentytwenty/)
- [Gatsby WordPress blog starter](https://github.com/gatsbyjs/gatsby-starter-wordpress-blog)
- [Gatsby Starter - WordPress Twenty Twenty](https://github.com/henrikwirth/gatsby-starter-wordpress-twenty-twenty)

#### Acknowledgements

- [NeverNull GmbH](https://nevernull.io) - The team I'm working with. Checkout what we are building here: [mobileui.dev](https://mobileui.dev)
- [@TylerBarnes](https://github.com/TylerBarnes) - Head developer of gatsby-source-wordpress@v4
- [@JasonBahl](https://github.com/jasonbahl) - Head developer of WPGraphQL
- [@LouieChristie](https://github.com/louiechristie) - Open source contributor

## 💫 Deploy

Deploy this starter with one click on [Gatsby Cloud](https://www.gatsbyjs.com/cloud/):

[<img src="https://www.gatsbyjs.com/deploynow.svg" alt="Deploy to Gatsby Cloud">](https://www.gatsbyjs.com/dashboard/deploynow?url=https://github.com/gatsbyjs/gatsby-starter-wordpress-blog)

<!-- AUTO-GENERATED-CONTENT:END -->
