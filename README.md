CSSMIN_PHP_SCRIPT
=================

This script will strip minify all css on the website.


Simply link php script in header

ex. <code><link rel="stylesheet" type="text/css" href="/cssmin.php"/></code>

Inside cssmin.php you'll find include function that would be the place to link css needed to be minified.

Ex:<code>
  /* your css files */
  include('master.css');
  include('typography.css');
  include('grid.css');
  include('print.css');
  include('handheld.css');
</code>
