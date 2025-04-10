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
│   │── front/
│   │   
│   ├── head.blade.php
│   ├── settings-heading.blade.php

```

### Explanation of Directories

#### 1. `components/layouts/`
Livewire layouts for Back and Front Office layouts

#### 2. `pages/`
Livewire Back Office pages

#### 3. `partials/`
Livewire Back Office Partials

#### 4. `components/layouts/front/`
Livewire Front Office layouts

#### 5. `front/`
Livewire Front Office Pages

#### 6. `partials/front/`
Livewire Front Office Partials

