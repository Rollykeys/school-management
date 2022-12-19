
# School Management System

```
\Frontend ~ this is where next application is installed
```

### Installation
Install <a href="https://www.apachefriends.org/download.html"> xampp </a> and <a href="https://getcomposer.org/">composer</a> 

After cloning repo

```
composer update && composer install
cp .example.env .env
php artisan serve
localhost:8000
```
```
cd frontend
cp .example.env .env.local
npm install && npm run dev
localhost:3000
```
### dependances

```
"dependencies": {
    "@headlessui/react": "^1.4.2",
    "axios": "^0.21.1",
    "next": "^13.0.3",
    "react": "^18.2.0",
    "react-dom": "^18.2.0",
    "swr": "^1.3.0"
  },
```
### routes
```
php artisan route:list
```
```
 GET|HEAD   / ........................................................................................ 
  POST       _ignition/execute-solution ignition.executeSolution › Spatie\LaravelIgnition › ExecuteSol…
  GET|HEAD   _ignition/health-check ignition.healthCheck › Spatie\LaravelIgnition › HealthCheckControl…
  POST       _ignition/update-config ignition.updateConfig › Spatie\LaravelIgnition › UpdateConfigCont…
  GET|HEAD   api/user ................................................................................. 
  POST       email/verification-notification verification.send › Auth\EmailVerificationNotificationCon…
  POST       forgot-password .................. password.email › Auth\PasswordResetLinkController@store
  POST       login .................................. login › Auth\AuthenticatedSessionController@store
  POST       logout .............................. logout › Auth\AuthenticatedSessionController@destroy
  POST       register .................................. register › Auth\RegisteredUserController@store
  POST       reset-password ......................... password.store › Auth\NewPasswordController@store
  GET|HEAD   sanctum/csrf-cookie .... sanctum.csrf-cookie › Laravel\Sanctum › CsrfCookieController@show
  GET|HEAD   verify-email/{id}/{hash} ....... verification.verify › Auth\VerifyEmailController@__invoke                   
```
