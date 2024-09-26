<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About
This project focuses on implementing user API authentication, which can be integrated into both web and mobile applications for secure communication. The primary goal is to authenticate users and manage their access to various resources through APIs, allowing external systems (such as mobile apps or third-party web services) to interact with the core application.

To achieve this, Laravel Sanctum is used as the API authentication package. Sanctum provides a lightweight authentication system for Single Page Applications (SPAs), mobile applications, and simple token-based APIs. Here's how Sanctum fits into the project:

- Token-Based Authentication: Sanctum generates API tokens for users. These tokens allow authenticated requests to be made to the API without needing to re-enter credentials on every request. Each token can be assigned specific abilities, controlling which endpoints or actions the token is allowed to access.

- Session-Based Authentication: For SPAs, Sanctum uses Laravel's built-in session authentication, meaning users logged into the app can make requests to the API without using tokens.

- Security: Sanctum ensures that only authenticated users can access protected resources, providing a secure method of authentication across different platforms.

By integrating Sanctum, this project establishes a flexible and secure authentication mechanism that can be easily used by other applications or services to communicate with your API.
