# SANAD

**SANAD** is a digital ledger application designed for small and medium-sized merchants to manage customers, debts, payments, and account balances in a simple and organized way.

The project consists of two main parts:

- **Frontend:** Flutter mobile application
- **Backend:** Laravel REST API

## Project Structure

```text
SANAD/
├── frontend/   → Flutter Application
├── backend/    → Laravel API
└── README.md
```

This repository uses **Git Submodules** to connect the frontend and backend repositories while keeping their original Git history and development workflow separate.

## Repositories

### Frontend
Flutter mobile application:

https://github.com/ni7170991-source/daftari-app

### Backend
Laravel backend API:

https://github.com/YasminAlNajjar/daftari-backend

## Main Features

- User authentication
- Customer management
- Debt and payment tracking
- Customer balance calculation
- Credit limit management
- Reports and financial summaries
- Notifications
- QR-based functionality
- Secure API communication between Flutter and Laravel

## Technologies

### Frontend
- Flutter
- Dart
- REST API Integration

### Backend
- Laravel
- PHP
- MySQL
- RESTful API

## Clone the Project

Because this repository uses Git Submodules, clone it using:

```bash
git clone --recurse-submodules YOUR_REPOSITORY_URL
```

If you already cloned the repository without the submodules, run:

```bash
git submodule update --init --recursive
```

## Update Submodules

To update the frontend and backend to their latest versions:

```bash
git submodule update --remote
```

Then commit the updated references:

```bash
git add .
git commit -m "Update submodules"
git push
```

## Project Goal

SANAD aims to provide merchants with a simple digital alternative to traditional paper-based debt ledgers, helping them organize customer accounts, track transactions, and reduce the risk of losing financial records.

## Status

The project is currently under development.

## Team

Developed as a collaborative software project with separate frontend and backend development workflows.
