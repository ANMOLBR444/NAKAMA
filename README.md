# NAKAMA - Coming Soon Landing Page

A beautiful and responsive "Coming Soon" landing page built with Node.js, Express, and Tailwind CSS.

## Features

- **Responsive Design**: Looks great on desktop, tablet, and mobile devices
- **Modern UI**: Beautiful gradient backgrounds with animated elements
- **Email Signup**: Newsletter subscription form (ready for backend integration)
- **Social Media Links**: Placeholder social media icons
- **Tailwind CSS**: Utility-first CSS framework for rapid styling
- **Node.js Server**: Express server to serve the landing page

## Tech Stack

- **Backend**: Node.js with Express
- **Frontend**: HTML5, CSS3 (Tailwind CSS)
- **Build Tools**: Tailwind CSS CLI
- **Development**: Nodemon for auto-reloading

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn

### Installation

1. Clone the repository or navigate to the project directory
2. Install dependencies:

   ```bash
   npm install
   ```

3. Build the CSS:

   ```bash
   npm run build-css
   ```

4. Start the development server:

   ```bash
   npm run dev
   ```

5. Open your browser and visit `http://localhost:3000`

## Available Scripts

- `npm start` - Start the production server
- `npm run dev` - Start the development server with nodemon
- `npm run build-css` - Build Tailwind CSS with watch mode

## Project Structure

```
nakama-coming-soon/
├── .github/
│   └── copilot-instructions.md
├── public/
│   └── style.css                # Compiled CSS
├── src/
│   └── input.css               # Tailwind CSS source
├── views/
│   └── index.html              # Main landing page
├── server.js                   # Express server
├── package.json                # Dependencies and scripts
└── tailwind.config.js          # Tailwind configuration
```

## Customization

### Colors & Styling

Modify the Tailwind classes in `views/index.html` or extend the theme in `tailwind.config.js`.

### Content

Edit the text content, brand name, and messaging in `views/index.html`.

### Email Integration

Connect the email form to your preferred email service (Mailchimp, ConvertKit, etc.) by adding form handling in `server.js`.

### Social Media

Update the social media links and icons in the footer section of `index.html`.

## Deployment

1. Build the production CSS:

   ```bash
   npx tailwindcss -i ./src/input.css -o ./public/style.css --minify
   ```

2. Deploy to your preferred hosting platform (Vercel, Netlify, Heroku, etc.)

## License

MIT License - feel free to use this project for your own coming soon pages!
