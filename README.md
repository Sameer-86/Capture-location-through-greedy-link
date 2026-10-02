# LocationShare — Laravel 12 Location Sharing System

A professional, privacy-first location-sharing web application built with **Laravel 12**.

Administrators can generate unique share links. Recipients open the link, grant browser location permission, and their precise coordinates are securely captured. Locations are viewable on an interactive map with CSV export.

> **Privacy First:** This application NEVER attempts to access GPS silently, bypass browser permissions, or track users without explicit consent.

---

## 📖 Table of Contents

1. [Features](#-features)
2. [Requirements](#-requirements)
3. [Installation](#-installation)
4. [Environment Setup](#-environment-setup)
5. [Database Setup](#-database-setup)
6. [Running the Application](#-running-the-application)
7. [Default Admin Credentials](#-default-admin-credentials)
8. [How It Works](#-how-it-works)
9. [HTTPS Requirement](#-https-requirement)
10. [Project Structure](#-project-structure)
11. [Security & Privacy](#-security--privacy)
12. [Testing Checklist](#-testing-checklist)
13. [Deployment](#-deployment)
14. [License](#-license)

---

## ✨ Features

### Admin Side
- ✅ Secure authentication (Laravel Breeze)
- ✅ Role-based access (admin/user)
- ✅ Generate unique location-sharing links
- ✅ Optional title, description, expiry date
- ✅ Enable/disable links anytime
- ✅ Dashboard with statistics
- ✅ Interactive Leaflet map (OpenStreetMap)
- ✅ View captured coordinates with accuracy
- ✅ Filter by link, permission status, date range
- ✅ Export location records to CSV
- ✅ Delete/deactivate links

### User Side
- ✅ Clean, responsive landing page
- ✅ Clear privacy notice before requesting location
- ✅ One-click location sharing (browser permission required)
- ✅ Friendly error messages (denied/timeout/unavailable)
- ✅ Success confirmation with summary
- ✅ Mobile-friendly UI (Android, iOS, tablets, desktop)

---

## 🛠 Requirements

- **PHP** ≥ 8.2
- **Composer** ≥ 2.x
- **Node.js** ≥ 18.x + npm
- **MySQL** ≥ 8.0 (or PostgreSQL/SQLite)
- **Modern browser** with Geolocation API support

---

## 🚀 Installation

### 1. Clone or extract the project

```bash
cd location-share