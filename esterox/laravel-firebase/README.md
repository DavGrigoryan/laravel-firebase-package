- php: 8.2
# publish config file
```bash
php artisan vendor:publish --provider="Esterox\Firebase\ServiceProvider\FirebaseServiceProvider" --tag=config
```


# To use in another project
### Add the following snippet to the composer.json file
```
"repositories": [
    {
        "type": "vcs",
        "url": "https://github.com/davitgrigoryandeveloper/laravel-firebase"
    }
],

"require": {
    "esterox/laravel-firebase": "dev-main"
},
```

### After all that write the following code in terminal
```bash
composer install
```
### OR
```bash
composer update
```
    