#TamagoFeedRenderBundle
Simple bundle to render RSS news feeds within an app

## Installation

Add the package to your composer.json file

```
"Tamago/FeedRenderBundle": "dev-master",
```
##Configuration

Edit config.yml

```
parameters:
    tamago_feed_render.url: 'http://rss.indeed.com/rss?q=RSS'
    tamago_feed_render.MaxPerPage: 10
```

## License

This bundle is under the MIT license.