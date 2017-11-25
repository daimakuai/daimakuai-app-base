<p align="center">
    <a href="https://github.com/daimakuai" target="_blank">
        <img src="https://avatars0.githubusercontent.com/u/993323" height="100px">
    </a>
    <h1 align="center">Daimakuai Basic Project Template</h1>
    <br>
</p>


DIRECTORY STRUCTURE
-------------------

      app/		  contains assets definition
      config/             contains application configurations
      controllers/        contains Web controller classes
      tests/              contains various tests for the basic application
      vendor/             contains dependent 3rd-party packages
      resources/          contains view files for the Web application
      public/             contains the entry script and Web resources



REQUIREMENTS
------------

The minimum requirement by this project template that your Web server supports PHP 7.0.0.

INSTALLATION
------------

### Install via Composer

If you do not have [Composer](http://getcomposer.org/), you may install it by following the instructions
at [getcomposer.org](http://getcomposer.org/doc/00-intro.md#installation-nix).

You can then install this project template using the following command:

```
composer create-project --prefer-dist --stability=dev daimakuai/daimakuai-app-base


php artisan vendor:publish --provider="Jblv\Admin\AdminServiceProvider"


php artisan admin:install

```