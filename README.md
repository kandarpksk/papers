#Skaket

Skaket is a simple blog theme powered by [Jekyll](http://jekyllrb.com/) and [Bootstrap](http://getbootstrap.com/).

To use Skaket, install Jekyll and clone this repository:
```bash
~$ gem install jekyll
~$ git clone https://github.com/seankross/skaket.git
~$ cd skaket
~$ jekyll serve
# => Now browse to http://localhost:4000
```

Configuration is easy, just edit `_config.yml`:

```yaml
name: Sean Kross
pygments: true
base_url: /
markdown: redcarpet

github: seankross
twitter: seankross
```

At the beginning of each post there is some yaml front-matter which gives you some options:

```yaml
layout: post
title: Welcome to Jekyll!
date: 2014-02-03 23:16:00
jumbo_title: Welcome to Jekyll!
jumbo_subtitle: Static Websites from Plain Text
```

There's also a layout for notes, which are intended to be some mixture of a Gist, an email, and a blog post. The yaml front-matter for notes looks like this:

```yaml
layout: note
title: First Note
header: Consider the following
```

Items in this repository you may want to change before deploying this template:
- `_config.yml`
- The contents of the `_posts` directory
- The contents of the `notes` directory
- The About page.
- The yaml front-matter for `index.html`
- The contents of this `README.md` file