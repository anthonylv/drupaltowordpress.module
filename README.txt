Drupal to WordPress migration analysis module
by Another Cup of Coffee Limited

A Drupal 6 module to display the results of pre-migration analysis for
Another Cup of Coffee Limited's Drupal to WordPress migration tool.

This is a convenience module and not intended for running on a live website.
If you run it on a live website, disable it and delete after use.

--- Installation instructions ---
(1) Make sure your site is Drupal 6.x
(2) Copy drupaltowordpress into your modules folder
(3) Enable the module
(4) Set the Drupal to WordPress block to appear in a region
(5) Go to [your site domain]/d2w/results to view the analysis results

Important note:
This module provides some basic analysis only and DOES NOT perform the actual migration.
For more information, please see:
http://anothercoffee.net/drupal-to-wordpress-migration-tool/


--- Known issues ---
On some Drupal installations, db_query() doesn't return any results. I'm currently
unable to pinpoint the reason. If this happens on your site, instead of the results
you'll see a message saying that this module is incompatible with your Drupal installation.



First released 2015-02-16 by Anthony Lopez-Vito of Another Cup of Coffee Limited
http://anothercoffee.net

This code is released under GNU GENERAL PUBLIC LICENSE Version 2 in accordance with The Drupal Association's requirements.

Please see LICENSE.txt.
