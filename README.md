**!! Please note the following steps so that you can implement this project !!**

**1.  Clone Repository**

      git clone https://github.com/iostream-code/react-laravel-10-api.git

#SERVER-SIDE (Laravel 10)

**2.  Go to the laravel-10-api**

      cd laravel-10-api
      
**3.  Generate key App**

      php artisan key:generate
      
**4.  Setup Your database in file ./env**

      Just customize the following lines 
      
        DB_DATABASE={Yout Database Name}
        DB_USERNAME={Your Database Username}
        DB_PASSWORD={Your Database Password}
        
**5.  Database Migration**

      php artisan migrate or php artisan migrate:fresh
      
**6.  Link the storage**

      php artisan storage:link

#CLIENT-SIDE

**7.  Enter the react-js-crud folder**

      cd ..
      cd react-js-crud

**8.  Install node_modules**

      npm i or npm install

**9.  Install the following package**

      npm i react-router-dom axios
