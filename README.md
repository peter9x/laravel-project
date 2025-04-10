# laravel-project
Template for Start a new Laravel Project

## Laravel Views Folder Structure (with Livewire)

The `resources/views` directory in a Laravel project contains Blade templates that define the HTML structure of the application's frontend. When using Laravel with Livewire, additional directories and structures are introduced to handle dynamic components seamlessly.

### Folder Structure

```
resources/views/
│── components/
│   │── layouts/
│   │   ├── app/
│   │   │   ├── header.blade.php
│   │   │   ├── sidebar.blade.php
│   │   │ 
│   │   ├── auth/
│   │   │   ├── card.blade.php
│   │   │   ├── simple.blade.php
│   │   │   ├── split.blade.php
│   │   │ 
│   │   ├── front/
│   │   │   ├── simple.blade.php
│   │
│   │── settings/
│   │
│   ├── components...
│
│── front/
│   ├── index.blade.php
│
│── livewire/
│   │── auth/
│   │   ├── pages
│   │   
│   │── settings/
│       ├── pages
│
│── pages/
│   ├── dashboard.blade.php
│
│── partials/
│   ├── home.blade.php
│   ├── about.blade.php
│   ├── contact.blade.php
```

## Explanation of Directories

### 1. `components/layouts/front/`
Livewire layouts are stored under the `components.layouts.front` directory:
- `simple.blade.php`: A simple front-end layout.
- `master.blade.php`: A master template used for multiple pages.
