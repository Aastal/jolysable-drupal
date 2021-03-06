INTRODUCTION
------------

JSON:API image styles is a JSON:API extension that exposes image style urls of a
drupal image to jsonapi export. This allows e.g. crop-defined image styles to be
consumed by frontend builds.

 * To submit bug reports and feature suggestions, or track changes:
   https://www.drupal.org/project/issues/jsonapi_image_styles


REQUIREMENTS
------------

 * This module is an extension to the core JSON:API module and requires Drupal
 8.7 or greater.


INSTALLATION
------------

 * Install as any contributed Drupal module. For further information, visit
   https://www.drupal.org/docs/8/extending-drupal-8/installing-drupal-8-modules


CONFIGURATION
-------------

 * Configure the image styles you wish to expose in Administration »
 Configuration » Web Services » JSON:API Image styles
 (/admin/config/services/jsonapi/image_styles)

   - Select the image styles you wish to expose for JSON:API

   - Select none to expose all defined image styles (default behaviour)


MAINTAINERS
-----------

Current maintainers:
 * Timo Kirkkala (kirkkala) - https://www.drupal.org/u/kirkkala

This project has been sponsored by:
 * Wunder.io
   Wunder is Europe's largest digital agency specialising in Drupal projects,
   web service design and business consulting. We work with private and public
   sectors.
