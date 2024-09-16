# Construction Website

This is a responsive construction website built with **React.js**. The website showcases construction projects, services, and company details with a modern design.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies](#technologies)
- [Folder Structure](#folder-structure)
- [Contributing](#contributing)
- [License](#license)

## Features

- Responsive design, mobile-first approach.
- Interactive project galleries.
- Service descriptions with icons and animations.
- Contact form integrated with email service.
- Google Maps for location display.
- SEO optimized for search engines.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/construction-website.git
    ```
2. Navigate to the project directory:
    ```bash
    cd construction-website
    ```
3. Install dependencies:
    ```bash
    npm install
    ```

## Usage

1. Start the development server:
    ```bash
    npm start
    ```
   This will run the app in development mode on [http://localhost:3000](http://localhost:3000).

2. To build the project for production:
    ```bash
    npm run build
    ```
   This will bundle the React app into static files for deployment.

## Technologies

- **React.js** - Frontend library
- **React Router** - For navigation
- **Styled Components** - For styling
- **Axios** - For making API requests
- **Google Maps API** - For location services
- **EmailJS** - For contact form integration

## Folder Structure

```bash
├── public
│   └── index.html       # HTML template
├── src
│   ├── assets           # Images, fonts, etc.
│   ├── components       # Reusable components (Header, Footer, etc.)
│   ├── pages            # Page components (Home, Services, Projects, Contact)
│   ├── App.js           # Main app component
│   ├── index.js         # Entry point of the app
│   └── styles           # Global styles and themes
└── package.json         # Project dependencies and scripts
