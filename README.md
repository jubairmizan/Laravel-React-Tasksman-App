# Laravel-React-Tasksman-App

Task management app, will consist of two main components: tasks and projects. Let’s break each of these component down.

**Tasks:** A task is an item that needs to be done by a user and usually consists of a brief and concise title of what needs to be done to complete that task. Tasks also need to indicate whether they have been completed or not. Finally, a task is usually associated with a project that contains similar or related tasks.

**Projects:** projects group related tasks together and usually have a descriptive name, and a description associated with them. We also need to be able to indicate whether or not a project is completed.

**Step 1**

Clone the `repository`

**Step 2**

After clone run `composer update` by your cmd

**Step 3**

run `npm install` by cmd

Duplicate .env.example and rename it .env

Then Run 

`php artisan key:generate`

**Prerequisites**

Be sure to fill in your database details in your .env file before running the migrations :

`php artisan migrate`

**That's it , You are ready to go!**

**Built With**

[Laravel](http://laravel.com/)-The PHP Framework For Web Artisans


[React](https://reactjs.org/) - A JavaScript library for building user interfaces
