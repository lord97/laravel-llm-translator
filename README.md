# Laravel LLM Translator

Database-backed, cache-first translations for Laravel using a modular LLM driver system.

> This package does not observe models or intercept global Laravel behavior.
> You translate explicitly by calling helper functions.

## Features
- Cache → DB → LLM (only on misses)
- Stores translations in a `translations` table
- Context-aware translations (context affects cache/DB key via hash)
- Swappable translation drivers (default: Gemini)
- Laravel 10+, PHP 8.1+

## Status
🚧 In development.

## License
MIT

