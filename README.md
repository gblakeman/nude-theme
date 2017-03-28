Nude Theme
============

The Nude Theme is a stripped down Shopify theme, to be used as a “blank slate” starting point. It started as a fork of the [Skeleton Theme](https://github.com/Shopify/skeleton-theme) from Shopify. I tend to build stores for clients that are smaller in scope and found myself spending too much time un-doing a lot of the code in the _Skeleton Theme_ to get it to a point where I could start my own work. I also pre-build sites in [Jekyll](https://jekyllrb.com/) (because it’s easier to work with), so this base theme incorporates some things that make the transition easier.

**Features:**

- Some sensible theme settings that aren’t as easily over-ridden in the Shopify admin.
- A totally blank slate on CSS.
- An almost entirely blank slate on JS.
- Virtually no HTML. There is a limited structure meant to either be built upon, or reset entirely.
- The assets directory is basically empty except for some icons and social meta images that I use as placeholders.
- Some features have been removed since I pretty much never use them: _customer login_, and _blog comments_ are the two primary missing features.

Getting started
---------------------
1. [Download](https://github.com/gblakeman/nude-theme/archive/v1.0.3.zip) the latest version (1.0.3)
2. or clone the git repo: `git clone git@github.com:gblakeman/nude-theme.git`

Basic structure
---------------
```
├── assets
│   └── Javascript, CSS, and theme images
├── config
│   └── custom Theme Settings
├── layout
│   ├── theme.liquid
│   └── optional alternate layouts
├── snippets
│   └── optional custom code snippets
├── templates
│   ├── 404.liquid
│   ├── article.liquid
│   ├── blog.liquid
│   ├── cart.liquid
│   ├── collection.liquid
│   ├── index.liquid
│   ├── page.liquid
│   ├── product.liquid
│   └── search.liquid
│   └── list-collections.liquid
.ruby-version
   └── set your ruby version if you use a manager and the Theme gem
config.example.yml
   └── rename to ‘config.yml’ and configure your theme settings for the Theme gem
```

Additional resources
---------------------
- The [Skeleton Theme](https://github.com/Shopify/skeleton-theme) itself is an excellent reference point for some more complex undertakings and best practices. Be sure to check it out.
- Shopify [Theme Gem](https://github.com/Shopify/shopify_theme) - I include a config file for using this Gem.

Disclaimer
---------------------
I don’t actively support other users of this theme. Feel free to file Github Issues for actual bugs, or submit your own PRs, but don’t expect Shopify theme writing help from me.
