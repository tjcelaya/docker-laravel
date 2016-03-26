# Running these projects

## 1. Display Account

Run the following:
```
docker run -p 8000:80 -p 443:443 -v $(pwd)/share:/share --restart=always --name=account_displayer mtmacdonald/docker-laravel:1.4.0
```

# Adding your own

Throw your project folder in here and do `ln -snf share $YOUR_PROJECT_FOLDER`.
