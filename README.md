File Usage Add
======================

Allows any existing file to be self-referenced.

This solves the problem that any pre-existing file without a reference cannot
be referecned anywhere else. Refernces are needed on managed file fields, images
inserted into content, and other various places.


Installation <!-- This section is required. -->
------------

- Install this module using the official Backdrop CMS instructions at
  https://docs.backdropcms.org/documentation/extend-with-modules.

- Visit Administration > Content > Manage Files and "manage" any pre-existing
  file that doesd NOT have a value in the `Use count` column.  You should see a'
  new checkbox labeled `Create a self-refrence to this file`.

- Check this box, and you will create a reference to this file from the File
  module, allowing it to be referenced from other places around your site.


Issues <!-- This section is required. -->
------

Bugs and feature requests should be reported in [the Issue Queue](https://github.com/backdrop-contrib/file_add_reference/issues).

Current Maintainers <!-- This section is required. -->
-------------------

- [Jen Lampton](https://github.com/jenlampton).
<!-- You may also wish to add: -->
- Seeking additional maintainers.

Credits <!-- This section is required. -->
-------

- Developed for Backdrop CMS by [Jen Lampton](https://github.com/jenlampton).

License <!-- This section is required. -->
-------

This project is GPL v2 software.
See the LICENSE.txt file in this directory for complete text.

