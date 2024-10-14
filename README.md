# laravel-notes
My own personal laravel notes and command

### New project in laragon/www
```bash
composer create-project laravel/laravel laraveldemo
```

### Masuk ke folder laraveldemo
```bash
cd laraveldemo
code .
composer install
```

### Tambahkan git ke folder laraveldemo
```bash
git init
git remote add origin link_git
git remote -v

git add . 
git commit
git push origin master
```

### Install Tailwind
[Tailwind Install](https://tailwindcss.com/docs/guides/laravel )
Add app.css in head, app.js in body
```javascript
@vite('resources/css/app.css')
@vite(['resources/js/app.js'])
```
### Basic Layout
[Basic Layout Laravel](https://github.com/NikoHoc/laravel-journey/commit/bf6b3040268bd8409005da178fb2e5661fd1d045#diff-d811fc052d23063350b0f7e7303b595c7dbc51c81d1125bf099d079c1245f0b8)

### Model - Migration - Factory - Seeder
```bash
php artisan make:model Article -m -f -s
```

### Controller
```bash
php artisan make:controller ArticleController
```

### Migrrate - Seed
```
php artisan migrate:fresh --seed
```




