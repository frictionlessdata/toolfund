This site is built with [Lektor](https://www.getlektor.com/).

It has a bunch of [dependencies](package.json), so do `npm install` and then `npm run build`.

`grunt` will watch for changes to your [SCSS files](assets/scss), and also [icons](assets/icons) (see [svgstore](https://github.com/FWeinb/grunt-svgstore)).

This repo is configured to automatically deploy to Amazon S3 whenever a push is made to the **master** branch.
