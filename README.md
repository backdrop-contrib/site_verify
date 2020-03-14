Site Verification
======================

The Site verification module verifies ownership of a site for use with search
engines. It assists with the site/domain ownership authentication/verification
for search engines. There are two types of verification methods supported:
adding meta tags, or uploading a specific file. If you are provided with a file
to upload, this module makes it easy because you can upload the file in the
module's interface and the proper filename and file contents will be saved and
used in the authentication process.


Installation
------------

- Install this module using the official Backdrop CMS instructions at
  https://backdropcms.org/guide/modules.

- Visit the configuration page under Administration > Configuration > Search >
  Verifications (admin/config/search/verify) and enter the required information.

CONFIGURATION
-------------

To Add a verification to a site:
1. To add a verification select "Add verification".
1. Select the search engine to which you would like to send verification.
1. "Verification META tag" is the full meta tag provided for verification, it is only visible in the source code of the front page.
1. There is an option to provide a file, simply upload it under "Upload an existing verification file" and then under "Verification file" provide the name of the HTML file you uploaded.
1. A description of the verification file can be added to "Verification file contents". By default it reads, "This is a verification page."
1. Save.

To Edit an existing verification:
1. Navigate to Administration > Configuration > Search > Verifications.
1. Select Edit next to the search engine to be edited.
1. Make appropriate edits.
1. Save.

To obtain the verification files, use one or more of the following services.

GOOGLE
Create a Google Webmaster Tools Account:
* https://www.google.com/webmasters/tools/home
* https://support.google.com/webmasters/answer/35179

Bing
Create a Bing Webmaster Tools Account:
* http://www.bing.com/toolbox/webmaster
* http://www.bing.com/webmaster/help/how-to-verify-ownership-of-your-site-afcfefc6

Yandex
Create Yandax webmaster account:
* https://webmaster.yandex.com
* https://help.yandex.com/webmaster/service/my-sites.xml


Documentation
-------------

Additional documentation is located in the Wiki:
https://github.com/backdrop-contrib/site_verify/wiki/Documentation.

Issues
------

Bugs and Feature requests should be reported in the Issue Queue:
https://github.com/backdrop-contrib/site_verify/issues.

Current Maintainers
-------------------

- [Jen Lampton](https://github.com/jenlampton).
- [Alex Finnarn](https://github.com/alexfinnarn).
- Seeking additional maintainers

Credits
-------

- Maintained for Drupal by [Kevin Reynen](https://www.drupal.org/u/kreynen)
- Maintained for Drupal by [Jim.M](https://www.drupal.org/u/jimm)
- Maintained for Drupal by [Dave Reid](https://www.drupal.org/u/dave-reid)
- Drupal version Supported by [University of Colorado Boulder](https://www.colorado.edu)

License
-------

This project is GPL v2 software.
See the LICENSE.txt file in this directory for complete text.


