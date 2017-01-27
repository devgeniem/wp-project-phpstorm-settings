# PhpStorm settings for [devgeniem/wp-project](https://github.com/devgeniem/wp-project)

These are the default PhpStorm settings for `.idea` folder used by Geniem.

## Contents
This will configure:
* composer.json location and composer path with `/usr/local/bin/composer`
* remote server configuration for `wordpress.test` for xdebug
    * This includes the local code mapping into `/var/www/project` inside container
    * Remember to regex replace this for the project address e.g `wordpress.test` -> `client.test`
* WordPress path

## Maintainers
[@onnimonni](https://github.com/onnimonni)

## License
MIT
