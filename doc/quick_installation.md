# Quick installation

## Download from GitHub

```bash
git clone https://github.com/oktatapi/shopping_list_api.git
cd shopping_list_api
```

```bash
composer install
```


## Make .env file

On Linuxon:

```bash
cp .env.example .env
```

On Windows:

```cmd
copy .env.example .env
```

## Application key

```bash
php artisan key:generate
```

## Database

```bash
php artisan migrate
```

## Start server

```bash
php artisan serve
```
