Hosting Projects
================

A simple example of add a "Project" field to associate sites and platforms.

Getting Started
---------------

Enable the Hosting Projects module.

Create some platforms:

    $ cd ~/platforms
    $ drush dl
    $ mv drupal-7.43 dev
    $ cp -r dev test
    $ cp -r dev prod

Add platform nodes for these in Aegir. Note the new "Project" field. Add a common project name to all three platforms.

Next create a site, adding the same project name used for the platforms.

From now on, only the platforms in the same project will be available to migrate or clone the site to.
