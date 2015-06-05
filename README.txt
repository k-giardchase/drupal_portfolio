Developers
----------------
Kyle Giard-Chase

Date
-----------
June 5 2015

Description
------------
A portfolio website created with Drupal which features several custom modules.

Technologies Used
-----------------
 * Drupal
 * MAMP
 * PHP

Use and Editing
-----------------
To view the site,
1. Open your command line and clone the repository using the command `https://github.com/k-giardchase/drupal_portfolio`
2. Change directory into the top level of the project folder. `cd drupal_portfolio`
3. Go into MAMP preferences and set the document root to the Drupal Core directory `drupal_portfolio`.
4. Start your MAMP servers.
5. Import the database using the instructions in the database section.
6. Open your browser and navigate to your root path: `localhost:8888`
7. NOTE: to login as an admin use the username `admin` and the password `admin`.

DATABASE
-----------------
1. Open your browser and navigate to `localhost:8888/MAMP`
2. Select `phpMyAdmin` under `Tools`.
3. Click the `Import` tab.
4. Leave all default settings, but do take care to make sure the character set is `utf-8`.
5. Click `Choose File` button and select drupal_portfolio.sql.zip found in `drupal_assessment3/sites/db-backups/`.
6. Click `Go` button on the bottom left.
7. Select `Privileges` tab and click `Add User`. Set the username to `kyle` and the password to `admin`.
8. Open your browser once more and clear your cookies.
9. Navigate to your root path: `localhost:8888`.


##Copyright (c) 2015 Kyle Giard-Chase
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

CONTENTS OF THIS FILE
---------------------

 * About Drupal
 * Configuration and features
 * Installation profiles
 * Appearance
 * Developing for Drupal

ABOUT DRUPAL
------------

Drupal is an open source content management platform supporting a variety of
websites ranging from personal weblogs to large community-driven websites. For
more information, see the Drupal website at http://drupal.org/, and join the
Drupal community at http://drupal.org/community.

Legal information about Drupal:
 * Know your rights when using Drupal:
   See LICENSE.txt in the same directory as this document.
 * Learn about the Drupal trademark and logo policy:
   http://drupal.com/trademark

CONFIGURATION AND FEATURES
--------------------------

Drupal core (what you get when you download and extract a drupal-x.y.tar.gz or
drupal-x.y.zip file from http://drupal.org/project/drupal) has what you need to
get started with your website. It includes several modules (extensions that add
functionality) for common website features, such as managing content, user
accounts, image uploading, and search. Core comes with many options that allow
site-specific configuration. In addition to the core modules, there are
thousands of contributed modules (for functionality not included with Drupal
core) available for download.

More about configuration:
 * Install, upgrade, and maintain Drupal:
   See INSTALL.txt and UPGRADE.txt in the same directory as this document.
 * Learn about how to use Drupal to create your site:
   http://drupal.org/documentation
 * Download contributed modules to sites/all/modules to extend Drupal's
   functionality:
   http://drupal.org/project/modules
 * See also: "Developing for Drupal" for writing your own modules, below.

INSTALLATION PROFILES
---------------------

Installation profiles define additional steps (such as enabling modules,
defining content types, etc.) that run after the base installation provided
by core when Drupal is first installed. There are two basic installation
profiles provided with Drupal core.

Installation profiles from the Drupal community modify the installation process
to provide a website for a specific use case, such as a CMS for media
publishers, a web-based project tracking tool, or a full-fledged CRM for
non-profit organizations raising money and accepting donations. They can be
distributed as bare installation profiles or as "distributions". Distributions
include Drupal core, the installation profile, and all other required
extensions, such as contributed and custom modules, themes, and third-party
libraries. Bare installation profiles require you to download Drupal Core and
the required extensions separately; place the downloaded profile in the
/profiles directory before you start the installation process. Note that the
contents of this directory may be overwritten during updates of Drupal core;
it is advised to keep code backups or use a version control system.

Additionally, modules and themes may be placed inside subdirectories in a
specific installation profile such as profiles/your_site_profile/modules and
profiles/your_site_profile/themes respectively to restrict their usage to only
sites that were installed with that specific profile.

More about installation profiles and distributions:
 * Read about the difference between installation profiles and distributions:
   http://drupal.org/node/1089736
 * Download contributed installation profiles and distributions:
   http://drupal.org/project/distributions
 * Develop your own installation profile or distribution:
   http://drupal.org/developing/distributions

APPEARANCE
----------

In Drupal, the appearance of your site is set by the theme (themes are
extensions that set fonts, colors, and layout). Drupal core comes with several
themes. More themes are available for download, and you can also create your own
custom theme.

More about themes:
 * Download contributed themes to sites/all/themes to modify Drupal's
   appearance:
   http://drupal.org/project/themes
 * Develop your own theme:
   http://drupal.org/documentation/theme

DEVELOPING FOR DRUPAL
---------------------

Drupal contains an extensive API that allows you to add to and modify the
functionality of your site. The API consists of "hooks", which allow modules to
react to system events and customize Drupal's behavior, and functions that
standardize common operations such as database queries and form generation. The
flexible hook architecture means that you should never need to directly modify
the files that come with Drupal core to achieve the functionality you want;
instead, functionality modifications take the form of modules.

When you need new functionality for your Drupal site, search for existing
contributed modules. If you find a module that matches except for a bug or an
additional needed feature, change the module and contribute your improvements
back to the project in the form of a "patch". Create new custom modules only
when nothing existing comes close to what you need.

More about developing:
 * Search for existing contributed modules:
   http://drupal.org/project/modules
 * Contribute a patch:
   http://drupal.org/patch/submit
 * Develop your own module:
   http://drupal.org/developing/modules
 * Follow best practices:
   http://drupal.org/best-practices
 * Refer to the API documentation:
   http://api.drupal.org/api/drupal/7
