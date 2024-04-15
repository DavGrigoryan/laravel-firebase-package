- php: 8.2
# publish config file
```bash
php artisan vendor:publish --provider="Esterox\Firebase\ServiceProvider\FirebaseServiceProvider" --tag=config
```


use another project composer.json
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