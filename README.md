# 🏨 AtomCMS – Modern Habbo Hotel CMS

A modern, community-driven CMS and management platform for Habbo-style hotel projects.

AtomCMS combines a modern Laravel-based web application with an HTML5/Nitro client and a powerful administration environment. The goal of the project is to provide developers with a clean, maintainable and extensible foundation for building and managing modern Habbo community projects.

> **Project Status:** Active Development 🚀

---

## ✨ About the Project

AtomCMS is being developed as a modern alternative to older Habbo CMS architectures.

The project focuses on:

- Modern web technologies
- Clean and maintainable code
- Performance
- Security
- Extensibility
- Modern administration tools
- HTML5/Nitro compatibility
- Developer-friendly architecture

Instead of relying on outdated CMS structures, the project uses a modern Laravel ecosystem while maintaining compatibility with the requirements of Habbo-style hotel servers.

---

## 🚀 Features

### 👤 User System

- User registration
- Authentication
- User profiles
- Account management
- Online status integration
- Player statistics
- User rankings
- Latest registrations

### 🏠 MePage

A modern player dashboard providing quick access to important account and hotel information.

Features include:

- Player information
- Hotel statistics
- News
- Account features
- Navigation to the hotel client
- Integrated staff tools for authorized users

### 📰 News System

Create and manage hotel news directly from the administration panel.

- News articles
- Editing and publishing
- Author management
- Structured news overview

### 🛡️ Housekeeping

AtomCMS includes a dedicated administration environment for hotel staff.

The Housekeeping provides management areas for:

- Dashboard
- Users
- Moderation
- News
- Events
- Logs
- Badges
- Shop
- Catalogue
- CMS
- Hotel
- Settings

Access to administrative functionality can be protected through permissions and additional staff security mechanisms.

---

## 🎮 Nitro HTML5 Client

The project is designed to work with a modern Nitro-based HTML5 client.

This allows the hotel client to run directly inside modern browsers without requiring Flash.

Supported infrastructure can include:

- Nitro HTML5
- Game assets
- Gamedata
- WebSocket connections
- Emulator integration
- Client configuration through the CMS

---

## 🧰 Technology Stack

AtomCMS uses modern technologies across the application:

| Technology | Purpose |
|---|---|
| PHP | Backend runtime |
| Laravel | Application framework |
| Livewire | Dynamic application components |
| Filament | Administration / Housekeeping |
| MariaDB / MySQL | Database |
| Nitro | HTML5 hotel client |
| Java | Emulator |
| IIS / Web Server | Production hosting |
| Cloudflare | CDN, caching and security |

---

## ⚡ Performance

Performance is an important focus of the project.

The architecture is designed to support optimizations such as:

- Application caching
- Database query optimization
- Asset caching
- CDN delivery
- Browser caching
- HTTP/2 and HTTP/3
- Brotli compression
- Optimized static assets
- Lazy loading
- Efficient Livewire components

Static client resources can be distributed through a CDN while authenticated and dynamic application content remains protected.

---

## 🔐 Security

Security is treated as a core part of the project.

Areas of focus include:

- Secure authentication
- CSRF protection
- Session security
- Permission-based administration
- Protected staff functionality
- Input validation
- Rate limiting
- Secure database interaction
- Security headers
- Dependency maintenance
- Vulnerability detection
- Cloudflare/WAF compatibility

Security improvements and code reviews are an ongoing part of development.

If you discover a security vulnerability, please report it responsibly instead of publishing exploit details publicly.

---

## 🏗️ Architecture

The project separates the main parts of the hotel infrastructure:

```text
User
 │
 ▼
Cloudflare / CDN
 │
 ▼
Web Server
 │
 ▼
Laravel / AtomCMS
 │
 ├── Authentication
 ├── MePage
 ├── News
 ├── Community
 ├── Housekeeping
 └── Nitro Configuration
 │
 ▼
Database
 │
 ▼
Hotel Emulator
 │
 ▼
Nitro HTML5 Client
```

This separation helps keep the project maintainable and allows individual components to evolve independently.

---

## 📋 Requirements

A typical installation requires:

- PHP
- Composer
- Laravel-compatible PHP extensions
- MariaDB or MySQL
- Node.js / NPM
- Web server such as IIS, Apache or Nginx
- Java for the hotel emulator
- Nitro-compatible client assets

Exact requirements may change while the project is under active development.

---

## 🛠️ Development Setup

Clone the repository:

```bash
git clone YOUR_REPOSITORY_URL
cd atomcms
```

Install PHP dependencies:

```bash
composer install
```

Install frontend dependencies:

```bash
npm install
```

Create the environment configuration:

```bash
cp .env.example .env
```

Generate the Laravel application key:

```bash
php artisan key:generate
```

Configure your database inside `.env`:

```env
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=hotel
DB_USERNAME=your_database_user
DB_PASSWORD=your_database_password
```

Run the database migrations:

```bash
php artisan migrate
```

Build frontend assets:

```bash
npm run build
```

Clear and optimize Laravel:

```bash
php artisan optimize:clear
```

For production deployments, additional server, HTTPS, caching and client configuration may be required.

---

## ⚠️ Environment Security

Never commit production credentials to GitHub.

The following information should always remain private:

```text
.env
Database passwords
API tokens
Cloudflare tokens
Application secrets
Private keys
Production credentials
```

Make sure `.env` is included in `.gitignore`.

Use `.env.example` to document required configuration variables without exposing real credentials.

---

## 🗺️ Project Goals

The long-term goal of AtomCMS is to provide a modern foundation for developers working within the Habbo retro ecosystem.

Planned and ongoing areas of development include:

- Improved Housekeeping
- Better moderation tools
- Performance improvements
- Security improvements
- Better Nitro integration
- Improved developer documentation
- Cleaner APIs and services
- Better permission management
- Improved CMS customization
- Automated testing
- Easier deployment

---

## 🤖 AI-Assisted Development

Modern development tools, including OpenAI Codex, may be used to assist with:

- Code review
- Refactoring
- Security analysis
- Test development
- Documentation
- Performance analysis
- Bug detection
- Code quality improvements

AI-generated changes should still be reviewed and tested before being deployed to production.

---

## 🤝 Contributing

Contributions are welcome.

You can help the project by:

- Reporting bugs
- Suggesting improvements
- Improving documentation
- Reviewing code
- Fixing issues
- Improving performance
- Improving security
- Adding tests
- Submitting pull requests

When contributing, please keep changes focused and document significant modifications.

---

## 🐛 Bug Reports

When reporting a bug, please include:

- What happened
- What you expected to happen
- Steps to reproduce the problem
- Relevant error messages
- PHP/Laravel version where relevant
- Browser information for frontend issues

Do **not** include passwords, API keys, session cookies or other private credentials.

---

## 📖 Documentation

Documentation will continue to grow alongside development.

The goal is to provide clear documentation for:

- Installation
- Configuration
- Nitro integration
- Emulator integration
- Housekeeping
- Development
- Deployment
- Security

---

## 💡 Why This Project?

Many projects in the Habbo retro ecosystem originate from older PHP architectures.

AtomCMS explores how a Habbo-style hotel platform can be built using a modern application stack while remaining familiar and extensible for the community.

The project also serves as a practical environment for experimenting with modern Laravel development, administration tooling, HTML5 client integration, performance optimization and application security.

---

## ⚖️ Disclaimer

This is an independent community project.

It is not affiliated with, endorsed by, sponsored by, or associated with Sulake Oy or the official Habbo service.

Habbo and related trademarks belong to their respective owners.

---

## 📜 License

Please refer to the `LICENSE` file for the licensing terms of this project.

---

## ⭐ Support the Project

If you find the project useful, you can support its development by:

- ⭐ Starring the repository
- 🐛 Reporting issues
- 💡 Suggesting improvements
- 🔧 Contributing code
- 📖 Improving documentation

Every contribution helps improve the project for the community.

---

**Built with ❤️ for developers and the Habbo retro community.**
