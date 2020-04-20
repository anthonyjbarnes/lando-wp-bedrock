# Local Wordpress Boilerplate and Environment 

**What will this give you?**
 - Ready to Dev local Wordpress instance which works on OSX, Windows and Linux
 - Improved wordpress structure, swapping the dreaded /wp-content for /app
 - Composer dependency management for WP Core and WP Plugins
 - Docker container LEMP Stack
 - PHPMyAdmin for easy Database Management
 - WP ClI out of the box 
 

## Instructions

1. If you don't already have it - Install lando [from here](https://github.com/lando/lando/releases/tag/v3.0.0-rrc.4).
2. Once installed, in root of project run: `lando start`
3. Install dependencies with composer: `lando composer install` (if you have composer installed locally then you can just run `composer install`)
4. If .env file does not get created automatically please rename .env.example or copy to .env
6. Visit http://lando-wp-bedrock.lndo.site/
7. Database can be viewed with PHPMyAdmin here http://pma.lando-wp-bedrock.lndo.site/


## Notes
The domain lando-wp-bedrock.lndo.site is just the default that works out of the box, you can customize the domain to anything you wish via the .lando.yml and .env file

Lando Docs - https://lando.dev/

Bedrock Docs - https://roots.io/bedrock/

## Credits
I take no credit or claim on any of the packages used in this repo. They are all maintained by their respective owners. I'm simply sharing the stack I like to use, and thought others might too.
