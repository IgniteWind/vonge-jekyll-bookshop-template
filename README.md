# Vonge

Vonge is a Personal portfolio/blog site template for Jekyll. Browse through a [live demo](https://jazzed-kale.cloudvent.net/).
Increase the web presence of your brand with this configurable theme.

![Vonge template screenshot](_screenshot.png)

Vonge was made by [CloudCannon](http://cloudcannon.com/), the JAMStack Cloud CMS.
The component library is built and maintained for use with [Bookshop](https://github.com/cloudcannon/bookshop/)

Find more templates, themes and step-by-step Jekyll tutorials at [CloudCannon Community](https://cloudcannon.com/community/).

[![Deploy to CloudCannon](https://buttons.cloudcannon.com/deploy.svg)](https://app.cloudcannon.com/register#sites/connect/github/CloudCannon/vonge-jekyll-bookshop-template)

## Features

* Component library for website building
* Fully configurable Website
* Pre-built pages
* Pre-styled components
* Blog
* Category pages
* Testimonials
* Portfolio
* Live editing with [CloudCannon](http://cloudcannon.com/)
* Optimised for editing in [CloudCannon](http://cloudcannon.com/)
* Search engine optimisation

## Develop

Vonge was built with [Jekyll](http://jekyllrb.com/) version 4.2.0, but should support newer versions as well.

Install the dependencies for Bookshop:

Install the Jekyll dependencies with [Bundler](http://bundler.io/):

```bash
nvm use 14 <-- version important
npm install
npm run install-jekyll

gem i did_you_mean -v=1.5.0
gem uni did_you_mean -v=1.6.1

# ruby 3.1.2 is not stable.
RUBY_CONFIGURE_OPTS=--with-readline-dir="$(brew --prefix readline)" rbenv install 3.1.3 --verbose

(tips) Dont use ruby_install, try rbenv

➜ rbenv global 3.1.3
ruby 3.1.3
bundler 2.4.7

# check if jekyll pick the right ruby
gem install jekyll -v 4.3.2
# 4.3.1 got issues
jekyll -v

npm start
```

## FAQ
cd site
bundle update cloudcannon-jekyll-bookshop

## Future
[jekyll tut](https://jekyllrb.com/)



