Create migration table
❯ php artisan make:migration create_categories_table

Create Migration to send to database
❯ php artisan migrateif you make mistake in the command above you can undo it> php artisan migrate:rollback


Create a new Model Command(category is the model name)
❯ php artisan make:model Category

Create a new Controller
❯ php artisan make:controller CategoryController

Create na new Component
❯ php artisan make:component AppWebLayout

To clear route cache
❯ php artisan route:cache