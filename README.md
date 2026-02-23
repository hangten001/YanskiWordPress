# WordPress Theme - YanskiWordPress

![Simple CI](https://github.com/hangten001/YanskiWordPress/actions/workflows/ci.yml/badge.svg?branch=main)

Custom WordPress theme built from scratch.

## 🚀 Features

- Custom theme structure
- Clean PHP architecture
- Organized template files
- CI workflow using GitHub Actions
- Automatic PHP syntax validation

## 🛠 Tech Stack

- PHP
- WordPress
- Git
- GitHub Actions (CI)

## 🔄 CI Pipeline

Every push to `main` triggers:

- PHP 8.2 setup
- Automatic syntax check for all PHP files

# set up file --

    .gitignore
        wp-admin/
        wp-includes/
        wp-content/uploads/
        wp-content/plugins/
    index.php
        get_header(), get_footer()
    style.css
    function.php
    header.php
        wp_head(), body_class(), wp_body_open()
    footer.php
        wp_footer()
