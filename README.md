# The HyTables Website

A modern, professional website for The HyTables HyTale server.

## Overview

This website showcases The HyTables server information, including:
- Server branding and information
- Complete rank system (Player Progression, Donator, and Staff ranks)
- Server features and commands
- Quick links to Discord, Store, and Join Server

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with medieval theme
- **Smooth Animations**: Scroll animations and interactive elements
- **Easy Navigation**: Fixed navbar with smooth scrolling
- **Copy Server Address**: One-click copy functionality for server address

## File Structure

```
website/
├── index.html      # Main HTML file
├── styles.css      # All styling and responsive design
├── script.js       # JavaScript for interactivity
├── assets/
│   └── logo.png   # Server logo
└── README.md       # This file
```

## Server Information

- **Server Name**: The HyTables
- **Slogan**: Knights of the HyTables
- **Discord**: discord.hytable.online
- **Store**: store.hytable.online
- **Server Address**: play.hytable.online:15880

## Ranks Displayed

### Player Progression Ranks
1. Peasant (Crude Tier)
2. Townsfolk (Copper Tier)
3. Guildsman (Iron Tier)
4. Vassal (Cobalt Tier)
5. Noble (Adamantite Tier)
6. Legend (Mithril Tier)

### Donator Ranks
1. Squire
2. Knight
3. Knight-Sergeant
4. Banneret
5. Commandant
6. Grandmaster
7. Royal Benefactor

### Staff Ranks
- Admin
- Infinity
- Overlord
- God
- Legacy

## Future Expansion

The website is designed to be easily expandable for future features:
- Discord chat/channels/live preview integration
- Server player count display
- Live player list
- Server map integration

## Usage

Simply open `index.html` in a web browser to view the website. For production deployment:

1. Upload all files to your web server
2. Ensure the `assets/` folder and logo are included
3. The website uses Google Fonts (Cinzel and Inter) - ensure internet connection or host fonts locally

## Customization

### Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #8B4513;
    --secondary-color: #D4AF37;
    /* ... */
}
```

### Content
All content is in `index.html` and can be easily modified.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Notes

- The website uses modern CSS features (CSS Grid, Flexbox, CSS Variables)
- JavaScript is used for interactivity but the site is functional without it
- All external resources (Google Fonts) are loaded from CDN
