# AnsorMed Website

A modern medical center website built with React and pure CSS, featuring traditional and natural treatment methods.

## Features

- **Responsive Design**: Works on desktop, tablet, and mobile devices
- **Modern UI**: Clean and professional design with teal and red color scheme
- **Uzbek Language**: Content in Uzbek language
- **Service Sections**:
  - Hijoma (Cupping therapy)
  - Manual therapy
  - Leech therapy
  - Natural remedies
- **Call-to-Action Buttons**: Multiple registration and contact options

## Technologies Used

- React 18
- Pure CSS (no external CSS frameworks)
- HTML5
- JavaScript ES6+

## Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- npm or yarn

### Installation

1. Clone the repository or navigate to the project directory
2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm start
   ```

4. Open [http://localhost:3000](http://localhost:3000) to view it in the browser

### Building for Production

To create a production build:

```bash
npm run build
```

This builds the app for production to the `build` folder.

## Project Structure

```
src/
├── components/
│   ├── Header.js          # Navigation header
│   ├── Header.css
│   ├── Hero.js            # Hero section with main message
│   ├── Hero.css
│   ├── Services.js        # Services section
│   ├── Services.css
│   ├── FooterCTA.js       # Footer call-to-action
│   ├── FooterCTA.css
│   ├── Footer.js          # Site footer
│   └── Footer.css
├── App.js                 # Main app component
├── App.css
├── index.js              # React entry point
└── index.css             # Global styles
```

## Design Features

- **Color Scheme**:

  - Primary: Teal (#20b2aa)
  - Secondary: Red (#e74c3c)
  - Background: White (#ffffff)
  - Text: Dark gray (#333333)

- **Typography**: Clean, modern sans-serif fonts
- **Layout**: Grid and flexbox for responsive design
- **Interactive Elements**: Hover effects and smooth transitions

## Customization

The website is built with modular components and CSS files, making it easy to customize:

- Update colors in the CSS files
- Modify content in the React components
- Add new services or sections
- Change images by updating the CSS background properties

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is created for demonstration purposes.
