Steps to follow:

- check laravel version : laravel -v
- jetstream will work on on laravel installer version >=4.0
- create new project - laravel new jetblog --jet
- choose appropriate option i.e. Livewire/inertia or application use team?
- run command : npm install && npm run dev 
- after that create DB and set config in .env
- now run command: php artisan migrate
- change "APP_URL" in .env file too.
