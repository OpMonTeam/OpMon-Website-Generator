This repository contains the necessary files to generate the OpMon website.

# How to generate OpMon website

The Opmon website is generated using [Jekyll](https://jekyllrb.com/).

You'll need to have Jekyll set up on your machine. Follow the Jekyll
documentation available [here](https://jekyllrb.com/docs/).

Once this is done, run the following command from the root of the project:

```
bundle install
```

This will install some necessary Ruby gems, such as `jekyll-theme-clean-blog`
which is the Jekyll theme used by the website.

Then, run the following command to build the website:

```
bundle exec jekyll build
```

The website files will be generated in the `_site` directory.
