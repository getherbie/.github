# Herbie CMS

> Create <u>small</u> but fully functional websites or blogs in no time — no database required 👌

[![Packagist downloads](https://img.shields.io/packagist/dt/getherbie/herbie.svg)](https://packagist.org/packages/getherbie/herbie)
[![Latest release](https://img.shields.io/github/release/getherbie/herbie/all.svg)](https://github.com/getherbie/herbie/releases)
[![PHP version](https://img.shields.io/packagist/php-v/getherbie/herbie.svg)](https://packagist.org/packages/getherbie/herbie)
[![License: BSD 3-Clause](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://github.com/getherbie/herbie/blob/3.x/LICENCE.md)

[⭐ GitHub](https://github.com/getherbie/herbie) ·
[📖 Documentation](https://herbie.tebe.ch) ·
[🚀 Live Demo](https://start.herbie.tebe.ch/) ·
[📦 Packagist](https://packagist.org/packages/getherbie/herbie)

Herbie is a lightweight flat-file CMS powered by **PHP, Twig** and human-readable text files like **Markdown, Textile** and **reStructuredText**. No database, no setup hassle — just write files and ship a site.

## Why Herbie?

- **No database** — content lives in plain text files, so you can version everything with Git.
- **Fast to start** — Docker or Composer, running in under a minute.
- **Easy to extend** — Twig templates, plugins, middlewares, event listeners and console commands.
- **Built on solid ground** — PSR standards, Composer, PHP 8.3–8.6, tested with Codeception, PHPStan and Deptrac.

## Quick start

~~~sh
docker run --rm -v "$PWD":/app composer create-project --ignore-platform-reqs getherbie/start-website mywebsite
cd mywebsite
docker compose up website
~~~

Open <http://localhost:8888>. No Docker? See the [full quick start](https://github.com/getherbie/herbie#quick-start).

## At a glance

<!-- TODO: Replace this placeholder URL with a real screenshot, e.g.
     https://raw.githubusercontent.com/getherbie/.github/main/profile/demo.png -->
![Herbie demo with one of its seven starter themes](https://raw.githubusercontent.com/getherbie/.github/main/profile/demo.png)

## Who is it for?

Developers and small teams who want a blog, portfolio, documentation site or landing page without the overhead of a database-driven CMS.

## Need help or want to contribute?

- [Open an issue](https://github.com/getherbie/herbie/issues)
- [Read the documentation](https://herbie.tebe.ch/doc)
- [Try the demo with 7 themes](https://start.herbie.tebe.ch/)
- [Star the repository](https://github.com/getherbie/herbie) ⭐
