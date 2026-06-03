<p align="center">
  <img src="icon-512.png" alt="DScore Logo" width="96" height="96">
</p>

<h1 align="center">DScore</h1>

<p align="center">
  A lightweight local-first Progressive Web App for daily action scoring and simple productivity tracking.
</p>

## Overview

DScore is a small Progressive Web App designed to track daily actions and summarize them with a simple score-based system. Each action is assigned a duration and a category based on the Eisenhower matrix: important/urgent, important/not urgent, not important/urgent, or not important/not urgent.

The app calculates daily scores, category-level scores, weekly summaries, and simple visual statistics. It is intentionally minimal and local-first: the goal is to provide a fast, installable, offline-capable utility without requiring a backend, user accounts, or cloud infrastructure.

## Features

* Add and manage daily records
* Add, edit, and delete actions for each day
* Score actions using Eisenhower-style categories
* Support decimal durations such as `0.5`, `1.25`, or `2.5` hours
* View daily total and category-level scores
* Add short daily notes
* View score trends and weekly summaries
* Export and import JSON backups
* Installable as a Progressive Web App
* Offline-capable after the first successful load
* Stores data locally on the device

## Design Choice

DScore is built as a static local-first PWA rather than a full backend application. For this type of compact tracking tool, a server-side database, authentication system, and deployment pipeline would add unnecessary complexity.

The app uses browser local storage for data persistence and JSON export/import for backup. This keeps the project simple, private, and easy to run on mobile devices.

## Technology

* HTML
* CSS
* Vanilla JavaScript
* localStorage
* Service Worker
* Progressive Web App manifest

## Project Scope

This is a compact utility project, not a large-scale productivity platform. The focus is on quick usability, offline access, simple scoring logic, and clean mobile-first interaction.

## License

No license has been selected yet.
