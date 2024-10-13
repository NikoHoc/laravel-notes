# laravel-notes
My own personal laravel notes and command


Buka terminal, pada path "C:\Apps\laragon\www"
##Buat project Laravel baru
composer create-project laravel/laravel:^10.0 laraveldemo

##Masuk ke folder laraveldemo
cd laraveldemo

##Tambahkan git ke folder laraveldemo
git init
git remote add origin https://github.com/mkvem/laravelwithtailwind.git
git remote -v
##Untuk menambahkan seluruh isi folder project laraveldemo
git add . 
git commit

##Push ke branch main
git push origin master
