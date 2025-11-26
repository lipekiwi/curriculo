# Personal Portfolio Website

A modern, clean, and fully responsive personal portfolio website for Filipe Santos.

## Features

- ✨ Modern and clean design with soft colors
- 🌙 Dark mode toggle with theme persistence
- 📱 Fully responsive design (mobile, tablet, desktop)
- 🎯 Smooth scrolling navigation
- 🎨 Smooth animations and transitions
- 📧 Contact form with validation
- 🔗 Social media links (GitHub, LinkedIn)

## Sections

1. **Home** - Introduction with name, title, location, and call-to-action buttons
2. **About** - Personal bio and background
3. **Skills** - Technical skills with icons
4. **Projects** - Featured projects with descriptions and links
5. **Certifications** - Cisco certifications
6. **Contact** - Contact form and social links

## Technologies Used

- HTML5
- CSS3 (with CSS Variables for theming)
- JavaScript (Vanilla JS)
- Font Awesome (for icons)

## Setup

1. Clone or download this repository
2. Open `index.html` in your web browser
3. No build process or dependencies required!

## Customization

### Update GitHub Link

If you have a GitHub profile, update the GitHub links in `index.html`:
- Line 48: Home section social link
- Line 232: Contact section social link

Replace `filipecorreiasantos` with your actual GitHub username.

### Add Project Images

To add images for projects:
1. Create an `images` folder
2. Add your project images
3. Update the project cards in `index.html` to include `<img>` tags

### Modify Colors

Edit the CSS variables in `styles.css` (lines 4-20) to change the color scheme:
- `--accent-color`: Primary accent color
- `--bg-primary`: Background color
- `--text-primary`: Main text color

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is open source and available for personal use.

---

**Note**: The contact form currently shows an alert message. To make it functional, you'll need to:
1. Set up a backend service (e.g., Formspree, EmailJS, or your own server)
2. Update the form submission handler in `script.js`

