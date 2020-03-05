---
title: 16 Must-Have eCommerce App Features
date: 2018-08-09T17:49:28.000+00:00
excerpt: 7 MIN READ More and more retailers are seeing the benefits of improving their
  mobile offering, whether that is through taking the initial steps of getting a mobile-responsive
  site or diving into the exciting world of app commerce. The impact of mobile shoppers
  habits’...

---
# 16 Must-Have eCommerce App Features

Let's check out how we can automatically deploy our VuePress sites and manage the content from within Forestry.

### Preparing our VuePress site

We need to create a `package.json` file in the root of our project, this will include the `build` and `dev` command and list VuePress as a dependency.

    {
      "name": "portfolio-vuepress",
      "scripts": {
        "site:build": "vuepress build portfolio",
        "site:develop": "vuepress dev portfolio"
      },
      "author": "Nichlas W. Andersen",
      "license": "MIT",
      "dependencies": {
        "vuepress": "^1.2.0"
      }
    }

Now, push it up to your remote git repository.

### Deploying with Netlify

1. Create a new site in Netlify and import your repository.
2. Set the build command to: `npm run site:build`
3. Set the publish directory to `portfolio/.vuepress/dist`

### Manage your content with Forestry

Well, not much to do here really, this theme is pre-configured and works out of the box with Forestry. Create an account at [Forestry](https://forestry.io "Forestry") and import your repository.

That's it, that's all. Enjoy your new site!