# Randevu Client

A simple appointment booking client application that serves HTML files on localhost.

## Features

- 🚀 Simple Node.js server that serves HTML files locally
- 📅 Appointment booking system interface
- 📱 Mobile-responsive design
- 🎨 Clean and modern UI
- 🔧 No external dependencies required

## Getting Started

### Prerequisites

- Node.js (version 12 or higher)

### Installation & Running

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd randevuClient
   ```

2. Start the server:
   ```bash
   npm start
   ```

3. Open your browser and navigate to:
   ```
   http://localhost:3000
   ```

## Project Structure

```
randevuClient/
├── server.js          # Node.js HTTP server
├── package.json       # Project configuration
├── public/            # Web assets
│   ├── index.html     # Home page
│   ├── booking.html   # Appointment booking form
│   ├── appointments.html # View appointments
│   ├── about.html     # About page
│   ├── styles.css     # Styling
│   └── script.js      # Client-side JavaScript
└── README.md          # This file
```

## Pages

- **Home (`/`)**: Main landing page with navigation
- **Book Appointment (`/booking.html`)**: Form to schedule new appointments
- **My Appointments (`/appointments.html`)**: View and manage existing appointments
- **About (`/about.html`)**: Information about the application

## Development

The server automatically serves files from the `public/` directory. Any changes to HTML, CSS, or JavaScript files will be immediately available after refreshing the browser.

## Customization

- Modify HTML files in the `public/` directory to change the interface
- Update `styles.css` to customize the appearance
- Edit `script.js` to add client-side functionality
- The server runs on port 3000 by default (configurable in `server.js`)

## License

MIT License