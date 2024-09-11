# Laravel Design Patterns

This document outlines the design patterns that are used internally by the Laravel framework and those that are most popular in the Laravel community.

## Creational Patterns

1. **Singleton**
   - **Used in**: Laravel's service container for managing single instances of classes.

2. **Factory Method**
   - **Used in**: Model factories for generating test data and creating instances.

## Structural Patterns

1. **Facade**
   - **Used in**: Provides a static interface to classes in the service container, such as `Cache`, `DB`, and `Route`.

2. **Decorator**
   - **Used in**: Middleware for enhancing request and response functionality.

3. **Builder**
   - **Used in**: Laravel’s Query Builder for constructing SQL queries in a fluent and flexible manner.

## Behavioral Patterns

1. **Observer**
   - **Used in**: Eloquent models to handle events like `created`, `updated`, and `deleted`.

2. **Strategy**
   - **Used in**: Components like authentication and validation where different strategies can be selected at runtime.

3. **Command**
   - **Used in**: Artisan console commands for handling command-line operations.

4. **Chain of Responsibility**
   - **Used in**: Middleware to handle request processing in a chain, allowing modifications at different stages.
