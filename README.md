# Anna Sorokina Photography Portfolio

Professional photography portfolio website for Anna Sorokina — fashion, portrait, and lifestyle photographer based in Winnipeg, Canada.

## Features

✨ **Modern Design**
- Elegant black & white aesthetic
- Serif typography (Playfair Display)
- Smooth animations and transitions
- Fully responsive (mobile, tablet, desktop)

📸 **Portfolio Gallery**
- 8 professional photography samples
- Interactive lightbox viewer
- Keyboard navigation (arrow keys + ESC)
- Smooth image transitions

🌍 **Bilingual Support**
- English (EN)
- Ukrainian (UA)
- Language preference saved in localStorage

📋 **Sections**
- **Home** - Hero section with animated background
- **About** - Professional biography and specializations
- **Services** - 6 pricing packages for different session types
- **Portfolio** - Gallery with navigation and modal view
- **Blog** - News, tips, and upcoming events
- **Booking Policy** - Session details and booking process
- **Booking Form** - Contact form for session requests
- **Contact** - Social links and contact information

🎯 **Additional Features**
- Sticky "Book Now" button for easy access
- Social media links (Instagram, WhatsApp, Email)
- Modal portfolio viewer with arrow navigation
- Smooth scroll behavior
- Professional typography and spacing

## Technology Stack

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with animations
- **Vanilla JavaScript** - No framework dependencies
- **Responsive Design** - Mobile-first approach

## Project Structure

```
anna-sorokina-photography/
├── public/
│   ├── index.html              # Main website file
│   └── images/
│       ├── hero-1.jpg          # Hero section background (4 images)
│       ├── hero-2.jpg
│       ├── hero-3.jpg
│       ├── hero-4.jpg
│       └── portfolio-*.jpg     # Portfolio gallery (8 images)
├── README.md
└── .gitignore
```

## Live Demo

🔗 **[Visit the website](https://anna-sorokina.kit.me.st)**

## Usage

### Local Development

1. Clone the repository:
```bash
git clone https://github.com/yourusername/anna-sorokina-photography.git
cd anna-sorokina-photography
```

2. Start a local HTTP server:
```bash
cd public
python3 -m http.server 8000
```

3. Open in browser:
```
http://localhost:8000
```

### Language Toggle
Click the **UA/EN** button in the top-right corner to switch languages.

### Portfolio Navigation
- Click any photo in the portfolio grid
- Use arrow buttons or keyboard arrows (← →) to navigate
- Press ESC or click the X button to close

## Customization

### Edit Contact Information
Open `public/index.html` and find the contact section to update:
- Email: `mir12312@ukr.net`
- WhatsApp: `+1-204-698-1788`
- Instagram: `@hanna_sorokina`

### Update Portfolio Images
Replace files in `public/images/portfolio-*.jpg` with your own images.

### Modify Services & Pricing
Edit the Services section in `index.html` to update packages and pricing.

### Change Colors & Fonts
All CSS variables are defined in the `<style>` section:
- `--primary-dark`: Background color
- `--text-primary`: Main text color
- `--serif`: Font for headings (Playfair Display)
- `--sans`: Font for body text (Inter)

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

All content © 2026 Anna Sorokina. All rights reserved.

## Contact

For inquiries about photography sessions, contact Anna directly:
- 📧 Email: mir12312@ukr.net
- 💬 WhatsApp: +1-204-698-1788
- 📷 Instagram: [@hanna_sorokina](https://www.instagram.com/hanna_sorokina)

---

*Website created by Kit | May 2026*
