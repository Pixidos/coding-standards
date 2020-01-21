### Pixidos coding standards

Coding standarts and check for pixidos libs

### Install

```bash
composer require pixidos/coding-standards
```

##### phpstan
make include in you phpstan.neon
````
includes:
     - vendor/pixidos/coding-standards/phpstan.neon
````

##### phpcs
include rules into your ruleset
````
<?xml version="1.0"?>
<ruleset name="Your name of ruleset">
    <rule ref="vendor/pixidos/coding-standards/phpcs.xml"/>
</ruleset>

````
