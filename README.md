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

Per aggiornarlo in caso di modifiche successive all'installazione:
composer update barryvdh/laravel-ide-helper

Per scrivere modelli:
php artisan ide-helper:models -W

Per scrivere singolo modello:
php artisan ide-helper:models "App\Models\Post" -W