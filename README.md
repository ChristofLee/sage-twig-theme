# Sage + Twig theme for Wordpress

Sage is a WordPress starter starter theme with a modern front-end development workflow. Twig is a modern template enging. 

The Sage + Twig starter theme combines the best of both.

>Do check out the [Timber Wiki](https://github.com/jarednova/timber/wiki). It will help you to learn Twig and how to set it up with Wordpress.

## Theme installation

Clone the git repo - `git clone git@github.com:studiorabota/sage-twig-theme.git` and then rename the directory to the name of your theme or website.

## Theme setup

Edit `lib/setup.php` to enable or disable theme features, setup navigation menus, post thumbnail sizes, post formats, and sidebars.

## Installation

You will need:

* [Gulp](http://gulpjs.com/)
* [Bower](http://bower.io/)
* [Composer](https://getcomposer.org/)
* [Node](http://nodejs.org/download/) - We recommend you update to the latest version of npm: `npm install -g npm@latest`.

From the command line:

2. Navigate to the theme directory, then run `npm install`
3. Run `bower install`
4. Run `composer update` to install the Timber plugin
5. Run `gulp watch`

You now have all the necessary dependencies to run the build process.

## Adding extra data to Twig

In `lib/timber.php` you can add extra data to be used in your Twig templates. This is only for data which needs to be available site-wide, like menus, etc. 

You can also add data in for ex. page.php, archive.php, etc. For this you should check out the Timber documentation.


## Documentation

* Sage: [https://github.com/roots/sage](https://github.com/roots/sage)
* Twig: [http://twig.sensiolabs.org/](http://twig.sensiolabs.org/)
* Timber: [https://github.com/jarednova/timber/wiki](https://github.com/jarednova/timber/wiki)
