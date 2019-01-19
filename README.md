# laravel-homestead-setup
Laravel homestead setup


composer create-project --prefer-dist laravel/laravel blog

composer require laravel/homestead --dev

ssh-keygen -t rsa -C "youremail"

vagrant up

copy domain from Homestead.YAML to /etc/hosts
