# CyberMath — Gamified Mathematics Learning Platform

![PHP](https://img.shields.io/badge/PHP-8.x-777BB4) ![MySQL](https://img.shields.io/badge/MySQL%2FMariaDB-database-4479A1)

**CyberMath** is a web platform for practicing mathematics, built as a **diploma project by a team of three students**.

## What the platform does
- User registration and authentication
- Mathematics exercises and learning content in Estonian and Russian
- Progress tracking and leaderboards
- Administration and moderation features
- PDF functionality using PHP libraries

## Technology
PHP, MySQL/MariaDB, HTML, CSS, JavaScript. Composer dependencies include `vlucas/phpdotenv`, `setasign/fpdf`, and `tecnickcom/tcpdf`.

## My contribution
I contributed to **both frontend and backend development**, alongside another student who also developed code. A third teammate contributed design concepts and feature ideas. CyberMath was a **collaborative diploma project**.

## How to run locally
> **Source code has not been uploaded here yet.** A cleaned, upload-ready source archive has been prepared separately; the following steps apply after that archive is published.

1. Install PHP 8.x (including PDO MySQL), MySQL/MariaDB and Composer.
2. Run `composer install` in the project directory.
3. Create an empty local database named `cybermath`.
4. Import `database/schema.sql` (schema only, with **no real user records**).
5. Copy `.env.example` to `.env` and fill in local database credentials.
6. Serve the project with a local PHP-compatible web server, such as `php -S localhost:8000`, and open `http://localhost:8000`.
7. Register a test account and explore the learning pages.

These steps were inferred from the source structure and **not yet verified by running a fresh installation**.

## Security and publishing status
- Original `.env` and any passwords or API keys are excluded from the prepared archive.
- A database **schema-only** export replaces the original SQL dump, which contained user records.
- Vendor dependencies, local IDE files and two password-hash helper scripts were excluded.
- Source is awaiting final manual transfer and teammate publication review.

## Credits
Developed by three vocational school students as a diploma project. Teammates may be named with their permission.
