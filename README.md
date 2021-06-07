# The Summer Tech Forum Hugo Static Site Source

Hugo Static Site for the [Summer Tech Forum Conference](https://www.SummerTechForum.com).

Because of the theme, the site automatically works well on phones as well as
computers and tablets.

Everything is in markdown so it's easy to add/edit content. If you look at the
"content" subdirectory you'll see how straightforward it is to add new pages.

## Requirements

- Git
- [Hugo](https://gohugo.io/getting-started/installing/) `v0.59.0`
- Python (only for deploy)

## Setup

```bash
git clone git@github.com:BruceEckel/summertechforum-hugo.git
cd summertechforum-hugo
git clone git@github.com:pavelbinar/hugo-material-banner.git themes/hugo-material-banner
```

## Development

```bash
hugo server
```

## Build

```bash
hugo server
```

The build output will be in the `public` folder.

# Deploy

```bash
python deploy.py
```
