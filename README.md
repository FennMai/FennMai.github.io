
# Academic Pages

![pages-build-deployment](https://github.com/academicpages/academicpages.github.io/actions/workflows/pages/pages-build-deployment/badge.svg)

Academic Pages is a Github Pages template for academic websites.

# update discovery the template
```
now update:
### 1 
_config.yml  
# change the left part information in the first page 
### 2
├── _pages  # change the basic pages extent
│   ├── about.md # firtly page / heading page

tree:
── assets
│   ├── css
│   │   ├── academicons.css
│   │   ├── academicons.min.css
│   │   ├── collapse.css
│   │   └── main.scss
│   ├── fonts
│   │   ├── academicons.eot
│   │   ├── academicons.svg
│   │   ├── academicons.ttf
│   │   └── academicons.woff
│   ├── js
│   │   ├── collapse.js
│   │   ├── _main.js
│   │   ├── main.min.js
│   │   ├── plugins
│   │   │   ├── jquery.fitvids.js
│   │   │   ├── jquery.greedy-navigation.js
│   │   │   ├── jquery.magnific-popup.js
│   │   │   ├── jquery.smooth-scroll.min.js
│   │   │   └── stickyfill.min.js
│   │   └── vendor
│   │       └── jquery
│   │           └── jquery-1.12.4.min.js
│   └── webfonts
│       ├── fa-brands-400.ttf
│       ├── fa-brands-400.woff2
│       ├── fa-regular-400.ttf
│       ├── fa-regular-400.woff2
│       ├── fa-solid-900.ttf
│       ├── fa-solid-900.woff2
│       ├── fa-v4compatibility.ttf
│       └── fa-v4compatibility.woff2
├── _config.yml  
# change the left part information in the first page 
├── CONTRIBUTING.md
├── _data
│   ├── authors.yml
│   ├── comments
│   │   ├── layout-comments
│   │   │   ├── comment-1470944006665.yml
│   │   │   └── comment-1470944162041.yml
│   │   ├── markup-syntax-highlighting
│   │   │   └── comment-1470969665387.yml
│   │   └── welcome-to-jekyll
│   │       ├── comment-1470942205700.yml
│   │       ├── comment-1470942247755.yml
│   │       ├── comment-1470942265819.yml
│   │       └── comment-1470942493518.yml
│   ├── navigation.yml
│   └── ui-text.yml
├── _drafts
│   └── post-draft.md
├── files
│   ├── paper1.pdf
│   ├── paper2.pdf
│   └── paper3.pdf
├── Gemfile
├── images
│   ├── 3953273590_704e3899d5_m.jpg
│   ├── 500x300.png
│   ├── bio-photo-2.jpg
│   ├── bio-photo.jpg
│   ├── browserconfig.xml
│   ├── editing-talk.png
│   ├── favicon.ico
│   ├── foo-bar-identity.jpg
│   ├── foo-bar-identity-th.jpg
│   ├── image-alignment-1200x4002.jpg
│   ├── image-alignment-150x150.jpg
│   ├── image-alignment-300x200.jpg
│   ├── image-alignment-580x300.jpg
│   ├── manifest.json
│   ├── mstile-144x144.png
│   ├── mstile-150x150.png
│   ├── mstile-310x150.png
│   ├── mstile-310x310.png
│   ├── mstile-70x70.png
│   ├── paragraph-indent.png
│   ├── paragraph-no-indent.png
│   ├── profile.png
│   ├── safari-pinned-tab.svg
│   └── site-logo.png
├── _includes
│   ├── analytics.html
│   ├── analytics-providers
│   │   ├── custom.html
│   │   ├── google-analytics-4.html
│   │   ├── google.html
│   │   └── google-universal.html
│   ├── archive-single-cv.html
│   ├── archive-single.html
│   ├── archive-single-talk-cv.html
│   ├── archive-single-talk.html
│   ├── author-profile.html
│   ├── base_path
│   ├── breadcrumbs.html
│   ├── browser-upgrade.html
│   ├── category-list.html
│   ├── comment.html
│   ├── comments.html
│   ├── comments-providers
│   │   ├── custom.html
│   │   ├── discourse.html
│   │   ├── disqus.html
│   │   ├── facebook.html
│   │   ├── google-plus.html
│   │   ├── scripts.html
│   │   └── staticman.html
│   ├── feature_row
│   ├── footer
│   │   └── custom.html
│   ├── footer.html
│   ├── gallery
│   ├── group-by-array
│   ├── head
│   │   └── custom.html
│   ├── head.html
│   ├── masthead.html
│   ├── nav_list
│   ├── page__hero.html
│   ├── page__taxonomy.html
│   ├── paginator.html
│   ├── post_pagination.html
│   ├── read-time.html
│   ├── scripts.html
│   ├── seo.html
│   ├── sidebar.html
│   ├── social-share.html
│   ├── tag-list.html
│   └── toc
├── _layouts
│   ├── archive.html
│   ├── archive-taxonomy.html
│   ├── compress.html
│   ├── default.html
│   ├── single.html
│   ├── splash.html
│   └── talk.html
├── LICENSE
├── markdown_generator
│   ├── publications.ipynb
│   ├── publications.py
│   ├── publications.tsv
│   ├── PubsFromBib.ipynb
│   ├── pubsFromBib.py
│   ├── readme.md
│   ├── talks.ipynb
│   ├── talks.py
│   └── talks.tsv
├── package.json
├── _pages  # change the basic pages extent
│   ├── 404.md
│   ├── about.md # firtly page / heading page
│   ├── archive-layout-with-content.md
│   ├── category-archive.html
│   ├── collection-archive.html
│   ├── cv.md
│   ├── markdown.md
│   ├── non-menu-page.md
│   ├── page-archive.html
│   ├── portfolio.html
│   ├── publications.md
│   ├── sitemap.md
│   ├── tag-archive.html
│   ├── talkmap.html
│   ├── talks.html
│   ├── teaching.html
│   ├── terms.md
│   └── year-archive.html
├── _portfolio
│   ├── portfolio-1.md
│   └── portfolio-2.html
├── _posts
│   ├── 2012-08-14-blog-post-1.md
│   ├── 2013-08-14-blog-post-2.md
│   ├── 2014-08-14-blog-post-3.md
│   ├── 2015-08-14-blog-post-4.md
│   └── 2199-01-01-future-post.md
├── _publications
│   ├── 2009-10-01-paper-title-number-1.md
│   ├── 2010-10-01-paper-title-number-2.md
│   ├── 2015-10-01-paper-title-number-3.md
│   └── 2024-02-17-paper-title-number-4.md
├── README.md
├── _sass
│   ├── _animations.scss
│   ├── _archive.scss
│   ├── _base.scss
│   ├── _buttons.scss
│   ├── _footer.scss
│   ├── _forms.scss
│   ├── _masthead.scss
│   ├── _mixins.scss
│   ├── _navigation.scss
│   ├── _notices.scss
│   ├── _page.scss
│   ├── _print.scss
│   ├── _reset.scss
│   ├── _sidebar.scss
│   ├── _syntax.scss
│   ├── _tables.scss
│   ├── _utilities.scss
│   ├── _variables.scss
│   └── vendor
│       ├── breakpoint
│       │   ├── _breakpoint.scss
│       │   ├── _context.scss
│       │   ├── _helpers.scss
│       │   ├── _legacy-settings.scss
│       │   ├── _no-query.scss
│       │   ├── parsers
│       │   │   ├── double
│       │   │   │   ├── _default-pair.scss
│       │   │   │   ├── _default.scss
│       │   │   │   └── _double-string.scss
│       │   │   ├── _double.scss
│       │   │   ├── _query.scss
│       │   │   ├── resolution
│       │   │   │   └── _resolution.scss
│       │   │   ├── _resolution.scss
│       │   │   ├── single
│       │   │   │   └── _default.scss
│       │   │   ├── _single.scss
│       │   │   ├── triple
│       │   │   │   └── _default.scss
│       │   │   └── _triple.scss
│       │   ├── _parsers.scss
│       │   ├── _respond-to.scss
│       │   └── _settings.scss
│       ├── font-awesome
│       │   ├── _animated.scss
│       │   ├── _bordered-pulled.scss
│       │   ├── brands.scss
│       │   ├── _core.scss
│       │   ├── _fixed-width.scss
│       │   ├── fontawesome.scss
│       │   ├── _functions.scss
│       │   ├── _icons.scss
│       │   ├── _list.scss
│       │   ├── _mixins.scss
│       │   ├── regular.scss
│       │   ├── _rotated-flipped.scss
│       │   ├── _screen-reader.scss
│       │   ├── _shims.scss
│       │   ├── _sizing.scss
│       │   ├── solid.scss
│       │   ├── _stacked.scss
│       │   ├── v4-shims.scss
│       │   └── _variables.scss
│       ├── magnific-popup
│       │   ├── _magnific-popup.scss
│       │   └── _settings.scss
│       └── susy
│           ├── _su.scss
│           ├── susy
│           │   ├── language
│           │   │   ├── susy
│           │   │   │   ├── _background.scss
│           │   │   │   ├── _bleed.scss
│           │   │   │   ├── _box-sizing.scss
│           │   │   │   ├── _breakpoint-plugin.scss
│           │   │   │   ├── _container.scss
│           │   │   │   ├── _context.scss
│           │   │   │   ├── _gallery.scss
│           │   │   │   ├── _grids.scss
│           │   │   │   ├── _gutters.scss
│           │   │   │   ├── _isolate.scss
│           │   │   │   ├── _margins.scss
│           │   │   │   ├── _padding.scss
│           │   │   │   ├── _rows.scss
│           │   │   │   ├── _settings.scss
│           │   │   │   ├── _span.scss
│           │   │   │   └── _validation.scss
│           │   │   ├── susyone
│           │   │   │   ├── _background.scss
│           │   │   │   ├── _functions.scss
│           │   │   │   ├── _grid.scss
│           │   │   │   ├── _isolation.scss
│           │   │   │   ├── _margin.scss
│           │   │   │   ├── _media.scss
│           │   │   │   ├── _padding.scss
│           │   │   │   └── _settings.scss
│           │   │   ├── _susyone.scss
│           │   │   └── _susy.scss
│           │   ├── output
│           │   │   ├── float
│           │   │   │   ├── _container.scss
│           │   │   │   ├── _end.scss
│           │   │   │   ├── _isolate.scss
│           │   │   │   └── _span.scss
│           │   │   ├── _float.scss
│           │   │   ├── shared
│           │   │   │   ├── _background.scss
│           │   │   │   ├── _container.scss
│           │   │   │   ├── _direction.scss
│           │   │   │   ├── _inspect.scss
│           │   │   │   ├── _margins.scss
│           │   │   │   ├── _output.scss
│           │   │   │   └── _padding.scss
│           │   │   ├── _shared.scss
│           │   │   ├── support
│           │   │   │   ├── _background.scss
│           │   │   │   ├── _box-sizing.scss
│           │   │   │   ├── _clearfix.scss
│           │   │   │   ├── _prefix.scss
│           │   │   │   ├── _rem.scss
│           │   │   │   └── _support.scss
│           │   │   └── _support.scss
│           │   ├── su
│           │   │   ├── _grid.scss
│           │   │   ├── _settings.scss
│           │   │   ├── _utilities.scss
│           │   │   └── _validation.scss
│           │   └── _su.scss
│           ├── _susyone.scss
│           └── _susy.scss
├── talkmap
│   ├── leaflet_dist
│   │   ├── leaflet.markercluster.js
│   │   ├── leaflet.markercluster-src.js
│   │   ├── MarkerCluster.css
│   │   ├── MarkerCluster.Default.css
│   │   └── screen.css
│   ├── map.html
│   └── org-locations.js
├── talkmap.ipynb
├── talkmap.py
├── _talks
│   ├── 2012-03-01-talk-1.md
│   ├── 2013-03-01-tutorial-1.md
│   ├── 2014-02-01-talk-2.md
│   └── 2014-03-01-talk-3.md
└── _teaching
    ├── 2014-spring-teaching-1.md
    └── 2015-spring-teaching-2.md

```

# Getting Started

1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Click the "Use this template" button in the top right.
1. On the "New repository" page, enter your repository name as "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and add your content.
1. Upload any files (like PDFs, .zip files, etc.) to the `files/` directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section
1. (Optional) Use the Jupyter notebooks or python scripts in the `markdown_generator` folder to generate markdown files for publications and talks from a TSV file.

See more info at https://academicpages.github.io/

## Running Locally

When you are initially working your website, it is very useful to be able to preview the changes locally before pushing them to GitHub. To work locally you will need to:

1. Clone the repository and made updates as detailed above.
1. Make sure you have ruby-dev, bundler, and nodejs installed: `sudo apt install ruby-dev ruby-bundler nodejs`
1. Run `bundle install` to install ruby dependencies. If you get errors, delete Gemfile.lock and try again.
1. Run `jekyll serve -l -H localhost` to generate the HTML and serve it from `localhost:4000` the local server will automatically rebuild and refresh the pages on change.

If you are running on Linux it may be necessary to install some additional dependencies prior to being able to run locally: `sudo apt install build-essentials gcc make`

# Maintenance 

Bug reports and feature requests to the template  should be [submitted via GitHub](https://github.com/academicpages/academicpages.github.io/issues/new/choose). For questions concerning how to style the template, please feel free to start a [new discussion on GitHub](https://github.com/academicpages/academicpages.github.io/discussions).

This repository was forked (then detached) by [Stuart Geiger](https://github.com/staeiou) from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/), which is © 2016 Michael Rose and released under the MIT License (see LICENSE.md). It is currently being maintained by [Robert Zupko](https://github.com/rjzupkoii) and additional maintainers would be welcomed.

## Bugfixes and enhancements

If you have bugfixes and enhancements that you would like to submit as a pull request, you will need to [fork](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo) this repository as opposed to using it as a template. This will also allow you to [synchronize your copy](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/syncing-a-fork) of template to your fork as well.

Unfortunately, one logistical issue with a template theme like Academic Pages that makes it a little tricky to get bug fixes and updates to the core theme. If you use this template and customize it, you will probably get merge conflicts if you attempt to synchronize. If you want to save your various .yml configuration files and markdown files, you can delete the repository and fork it again. Or you can manually patch.
