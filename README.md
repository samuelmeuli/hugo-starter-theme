# Hugo Starter Theme

This is a very simple boilerplate for a [Hugo](https://gohugo.io) theme. It contains useful blocks and partials for the most important page elements.

The theme contains no styles. It is meant to be used as the basis of a custom theme.

## Example

An example site building on this theme can be found [here](https://github.com/samuelmeuli/samuelmeuli.com).

## Usage

Make sure you have Hugo installed.

1. `hugo new site my-site`
2. `cd my-site`
3. `git init`
4. `git submodule add https://github.com/samuelmeuli/hugo-starter-theme themes/hugo-starter-theme`
5. `echo 'theme = hugo-starter-theme' >> config.toml`

## Configuration

The following parameters are supported by default:

- **`githubUrl`**: URL to the site's GitHub repository. If specified, blog posts will contain an "Edit" link
- **`rssUrl`**: URL to the blog's RSS feed. If specified, blog posts will contain a link to the feed
