# Steps 
## 1. Configuration
- cp .env.example .env
- composer update
- .env change localhost to localhost:8000
- Download firebase crentendtials from comptes de services(web app dans la console firebase)
 et remplace it
 - php artisan generate:key
## 2. Add vue js to you project
 - php artisan ui vue
 - npm i
 - npm run dev
 - Add :
 <script src="{{ mix('/js/app.js') }}"></script>
 - add Id='app' : 
 <div id="app">
   <example-component></example-component>
</div>



#### Doc official steven stec
