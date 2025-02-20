---
title: Hugo blog awesome
github: https://github.com/hugo-sid/hugo-blog-awesome
demo: https://hugo-blog-awesome.netlify.app/
author: Sidharth R
date: 2023-02-15T00:00:00.000Z
ssg:
  - Hugo
cms:
  - No CMS
css:
  - SCSS
archetype:
  - Blog
  - Portfolio
description: Fast, minimal blog with dark mode support.
stale: false
disabled: true
disabled_reason: demo url not found
---

<h1 align=center> Awesome hugo blog | <a href="https://hugo-blog-awesome.netlify.app/" target="_blank" rel="nofollow">Demo</a></h1>

<h4 align=center>⚡ Fast | 📰 Clean UI | 🌙 Dark mode support | 📱 Responsive design </h4>

## Features

- Minimal design
- Responsive design
- Light and dark mode
- Syntax highlighting
- RSS feed
- No jQuery, Bootstrap
- 100/100 Google PageSpeed Insights score on all 4 metrics

## Screenshots

| Dark mode | Light mode |
| --- | --- |
| ![Dark mode](https://raw.githubusercontent.com/hugo-sid/hugo-blog-awesome/master/images/tn.png) | ![Light mode](https://raw.githubusercontent.com/hugo-sid/hugo-blog-awesome/master/images/light.png) |

Page speed score:

![Page speed score](https://raw.githubusercontent.com/hugo-sid/hugo-blog-awesome/master/images/pagespeed.png)

Google PageSpeed Insights [test link](https://pagespeed.web.dev/report?url=https%3A%2F%2Fhugo-blog-awesome.netlify.app%2F).

## Setup

Ensure that you have installed the Hugo extended version. This theme uses SCSS for styling, so you need the extended version of Hugo to compile the SCSS files.

To create a new Hugo site with this theme, run the following command:

    hugo new site myblog

Then, clone this repository into the `themes` directory of your new site:

    cd myblog
    git clone https://github.com/hugo-sid/hugo-blog-awesome.git themes/hugo-blog-awesome

To preview the thmeme with example content, run the following command from the `exampleSite` directory:

    hugo server --themesDir ../..

## Usage

To use this theme, set the `theme` variable in your site's `config.toml` to `hugo-blog-awesome`:

    theme = "hugo-blog-awesome"

## Configuration

You can have a look at the `config.toml` file in the `exampleSite` directory for an example configuration.
I recommend you to copy the `config.toml` file from the `exampleSite` directory to the root directory of your Hugo site. Then, you can edit the `config.toml` file to suit your needs.

## Content

### Posts

To create a new post, run the following command:

    hugo new posts/my-first-post.md

Then, edit the `my-first-post.md` file to suit your needs.

## Contributing

If you find any bugs or have any suggestions, feel free to open an issue or a pull request.

## License

This theme is released under the MIT license. For more information read the [License](https://github.com/hugo-sid/hugo-blog-awesome/LICENSE.md).
