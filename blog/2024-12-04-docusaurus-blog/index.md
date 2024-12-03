---
slug: docusaurus-blog
title: How to create your own blog with Docusaurus?
authors: ricardo
tags: [technology]
draft: true
---

# How to Install Docusaurus and Create Your Own Personal Blog

In this guide, we'll walk you through the process of installing Docusaurus and setting up your own personal blog. Docusaurus is a static site generator that makes it easy to build and maintain open source project websites. Follow these steps to get your blog up and running quickly.

<!-- truncate -->

## Step 1: Prerequisites

Before you begin, make sure you have the following installed on your computer:
- Node.js (version 14 or above)
- npm (Node Package Manager)


You can download and install Node.js and npm from [nodejs.org](
https://nodejs.org/).


## Step 2: Create a New Docusaurus Site

Open your terminal and run the following command to create a new Docusaurus site:


`npx create-docusaurus@latest my-blog classic`


This command will create a new directory called `my-blog` with a Docusaurus site using the "classic" template.

## Step 3: Navigate to Your Site Directory

Change into the newly created directory:


`cd my-blog`


## Step 4: Start the Development Server

Run the following command to start the development server:


`npm run start`


This will start a local development server and open your new Docusaurus site in your default web browser. You should see the default Docusaurus homepage.

## Step 5: Create Your First Blog Post

To create a new blog post, navigate to the `blog` directory within your project:


cd blog


Create a new Markdown file for your blog post, for example, `2023-10-01-my-first-blog-post.md`:


`touch 2023-10-01-my-first-blog-post.md`


Open the file in your favorite text editor and add the following content:

```
---
title: My First Blog Post
author: Your Name
author_title: Your Title
author_url: Your URL
author_image_url: Your Image URL
tags: [first post, docusaurus]
---
```

Welcome to my first blog post using Docusaurus!


Save the file and navigate back to the root of your project directory:


`cd ..`


## Step 6: Customize Your Blog

You can customize the look and feel of your blog by editing the configuration file `docusaurus.config.js` and the theme file `src/css/custom.css`.

For example, to change the site title and tagline, open `docusaurus.config.js` and update the following lines:

```js
module.exports = {
  title: 'My Personal Blog',
  tagline: 'A blog about my journey with Docusaurus',
  // other configuration options...
};
```


## Step 7: Build and Deploy Your Site to GitHub Pages

TBD

## Conclusion

Congratulations! You have successfully installed Docusaurus and created your own personal blog. You can now start writing and sharing your blog posts with the world. Happy blogging!