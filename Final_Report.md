# Final Report For Google Summer Of Code 2019

## GatsbyJs Preview For Plone CMS
Gatsby is a blazing fast static site generator for React. `gatsby-source plugin` is a Gatsby plugin that pulls the whole content tree from the `plone.restapi` and makes it available for querying via GraphQL in a hierarchical data structure, handling all native content types including images and files.Now `gatsby-source-plugin` has a new feature by which user can see the instant update of site whenever they make changes to the Plone CMS. This feature in Gatsby community called as **GatsbyJs Preview**. I implemented this feature in this GSOC period. `gatsby-source-plugin` support all feature of GatsbyJs Preview i.e **Create mode**, **modified mode** and **Delete mode**. If you make any these event in Plone CMS you can see instant update into your hosted site.

`gatsby-source-plugin` has all the documentation we needed to get started with your wonderful project. We also have `gatsby-starter-plone` and `gatsby-theme-plone` . currently `gatsby-theme-plone` is in alpha phase.

## Get the code

The plugin to pull data from a Plone site and respond to all the websocket event i.e `created`, `modified` and `delete` to a Gatsby project , **gatsby-source-plone**: https://github.com/collective/gatsby-source-plone.

## Live Demos
Documentation for gatsby-source-plone (Gatsby site generated from mock Plone site): https://collective.github.io/gatsby-source-plone/

