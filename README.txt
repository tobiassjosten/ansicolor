$Id: README.txt,v 1.1 2009/11/27 22:21:39 tobiassjosten Exp $

-- SUMMARY --

This Drupal module converts ANSI colors into more web friendly equivalents.

It does this by translating ANSI sequences into span tags with proper (X)HTML
classes which are used to color it correctly, using CSS.

For a full description of the module, visit the project page:
  http://drupal.org/project/ansicolor

To submit bug reports and feature suggestions, or to track changes:
  http://drupal.org/project/issues/ansicolor


-- REQUIREMENTS --

None.


-- INSTALLATION --

Install as usual, see http://drupal.org/node/70151 for further information.


-- CONFIGURATION --

* Visit admin/settings/filters and either choose to configure the input format
  you want to add ANSI Color to, or create a new one.

* Scroll down to Filters and check ANSI Color to enable it for this format.

* WARNING! Do not put the HTML filter after ANSI Color. Check the sequences for
  your format by visiting the Rearrange tab when editing your format.


-- CONTACT --

Current maintainers:
* Tobias Sjösten (tobiassjosten) - http://drupal.org/user/213383

This project has been sponsored by:
* NoGFX
  MUD gaming community. Visit http://nogfx.org/ for more information.

* Kollegorna
  Drupal specialists. Visit http://www.kollegorna.se for more information.
