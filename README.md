# CoderDojo-Porirua.github.io

This is the website for Porirua CoderDojo. It's built on Jekyll.

# Layout
The overall pages layout is defined in the _layout folder.

# Styling
The styling can be added to/changed using the css file in the assets/css folder. This is a SCSS file.

# Navigation
The navigation is controlled by the _data/nav.yml file

# Pages
These can be added to the main repository, and will be reflected into the website with the same path as the files and folders used.

Pages can be authored in either html (in a .html file), or markdown (specifically [kramdown](https://kramdown.gettalong.org/quickref.html), in a .md file)

# To run locally

First ensure you have Ruby installed. Then run:

```
gem install bundler
bundle install
bundle exec jekyll serve
```

Finally, browse to:

[http://localhost:4000/](http://localhost:4000/)
