# Development & Authoring Content

The instructions below are useful reminders for developers.


## System Preparation

To use this project, you'll need the following things installed on your machine.

1. [Jekyll](http://jekyllrb.com/docs/) - `$ gem install jekyll bundler`
2. [Jekyll-Gems](http://jekyllrb.com/docs/) - `$ bundle install`
3. [node.js](https://nodejs.org/en/download) - `$ brew install node`

### Installing Dependencies

This is not a `node.js` project but it does uses some `node.js` packages and utilities at development time. So you must first install the dependencies.

1. `bundle install`
2. `npm install`


## Usage

Since this is a Jekyll site, every command described in the [Jekyll documentation](https://jekyllrb.com/docs/) is available.

### Development

To start the development workflow, run:

```
bundle exec jekyll serve --livereload
```

For debugging missing content, enable verbose logging:
```
bundle exec jekyll build --trace --verbose JEKYLL_LOG_LEVEL=debug
```

### Production

To build the project, run:

```
bundle exec jekyll build
```

### GitHub Pages

Because this site is using the latest version of Jekyll, deployment to GitHub Pages must happen by way of a custom Workflow Action.

For more information see: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site#publishing-with-a-custom-github-actions-workflow


## Useful Utilities

https://www.svgrepo.com/ - Good source of open source SVG images.

https://compress-or-die.com/ - Great for compressing all sorts of images.
