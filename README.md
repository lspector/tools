# AILA Tools & News Website

This readme was adopted from the ai-libarts-website readme created by [Oliver-BE](https://github.com/Oliver-BE).

# How to run locally

1. Clone this repository to your local device.

```
$ git clone https://github.com/lspector/tools.git
```

2. Install the Jekyll gem dependencies by running

```
$ bundle install
```

> **NOTE**: If this doesn't work you likely need to install the the Jekyll and Bundler gems by running `gem install jekyll bundler`. If you're on a Mac you should already have Ruby installed on your system, so this command should work (gems are packages/libraries in the Ruby language). If installing Jekyll and Bundler doesn't work, you might not have Ruby installed. [Here](https://jekyllrb.com/docs/installation/macos/) is a detailed guide to getting Ruby/Jekyll installed on Mac (tutorials for other operating systems are also available).

3. Build the Jekyll site locally:

```
$ bundle exec jekyll serve
```

4. You should get an output that contains something that looks like the following:

```
> Server address: http://127.0.0.1:4000/tools
```

Follow the server address given to see the Jekyll site locally. Now you can make changes in your text editor and see them update in real time at the server address above.

> [This](https://idratherbewriting.com/documentation-theme-jekyll/mydoc_publishing_github_pages.html) is a great reference for the full process in getting a site set up to run locally with Jekyll and GitHub Pages. [Here](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll) is a less good reference from the GitHub Pages documentation on how to test your GitHub Pages site locally with Jekyll.

# Demo

View this jekyll theme in action at https://lspector.github.io/tools
