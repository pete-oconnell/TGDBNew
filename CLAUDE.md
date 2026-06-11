## Project Overview
This is a new project to replace the old defunt code on thegamesdb.net

## Tech Stack
    - PHP 8.5 / Laravel 
    - Database: MySQL
    - Testing: PHPUnit (php artisan test)
    - Frontend: Blade

    ## Directory Structure
    app/Http/Controllers/  — Keep controllers thin
    app/Models/            — Eloquent models
    app/Services/          — Business logic goes here
    database/migrations/   — Database migrations
    tests/Feature/         — Feature tests
    tests/Unit/            — Unit tests
    routes/api.php         — API routes
    routes/web.php         — Web routes

    ## Coding Conventions
    - PSR-12 code style
    - Business logic in Service classes, not controllers
    - Every new Model needs a Factory
    - New Service methods need a unit test

    ## IMPORTANT RESTRICTIONS
    - NEVER run php artisan migrate
    - NEVER modify .env files
    - If a migration is needed, create it but do not run it
    - If a decision is made for technology, ensure that technically it is compatible with other elements
    - Keep CLAUDE.md updated with important information
