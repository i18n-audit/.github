# i18n Audit (👀![Organization Views](https://komarev.com/ghpvc/?username=i18n-audit\&color=blue))

Multi-language translation audit toolkit — detect missing, unused, and inconsistent translation keys across your codebase.

---

## 🚀 Packages

| Language | Package | Repo | Description | Status | ⭐ Stars | 📥 Downloads |
|----------|---------|------|-------------|--------|---------|-------------|
| Rust | `i18n-audit` | [i18n-audit-rust](https://github.com/i18n-audit/i18n-audit-rust) | CLI tool to audit translation files in Rust projects | Stable | ![GitHub stars](https://img.shields.io/github/stars/i18n-audit/i18n-audit-rust?style=flat) | ![Crates.io downloads](https://img.shields.io/crates/d/i18n-audit?label=crates.io) |
| JS/TS | `@i18n-audit/javascript` | [i18n-audit-javascript](https://github.com/i18n-audit/i18n-audit-javascript) | Audit translation keys in JavaScript/TypeScript projects | Beta | ![GitHub stars](https://img.shields.io/github/stars/i18n-audit/i18n-audit-javascript?style=flat) | ![npm downloads](https://img.shields.io/npm/dt/@i18n-audit/javascript?label=npm) |
| PHP | `i18n-audit/php` | [i18n-audit-php](https://github.com/i18n-audit/i18n-audit-php) | Audit translation files in PHP projects | Stable | ![GitHub stars](https://img.shields.io/github/stars/i18n-audit/i18n-audit-php?style=flat) | ![Packagist downloads](https://img.shields.io/packagist/dt/i18n-audit/php?label=packagist) |
| PHP/Laravel | `i18n-audit/laravel` | [i18n-audit-laravel](https://github.com/i18n-audit/i18n-audit-laravel) | Laravel package to audit translation usage, missing keys, and unused keys | Stable | ![GitHub stars](https://img.shields.io/github/stars/i18n-audit/i18n-audit-laravel?style=flat) | ![Packagist downloads](https://img.shields.io/packagist/dt/i18n-audit/laravel?label=packagist) |
| JS/TS | — | [i18n-demo](https://github.com/i18n-audit/i18n-demo) | Demo app showcasing i18n-audit integrations across frameworks | Demo | ![GitHub stars](https://img.shields.io/github/stars/i18n-audit/i18n-demo?style=flat) | — |

---

## 📦 Installation

### Rust
```sh
cargo install i18n-audit
```

### JavaScript
```sh
npm install @i18n-audit/javascript
```

### PHP
```sh
composer require i18n-audit/php
```

### Laravel
```sh
composer require i18n-audit/laravel
```

Then publish the config:
```sh
php artisan vendor:publish --provider="I18nAudit\Laravel\ServiceProvider"
```

---

## 📚 Documentation

- Getting Started
- Configuration
- CLI Usage
- CI Integration

---

## 🌍 Supported Ecosystems

- PHP
- Laravel
- React
- Vue
- Next
- Rust
