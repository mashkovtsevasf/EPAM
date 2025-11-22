Best Shop - E-commerce Website

Multi-page e-commerce website built with HTML, SCSS, and JavaScript.

Prerequisites

Node.js (v14 or higher)
npm (v6 or higher)

Setup and Run

1. Install dependencies:
   npm install

2. Compile SCSS and start development server:
   npm run dev

   This command will:
   - Compile SCSS to CSS
   - Watch for SCSS file changes and automatically recompile
   - Start a local HTTP server on port 5050
   - Open the website in your default browser

Features

- Responsive Design: Supports 768px, 1024px, and 1440px breakpoints
- Dynamic Content: Products loaded from JSON file
- Shopping Cart: LocalStorage-based cart management
- Product Filtering: Filter by category, color, size, and sales status
- Search: Real-time product search
- User Reviews: Add and view product reviews
- Form Validation: Email validation and required field checks

Development

- SCSS files are automatically compiled to CSS when changes are detected
- The development server runs on http://localhost:5050
- Main entry point: src/index.html

Build

To compile SCSS without watching:
npm run compile
