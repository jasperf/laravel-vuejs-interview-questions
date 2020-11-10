# Laravel Vue JS Interview Questions
Laravel Developer Interview Questions to be used for interviewing potential Laravel Developers. VueJs related questions will also be included here for frontend work.


## General

1. What is your Laravel experience like? Is Laravel populair in x? Why so?
2. Describe a typical working day in your life. Do you work at home or elsewhere? What hours do you keep?
3. Why did you become a developer?

## Tech in Detail
1. What type of problems did you have working with Laravel or VueJS projects and how did you solve them?
2. How is Type Hinting used in Laravel?
3. What is Laravel Eloquent? Why is it nice to have for development?
4. What is the Laravel Service Container for? Give an example of its usefulness in an ecommerce environment.
5. What are Laravel Facades? Why should we use them? How did you use one last time around?
6.  What are Laravel Service Providers used for? Give an example in one of your projects?
7.  Name 5 Laravel Packages you have used the most and can heartily recommend.
8.  Database Migrations - What is so useful about them?
9.  Axios Errors - How do you debug them? What tools do you use for it?
10.  How is the Vue Js Browser support these days?
11. How do you perform testing in vuejs & Laravel?
12. What is your favorite feature of Laravel?
13. Have you used VueX in projects? Examples? When to use Event Buses and when to use VueX?
14. A project is using Laravel 6 and with LaravelShift could move to 7. Should it?


## Code Questions

1. I've already created a database table that I want to use with Laravel's ORM. How would I setup a class to do that?
2. Laravel comes with a PHP CLI called artisan. What is your favorite artisan command?
3. Give us an example of Vue *created()* and *mounted()* as you applied it in your last app. Do explain why this was set up this way.
4. Form Validation - How do I validate a zip Dutch code / email address / password w 15 chars, at least one lower, upper case letter, one special char and one number?
5.  SEO issues in SPA - How do you deal with this with Vue routing to register users with Google Analytics?
6.  When registering a tablet or mobile as a quest to your application what can you find out about the device with server side code and what with frontend code? What plugins and or packages do you recommend?
7.   Vue Key Modifier - give an example of one used in one of your projects
```
Route::group(['prefix' => 'dashboard', 'middleware' => ['auth', 'subcheck'], 'namespace' => 'Dashboard'], function () {
```

do for routes included in that code part in *web.php*? What is a prefix for? What is a group in this case?

8. You need to add add a new private checkbox (private or not) to the dashboard for a site. Checked site will be private. How would you go about adding this new option to the dashboard and storing it to an existing database table?

9. Standard Vue JS Issue:

```
[vue/no-use-v-if-with-v-for]
The 'textModules' variable inside 'v-for' directive should be replaced with a computed property that returns filtered array instead. You should not mix 'v-for' with 'v-if'.
```

Explain in plain English what this issue is and how you would resolve this

## Sources

* https://www.onlineinterviewquestions.com/laravel-interview-questions/
* https://codingcompiler.com/laravel-interview-questions-answers/
* https://codetiburon.com/how-to-choose-the-best-laravel-developers/
* https://github.com/sudheerj/vuejs-interview-questions
* https://gist.github.com/lukevers/32566dd2c7e6b02fa0d2
* https://gist.github.com/jamespfarrell/f09cb120ee87f8030b7f3cdcd5b710a5
* https://github.com/smart48/vuejs-interview-questions
