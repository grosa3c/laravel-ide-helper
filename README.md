Custom Implementation.

Per aggiungerlo ad un nuovo progetto (composer):

"repositories": [
        {
            "type": "vcs",
            "url": "https://github.com/grosa3c/laravel-ide-helper"
        }
    ]

Per aggiungerlo ad un nuovo progetto:
composer require --dev barryvdh/laravel-ide-helper:dev-master

Per aggiornarlo in caso di modifiche successiva all'installazione:
composer update barryvdh/laravel-ide-helper

Per scrivere modelli:
php artisan ide-helper:models -W