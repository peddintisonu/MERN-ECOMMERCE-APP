# ShopFlow

ShopFlow is a modern, responsive full-stack e-commerce web application engineered with the MERN stack to deliver a seamless online shopping experience with secure transaction handling and robust session security.

## Overview
The platform provides a complete digital storefront featuring real-time inventory management, dynamic catalog navigation, and automated order fulfillment workflows. Built with a modular architecture, ShopFlow separates concerns between high-performance client state management and scalable backend API services.

## Key Features
* **Dynamic Product Catalog**: Multi-category filtering, instant search querying, and persistent pagination controls.
* **Persistent Cart Management**: Session-synced client shopping cart maintaining state across browser refreshes and device sessions.
* **Payment Gateway Integration**: Secure end-to-end checkout pipeline powered by the Stripe API, handling webhooks and instant payment verification.
* **Authentication & Authorization**: Google OAuth 2.0 onboarding combined with JSON Web Token (JWT) refresh token rotation and role-based route guards.
* **Order Tracking & Admin Dashboard**: Dedicated portal for order status updates, transactional logging, and customer management.

## Tech Stack
* **Frontend**: React.js, Vite, Tailwind CSS, Axios, Lucide React
* **Backend**: Node.js, Express.js, RESTful APIs
* **Database**: MongoDB (Mongoose ODM)
* **Authentication**: JSON Web Tokens (JWT), Google OAuth 2.0
* **Payment Gateway**: Stripe API