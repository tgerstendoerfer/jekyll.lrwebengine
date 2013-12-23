Web Gallery for Jekyll
======================

*jekyll.lrwebengine* is a very basic web gallery for Adobe Lightroom to
create photo galleries of [Jekyll](http://jekyllrb.com)-based web sites.
Instead of controlling the layout directly, this web gallery just creates
a single index referencing the thumbnail and full-size images, expecting
the `gallery` layout to do the heavy lifting.

It is meant as quick fix until I get around coding-up a proper LR/Jekyll
plugin that can be used in a publish service (which may or may not happen,
though).

Installation
------------

Fork/clone the repository directly to your
`~/Library/Application Support/Adobe/Lightroom/Web Galleries` directory
on OS&nbsp;X, or `%APPDATA%\Adobe\Lightroom\Web Galleries` on Windows.

Usage
-----

After installation, *TG Jekyll Gallery* should show up as a layout style
in Lightroom's *Web* module and can be chosen just like any other module.

Once you have the photos for your gallery chosen, you can hit *Export…*
and create a new subfolder for your Jekyll gallery.

To make the gallery work as expected, create a `gallery` Jekyll layout
that processes the list of image links.
