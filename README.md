# Laravel Design Patterns

This document outlines the design patterns used internally by the Laravel framework and popular in the Laravel community.

## Creational Patterns

- **Singleton**: Manages single instances in the service container.
- **Factory Method**: Creates instances via model factories.

## Structural Patterns

- **Facade**: Provides a static interface to service container classes.
- **Decorator**: Enhances request and response functionality via middleware.
- **Builder**: Constructs SQL queries using Laravel’s Query Builder.

## Behavioral Patterns

- **Observer**: Handles Eloquent model events like `created` and `updated`.
- **Strategy**: Implements varying strategies in authentication and validation.
- **Command**: Manages Artisan console commands.
- **Chain of Responsibility**: Processes requests through middleware chains.
