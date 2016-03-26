# Display Account

This app takes a `STITCH_TOKEN` and displays account info at `/`.

A .env file is needed to run this application. .env is specifically ignored by version control but a .env.example file is provided. Scripts may be created in the future to facilitate configuration.

## Install

```
cd share
cp .env.example .env
composer install
./artisan                   # should show available artisan commands
./artisan key:generate      # should successfully set an application key in .env
```
