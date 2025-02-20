# Personal Blog

This is my personal blog built with [Hugo](https://gohugo.io/) and the [PaperMod](https://github.com/adityatelange/hugo-PaperMod) theme. The blog is deployed using GitHub Pages

## Features

- Static site generated with Hugo
- Uses the elegant and customizable PaperMod theme
- Supports Markdown for easy content writing
- Fast and lightweight

## Installation

### Prerequisites

- Install [Hugo](https://gohugo.io/getting-started/installing/)
- Install [Git](https://git-scm.com/)

### Clone the Repository

```bash
git clone https://github.com/edhlii/blog-site.git
cd blog-site
```

### Install the Theme

```bash
git submodule update --init --recursive
```

## Running Locally

```bash
hugo server -D
```

## Adding New Posts

To create a new blog post, run:

```bash
hugo new posts/my-new-post.md
```

Edit the generated Markdown file in `content/posts/`.

## Building the Site

```bash
hugo -D
```

The generated static files will be in the `public/` directory.

## Customization

You can customize the theme by modifying `config.yml`. See the [PaperMod documentation](https://github.com/adityatelange/hugo-PaperMod/wiki) for more details.
