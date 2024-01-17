---
title: Simple GitHub Pages Blog
---

# Creating a Simple Blog Website with GitHub Pages, Jekyll, and Bootstrap

![GitHub Pages](placeholder_image_url)
![Jekyll](placeholder_image_url)
![Bootstrap](placeholder_image_url)

Introduction

In this tutorial, we will walk through the process of creating a simple blog website using GitHub Pages, Jekyll, and Bootstrap. GitHub Pages is a free hosting service provided by GitHub, which allows you to host static websites directly from your GitHub repositories. Jekyll is a static site generator that simplifies the process of building and maintaining a website. Bootstrap is a popular CSS framework that provides a set of pre-designed components and styles.

Prerequisites

Before we get started, make sure you have the following:

-   A GitHub account
-   Basic knowledge of HTML, CSS, and Markdown

Step 1: Setting up GitHub Pages

The first step is to create a new repository on GitHub and enable GitHub Pages for it. Follow these steps:

1. Create a new repository on GitHub.
2. Go to the repository's settings.
3. Scroll down to the GitHub Pages section.
4. Select the branch you want to use for GitHub Pages (e.g., `main` or `master`).
5. Choose a theme or leave it as the default.

Step 2: Creating the Jekyll Site

GitHub Pages natively supports Jekyll, so you don't need to install it locally. Follow these steps:

1. Go back to your repository's main page.
2. Click on the "Add file" button and select "Create new file".
3. Name the file `_config.yml`.
4. In the file content, add the following lines:
    ```yaml
    remote_theme: "jekyll/minima"
    plugins:
        - jekyll-feed
    ```
5. Commit the file by providing a commit message and clicking on the "Commit new file" button.

Step 3: Customizing the Website

At this point, you have a basic Jekyll site set up. Now, let's customize it using Bootstrap. Follow these steps:

1. Download Bootstrap from the official website.
2. Extract the downloaded file and copy the CSS and JS files into your Jekyll site's `assets` directory.
3. Open the `_layouts/default.html` file and add the Bootstrap CSS and JS files.

Step 4: Creating Blog Posts

To create a new blog post, follow these steps:

1. Go back to your repository's main page.
2. Click on the "Add file" button and select "Create new file".
3. Name the file using the following format: `YYYY-MM-DD-title.md`.
4. In the file content, add the necessary front matter and write your blog post content using Markdown syntax. Here's an example:

    ```markdown
    ---
    layout: post
    title: "My First Blog Post"
    date: 2024-01-19
    ---

    This is my first blog post using GitHub Pages, Jekyll, and Bootstrap. It's so easy to get started!
    ```

5. Commit the file by providing a commit message and clicking on the "Commit new file" button.

Step 5: Deploying the Website

To deploy your website to GitHub Pages, follow these steps:

1. Go back to your repository's main page.
2. Click on the "Settings" tab.
3. Scroll down to the GitHub Pages section.
4. Select the branch you want to use for GitHub Pages (e.g., `main` or `master`).
5. Wait a few moments for GitHub Pages to build and deploy your site.
6. Visit `https://<your-username>.github.io/<repository-name>` to see your live website.

Conclusion

Congratulations! You have successfully created a simple blog website using GitHub Pages, Jekyll, and Bootstrap. With this setup, you can easily write and publish blog posts without the need for a complex content management system.

![Final Website](placeholder_image_url)

I hope you found this tutorial helpful. Happy blogging!
