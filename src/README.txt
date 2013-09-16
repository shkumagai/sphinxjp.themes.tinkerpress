=============================
 sphinxjp.themes.tinkerpress
=============================

Some famous blogging tool style for Tinkerer


Output sample
=============
:output: http://shkumagai.github.io/blog/index.html


Feature
=======
* provide tinkerer blog theme like some famous blogging tool


Installation
============
Make environment with easy_install::

   $ easy_install sphinxjp.themes.tinkerpress


setup conf.py with::

   html_theme = 'tinkerpress'
   extensions = [..., 'sphinxjp.themecore']


and run::

   $ tinker -b


Requirement
===========
Libraries:

* Python 2.4 or later (not support 3.x)
* Sphinx 1.0.x or later.
* Tinkerer 1.0.x or later.


Browsers:

* Safari
* Chrome
* Firefox 10 or later


License
=======
Licensed under the `MIT license <http://www.opensource.org/licenses/mit-license.php>`_ .
See the LICENSE file for specific terms.


.. END
