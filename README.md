<h1 align="center">Radio Gaza</h1>

<p align="center">
  <strong>Web platform and content-management system for a Palestinian radio station.</strong><br>
  Live audio streaming, news, programs, and listener engagement — backed by a full Arabic admin panel and a Firebase-powered mobile API.
</p>

<p align="center">
  <a href="https://radiogaza.com/"><strong>Production → radiogaza.com</strong></a>
  &nbsp;·&nbsp;
  <a href="https://test.radiogaza.com/">Staging → test.radiogaza.com</a>
</p>

---

## What it is

Radio Gaza is a full-stack Laravel application that powers the station's public website, admin operations, and companion mobile app. It is the editorial and operational hub the team uses to publish news, manage on-air content, push notifications to listeners, and keep the live broadcast running on the public web player.

## Features

### Public site
- Live audio stream player
- News articles with categories and sub-categories
- Banners and ad placements
- Static pages (about, terms, privacy, contact)
- FAQ section
- SEO-optimized routing and metadata
- Fully Arabic UI with RTL layout

### Admin panel
- Role-based access control (admins, editors, contributors)
- Content management — news, categories, banners, footer sections, static pages
- User and contact management
- Push notifications to mobile app users
- Statistics dashboard
- Excel exports and PDF prints for every major resource
- Activity log — every administrative action recorded with user, data, and timestamp

### Mobile API
- Laravel Passport OAuth2 authentication
- Firebase Cloud Messaging integration for push notifications
- App walkthroughs / onboarding screens managed from admin
- Endpoints for programs, news, live stream, and notifications

## Tech stack

**Backend** — PHP 8.2, Laravel 11, MySQL, Laravel Passport, Firebase (Kreait SDK), Intervention Image, Imagick
**Frontend (admin + site)** — Blade, Bootstrap, jQuery, Yajra Datatables
**Exports & PDFs** — Maatwebsite Excel, niklasravnsborg/laravel-pdf
**Tooling** — ArcaneDev Log Viewer, Laravel UI, Guzzle

## Status

Production. Maintained.

## About

Built and maintained by [@saberaldda](https://github.com/saberaldda).
For inquiries: saberaldda@gmail.com
