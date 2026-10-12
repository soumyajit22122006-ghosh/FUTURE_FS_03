
# Clean Cut — Salon Website

Clean Cut is a modern and responsive salon website concept designed with a premium dark theme and elegant gold accents. The website showcases salon services, brand information, customer reviews, and location details.

## Features

- Responsive design for desktop, tablet, and mobile devices
- Premium dark theme with gold accents
- Navigation bar with section links
- Hero section introducing Clean Cut
- Services section displaying salon services
- About section describing the brand
- Customer reviews displayed as sample content
- Contact and location section featuring Kolkata
- Responsive mobile navigation menu
- Footer with automatically updated year

**Note:** This is the original website version. It does not include live customer reviews, login/signup, review editing or deletion, or an interactive live map.

## Tech Stack

- HTML / EJS
- CSS
- JavaScript
- Node.js
- Express.js

## Project Structure

```text
CleanCut/
├── public/
│   ├── script.js
│   └── style.css
├── views/
│   └── index.ejs
├── app.js
├── package.json
├── package-lock.json
└── README.md
```

## Requirements

Before running the project, install:

- [Node.js](https://nodejs.org/)
- npm (included with Node.js)
- Visual Studio Code or another code editor

## Installation and Setup

### 1. Clone or Download the Project

Download the project and open the `CleanCut` folder in Visual Studio Code.

### 2. Install Dependencies

Open the terminal in the project directory and run:

```bash
npm install
```

### 3. Start the Server

Run:

```bash
node app.js
```

### 4. Open the Website

Visit the following URL in your browser:

```text
http://localhost:8080
```

Make sure the port configured in `app.js` is `8080`, or use the port shown in your terminal.

## Customization

You can customize the website by editing these files:

- **`views/index.ejs`** — Website structure, text, and sections.
- **`public/style.css`** — Colors, layout, styling, and responsiveness.
- **`public/script.js`** — Frontend interactions and mobile navigation.
- **`app.js`** — Express server configuration and routes.
- **`package.json`** — Project metadata, dependencies, and scripts.

You can update the sample reviews, service descriptions, contact information, and Kolkata location text to suit your project.

## Future Improvements

Possible future enhancements include:

- Online appointment booking
- Customer login and registration
- Database-powered customer reviews
- Review editing and deletion
- Interactive map integration

These features are not included in the original version.

## Purpose

This project was developed for learning, practice, and portfolio purposes. It demonstrates the creation of a responsive business website using frontend technologies and Node.js with Express.js.
