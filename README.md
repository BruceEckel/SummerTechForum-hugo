# The Summer Tech Forum (Hugo Source)

Hugo Static Site for the [Summer Tech Forum Conference](https://www.SummerTechForum.com).

The theme supports the site on phones as well as computers and tablets.

Everything is in markdown so it's easy to add/edit content. If you look at the
`content` subdirectory and the `config.toml` file you'll see how straightforward it is to add new pages.

## Requirements

- Git
- [Hugo](https://gohugo.io/getting-started/installing/) `v0.59.0`
- Python (only for `local.bat`)

## Setup

```bash
git clone git@github.com:BruceEckel/summertechforum-hugo.git
# If you want to refresh the theme from its repository:
cd summertechforum-hugo
rm -rf themes
git clone git@github.com:BruceEckel/hugo-material-banner themes/hugo-material-banner
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

Deploys automatically by Netlify whenever the Github repo is updated.

`local.bat` is a convenience for starting a local server and opening a local web window.
