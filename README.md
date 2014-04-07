Google Map Basic
================================================================================

Developer
-----------------------------------------------
Nicolaas Francken [at] sunnysideup.co.nz

Requirements
-----------------------------------------------
see composer.json

Documentation
-----------------------------------------------
1. create authentication key:http://code.google.com/apis/maps/signup.html
2. set configs
3. add decorator to sitetree + controller (see config)
4. create custom js file (if needed)
5. to include, add $GoogleMapBasic to your template...

Installation Instructions
-----------------------------------------------
1. Find out how to add modules to SS and add module as per usual.

2. Review configs and add entries to mysite/_config/config.yml
(or similar) as necessary.
In the _config/ folder of this module
you should to find some examples of config options (if any).

3. add <% include GoogleMapBasic %> to your template

4. go into CMS and add a map to a page type that can have maps (as set in config)

5. review on screen and code CSS for the right look and feel.
