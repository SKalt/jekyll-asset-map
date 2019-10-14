# Jekyll asset map \_include

> rails-webpacker's asset inclusion tags as jekyll \_includes

<!-- badges  -->

[![master](https://github.com/skalt/jekyll_asset_map/workflows/testing%20master/badge.svg)](https://github.com/skalt/jekyll_asset_map/actions?workflow=testing+master) [![v1](https://github.com/skalt/jekyll_asset_map/workflows/testing%20v1/badge.svg)](https://github.com/skalt/jekyll_asset_map/actions?workflow=testing+v1)

<!-- /badges -->

## When to use this

You should use this if all of the below are true:

[ ] you've got an existing Jekyll site written using liquid templates

[ ] you want to use some of the hot new tools from the JS ecosystem

[ ] but you don't want to completely rewrite your build process.

If you're going to process your HTML with some tool that runs in Node.js (webpack, rollup, parcel, gulp, or anything else), that tool likely has its own asset map implementation.

## Quickstart

Copy the [`_includes/asset_map` directory](./_includes/asset_map) into your own `_includes` directory.

# Documentation

You can see the docs all together on [GitHub pages](//skalt.github.io/jekyll_asset_map/) or see [`_data/docs.yml`](./_data/docs.yml), the [`_api` example collection](./_api), and working compiler configurations at [`examples`](./examples).

# Licensing

This package is free to use in open source under the terms of the [Parity Public License](./LICENSE).

Licenses for use in closed software are available via [licensezero.com](https://licensezero.com).

[![licensezero.com pricing](https://licensezero.com/projects/de9c209f-86b8-4a63-ae81-fb4ff3339d32/badge.svg)](https://licensezero.com/projects/de9c209f-86b8-4a63-ae81-fb4ff3339d32)
