Permalink Filter
================

Permalink Filter provides a content filter that automatically adds permalinks to
heading tags in your content.

Permalinks are characters or text (typically '#', '¶' or '§') that are displayed
next to headings and which link specifically to that heading via a unique ID.
The ID is generated from the text of the heading (for cleaner URLs), unless the
heading already has an ID attribute (in which case it is used instead).

You can customise:

- Which heading types the links are added to (h1, h2, h3, h4, h5, h6)
- The character/text to use for the links
- Where the links are positioned (before or after the heading)
- Whether default styling is applied to the links (e.g. hover over a heading for
  the link to appear)

Installation
------------

- Install this module using the official Backdrop CMS instructions at
  https://backdropcms.org/guide/modules.

- Visit the 'Text editors and formats' page under Administration > Configuration
  \> Content authoring (admin/config/content/formats) and configure the text
  format you'd like to enable the Permalink Filter on.

- Tick the 'Add permalinks to heading tags' box to enable the filter, and make
  sure it appears towards the end of the filter processing order (the exact
  position will depend on what other filters are enabled). Save.

- Visit the configuration page under Administration > Configuration > Content
  authoring > Permalink filter (admin/config/content/permalink-filter) and
  adjust the settings as appropriate for your site.

- (Optional) Style the permalinks with your own custom CSS.

Issues
------

Bugs and Feature requests should be reported in the Issue Queue:
https://github.com/backdrop-contrib/permalink_filter/issues.

Current Maintainers
-------------------

- Seeking maintainer(s)

Credits
-------

- Written for Backdrop by Peter Anderson (https://github.com/BWPanda).

License
-------

This project is GPL v2 software. See the LICENSE.txt file in this directory for
complete text.

