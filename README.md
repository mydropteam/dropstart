# dropstart

a composer based blueprint to start Drupal 8 projects, works as an addon to drupal-composer/drupal-project

Please add/replace in [drupal-composer/drupal-project](https://github.com/drupal-composer/drupal-project) to the composer.json the following:

```json
"repositories": [
        {
            "type": "composer",
            "url": "https://packagist.drupal-composer.org"
        },
        {
            "type": "vcs",
            "url": "https://github.com/mydropteam/dropstart"
        }
    ],
    ...
    
    "require": {
        "mydropteam/dropstart": "dev-master",
        "composer/installers": "^1.0.20",
        "drupal-composer/drupal-scaffold": "^2.0.1",
        "cweagans/composer-patches": "~1.0",
        "drupal/core": "~8.0",
        "drush/drush": "~8.0",
        "drupal/console": "~1.0"
    },
```
