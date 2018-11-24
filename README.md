# GitHub pages for brianesamson.com

This is the code repository for my [personal website](https://brianesamson.com/) that is powered by [Jekyll](https://jekyllrb.com/). 

## Dependencies

Here are the dependencies for this website. You can also check the `Gemfile` for more
information: 

- Ruby==2.5.3
- gem==2.7.6
- jekyll=3.5.2
- minima==2.5.0
- html-proofer
- jekyll-sitemap
- jekyll-feed==0.6
- jekyll-seo-tag

## Set-up

I'm working on a macOS and here are some quick instructions to get things started.

Install the bundler and jekyll gems in your system:

```
$ gem install bundler jekyll
```

Then, install the dependencies included in your `Gemfile` and `_config.yml`, and call `jekyll serve`:

```
$ git clone https://github.com/brianehenyo/brianehenyo.github.io.git 
$ cd brianehenyo.github.io/
$ bundle install
$ bundle exec jekyll serve
```

You now have a local instance of your Jekyll website that you can access at `localhost:4000`.
