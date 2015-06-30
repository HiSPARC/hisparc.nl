HiSPARC
=======

This is the source for the HiSPARC website. The website is a statically
generated, which means that the source is compiled to HTML/CSS files and
no database is used. The source
[Markdown](http://daringfireball.net/projects/markdown/)/
reStructuredText files are rendered to HTML using templates. These
templates use the [Jinja2](http://jinja.pocoo.org/) template language
(similar to [Django
templates](https://docs.djangoproject.com/en/dev/topics/templates/)). To
generate the static website the Python-based static site generator
[Pelican](http://blog.getpelican.com) is used.

These pages are hosted by GitHub Pages and can be reached via
[www.hisparc.nl](http://www.hisparc.nl).


Installation and Generation
---------------------------

Pelican is required to build the website. Install it with pip:

    $ pip install pelican

Once installed go to the repository and run the following command:

    $ pelican content

This generates the site in the `output` directory.
