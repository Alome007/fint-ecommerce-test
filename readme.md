# Building an E-commerce platform with Laravel and Vue
This is demo application contains the Code base for [FINT.NG Developer Role Test](http://fint.ng) . 

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites
What things you need to install the software.

* Git.
* PHP.
* Composer.
* Laravel CLI.
* A webserver like [XAMPP](https://www.apachefriends.org/download.html).
* A Node Package Manager ( npm or yarn ).

### Install
Clone the git repository on your computer

```$ https://github.com/Alome007/fint-ecommerce-test/```


You can also download the entire repository as a zip file and unpack in on your computer if you do not have git

After cloning the application, you need to install it's dependencies. 

```
$ cd fint-ecommerce-test
$ composer install
```


### Setup
- When you are done with installation, copy the `.env.example` file to `.env`

  ```$ cp .env.example .env```


- Generate the application key

  ```$ php artisan key:generate```


- Add your database credentials to the necessary `env` fields

- Migrate the application

  ```$ php artisan migrate```

- Install laravel passport

  ```$ php artisan passport:install```

- Seed Database

  ```$ php artisan db:seed```


- Install node modules

  ```$ npm install```


### Run the application

  ```$ php artisan serve```

## Screenshot 
<img src="https://github.com/Alome007/fint-ecommerce-test/blob/main/fint1.PNG" alt="s2" width="auto" height="auto"/> &nbsp;&nbsp;
<img src="https://github.com/Alome007/fint-ecommerce-test/blob/main/fint2.PNG" alt="s2" width="auto" height="auto"/> &nbsp;&nbsp;

   
    
    
## Built With
* [Laravel](https://laravel.com) - The PHP framework for building the API endpoints needed for the application
* [Vue](https://vuejs.org) - The Progressive JavaScript Framework for building interactive interfaces

## Acknowledgments
* [Laravel](https://laravel.com) - The excellent documentation explaining how to get started with Laravel and Laravel Passport made it easy to provide a step by step guide for beginners to follow the application
* [Vue](https://vuejs.org) - Concise documentation 
* [Stackoverflow](https://stackoverflow.com/questions/tagged/vue.js?tab=Newest) - Vue JS Related Tagss
