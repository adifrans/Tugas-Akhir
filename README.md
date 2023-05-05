# Laravel 9 - Ecommerce application penjualan laptop
#1.Adi Frans Situmeang - 2055201113
#2.Rio wahyu al yahya - 2055201111
#3.Radhivan Ikhramullah - 2057201033
#4.Yudha Saputra - 2057201048

## Screenshots

![preview img](/Preview.png)

## Run Locally

Clone the project-akhir

```bash
  git clone https://adifrans@bitbucket.org/adifrans2201/tugas_akhir.git
```

Go to the project directory

```bash
  cd project-akhir
```

-   Copy .env and edit database credentials there

```bash
    composer install
```

```bash
    php artisan key:generate
```

```bash
    php artisan migrate:fresh --seed
```

```bash
    php artisan storage:link
```

#### Login

admin

-   email = admin@kelompok4.com
-   password = 123
