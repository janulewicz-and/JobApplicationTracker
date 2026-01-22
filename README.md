Job Application Tracker

A modern job application tracking system built with Vue 3.
Manage your job search, track application statuses, and analyze your progress in one place.

📌 Overview

Job Application Tracker is a single-page application that helps you organize and track your job applications.

With this app you can:

Store all your job applications

Track application statuses

Analyze your job search progress

Search, filter and sort applications

Persist data locally

This project is built as a portfolio-ready frontend application following real-world architecture and best practices.

🚀 Features

Full CRUD for job applications

Status management: Wishlist, Applied, Interview, Offer, Rejected

Search by company and position

Filter by status

Sorting by date, company and status

Dashboard with statistics

LocalStorage persistence

Scalable and clean architecture

🛠 Tech Stack

Vue 3 (Composition API)

Vite

Pinia (state management)

Vue Router

LocalStorage

ESLint + Prettier

📂 Application Model
Application {
id: string
company: string
position: string
link?: string
status: 'wishlist' | 'applied' | 'interview' | 'offer' | 'rejected'
createdAt: string
updatedAt?: string
salaryMin?: number
salaryMax?: number
location?: string
notes?: string
}

⚙️ Project Setup
Install dependencies
npm install

Run development server
npm run dev

Build for production
npm run build

🎯 Project Goals

Demonstrate clean frontend architecture

Showcase state management with Pinia

Implement real-world CRUD workflows

Follow scalable project structure

Apply modern Vue 3 best practices

📦 Planned Improvements

API integration (Firebase or REST)

Authentication

Cloud sync

Charts & analytics

Export to CSV

🌐 Demo

Coming soon...

📄 License

MIT
