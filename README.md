## HRP Laravel Basic Todo List 

## Installation

Currently, todo list is under development. There are no Installer. You have to use [Composer](https://getcomposer.org/), to install 0ez.

**1.** Clone or download repository to your web-folder.

**2.** In the root directory, type:

``` bash
composer install
```

**3.** Then, you have to set up your DB.

**4.** Rename `.env.example` file to `.env` in root folder.

**5.** Open it with your favorite text editor and set up your database credentials.


Database host

```
    DB_HOST=localhost
```

Database name

```
    DB_DATABASE=quickstart
```

Database user

```//This is Localhost

    DB_USERNAME=root
    
    DB_USERNAME=server_user
    
```

Database password

```//THis is Local Host
    
    DB_PASSWORD=
    
    //THis is Your Server Pass
    
    DB_PASSWORD=Server Pass
```

**6.** In command line, type 

``` bash
php artisan migrate
```


**7.** Point your webserver (Apache ot NGINX) to `/public` folder.


Done!

Now, you can login to administrative area. 

### Authorization Credentials

http://androidwebseo.com



## Contributor

Contributions are [Polas.habib](https://github.com/polashrp)


