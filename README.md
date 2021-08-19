# thejantar.com

https://thejantar.com

Band website for Jantar. Built using [`jekyll`](https://jekyllrb.com/docs/), deployed via [Netlify](https://app.netlify.com/sites/importer-tiger-77042/overview).

## Development

Install dependencies using [bundler](https://bundler.io/):

```shell
bundle install
```

Run the application locally:

```shell
bundle exec jekyll serve
```

To generate a static build:

```shell
bundle exec jekyll build
```

### Updating Shows

Add a new entry to `_data/shows.yml`.

### Adding New Releases

Add a new markdown file with the correct front matter block (see any existing release file) to the `_releases/` directory. Supporting images are stored in `assets/img/`.

## Deployment

Changes to `master` are automatically deployed via Netlify:
https://app.netlify.com/sites/importer-tiger-77042/deploys?filter=master
