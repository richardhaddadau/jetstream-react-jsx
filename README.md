# Jetstream React JSX
[![Latest Version on NPM](https://img.shields.io/badge/npm-v0.1.0-orange)](https://www.npmjs.com/package/jetstream-react-jsx)

Replace Vue with React (JSX) in Jetstream for Laravel

## How To Use
Just as it states on the Jetstream website,
>#### Jetstream should only be installed into new Laravel applications.
>#### Attempting to install Jetstream into an existing Laravel application will result in unexpected behavior and issues.

With that out of the way, let's get into it.

---
### 1. Create a new laravel project and enter the directory 
```bash
composer create-project laravel/laravel new-app
cd new-app
```
---
### 2. Require and Install Jetstream
Remember to use the correct command based on your needs
- Standard (no teams):
```bash
composer require laravel/jetstream
php artisan jetstream:install inertia
```

- with Teams:
```bash
php artisan jetstream:install inertia --teams
```
---
### 3. Run Jetstream React JSX 
It's important that you run the corresponding command with the one you run in step 2.

- Standard (no teams):
```bash
npx jetstream-react-jsx@latest install
```

- with Teams:
```bash
npx jetstream-react-jsx@latest install --teams
```
---