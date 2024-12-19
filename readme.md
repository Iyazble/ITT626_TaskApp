# laravel-tasks

### Laravel-Tasks is a Complete Build of Laravel 7 with Individual User Task Lists

##### COMPLETE WORKING BUILD - R2R.

Laravel 7 with user authentication, password recovery, and individual user tasks lists. This also makes full use of Controllers for the routes, templates for the views, and makes use of middleware for routing.  Uses laravel ORM modeling and has CRUD (Create Read Update Delete) functionality for all tasks.

This has robust verbose examples using Laravel best practices.  The task list is a build out of https://laravel.com/docs/7/quickstart.

Super easy setup, can be done in 5 minutes or less.

###### A [Laravel](http://laravel.com/) 7.x with minimal [Bootstrap](http://getbootstrap.com) 3.5.x project.
| Laravel-Tasks Features  |
| :------------ |
|Built on [Laravel](http://laravel.com/) 5.2|
|Dependencies are managed with [COMPOSER](https://getcomposer.org/)|
|CRUD (Create, Read, Update, Delete) Tasks Management|
|User Registration with password reset via Email|
|User Login with remember password|

### Quick Project Setup
###### (Not including the dev environment)
1. Run `sudo git clone https://github.com/jeremykenedy/laravel-tasks.git laravel-tasks`
2. Create a MySQL database for the project
    * ```mysql -u root -p```, if using Vagrant: ```mysql -u homestead -psecret```
    * ```create database laravelTasks;```
    * ```\q```
3. From the projects root run `cp .env.example .env`
4. Configure your `.env`
5. Run `sudo composer update` from the projects root folder
6. From the projects root folder run `sudo chmod -R 755 ../laravel-tasks`
7. From the projects root folder run `php artisan key:generate`
8. From the projects root folder run `php artisan migrate`
9. From the projects root folder run `composer dump-autoload`

And thats it with the caveat of setting up and configuring your development environemnt. I recommend [VAGRANT](https://docs.vagrantup.com/v2/getting-started/) or the Laravel configured instance of Vagrant called [HOMESTEAD](http://laravel.com/docs/7/homestead).

#### View the Project in Browser
1. From the projects root folder run `php artisan serve`
2. Open your web browser and go to `http://localhost`


### Laravel-Tasks Authentication URL's (routes)
* ```/```
* ```/auth/login```
* ```/auth/logout```
* ```/auth/register```
* ```/password/reset```

### Laravel-Tasks URL's (routes)
* ```/home```
* ```/tasks```
* ```/tasks/create```
* ```/tasks/{id}/edit```
* ```/tasks-all```
* ```/tasks-complete```
* ```/tasks-incomplete```

---

## [Laravel](http://laravel.com/) PHP Framework

[![Build Status](https://travis-ci.org/laravel/framework.png)](https://travis-ci.org/laravel/framework) [![Latest Stable Version](https://poser.pugx.org/laravel/framework/version.png)](https://packagist.org/packages/laravel/framework) [![Total Downloads](https://poser.pugx.org/laravel/framework/d/total.png)](https://packagist.org/packages/laravel/framework) [![License](https://poser.pugx.org/laravel/framework/license.svg)](https://packagist.org/packages/laravel/framework)

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable, creative experience to be truly fulfilling. Laravel attempts to take the pain out of development by easing common tasks used in the majority of web projects, such as authentication, routing, sessions, and caching.

Laravel aims to make the development process a pleasing one for the developer without sacrificing application functionality. Happy developers make the best code. To this end, we've attempted to combine the very best of what we have seen in other web frameworks, including frameworks implemented in other languages, such as Ruby on Rails, ASP.NET MVC, and Sinatra.

Laravel is accessible, yet powerful, providing powerful tools needed for large, robust applications. A superb inversion of control container, expressive migration system, and tightly integrated unit testing support give you the tools you need to build any application with which you are tasked.

### Official Laravel Documentation

Documentation for the entire framework can be found on the [Laravel website](http://laravel.com/docs).

### Contributing To Laravel

**All Laravel Framework related issues and pull requests should be filed on the [laravel/framework](http://github.com/laravel/framework) repository.**

### Laravel License

The Laravel framework is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT)

## [Bootstrap](http://getbootstrap.com) Front-End Framework

[![Build Status](https://img.shields.io/travis/twbs/bootstrap/master.svg)](https://travis-ci.org/twbs/bootstrap) ![Bower version](https://img.shields.io/bower/v/bootstrap.svg) [![npm version](https://img.shields.io/npm/v/bootstrap.svg)](https://www.npmjs.com/package/bootstrap) [![devDependency Status](https://img.shields.io/david/dev/twbs/bootstrap.svg)](https://david-dm.org/twbs/bootstrap#info=devDependencies) [![License](https://poser.pugx.org/laravel/framework/license.svg)](https://packagist.org/packages/laravel/framework)

Bootstrap is a sleek, intuitive, and powerful front-end framework for faster and easier web development, created by [Mark Otto](https://twitter.com/mdo) and [Jacob Thornton](https://twitter.com/fat), and maintained by the [core team](https://github.com/orgs/twbs/people) with the massive support and involvement of the community.

[Bootstrap](http://getbootstrap.com)'s documentation, included in this repo in the root directory, is built with [Jekyll](http://jekyllrb.com) and publicly hosted on GitHub Pages at [<http://getbootstrap.com>](http://getbootstrap.com).

---

