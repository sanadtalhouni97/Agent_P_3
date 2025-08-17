# 🎌 AnimeVerse - Modern Anime Website

A beautiful, responsive anime website built with HTML, CSS, and JavaScript featuring modern animations, floating icons, and a professional design.

## ✨ Features

### 🎨 Design & UI
- **Modern & Professional Design** - Clean, minimal interface with subdued color palette
- **Responsive Layout** - Fully responsive design that works on all devices
- **Floating Icons** - Animated floating emojis throughout the page
- **Smooth Animations** - CSS animations and transitions for enhanced UX
- **Glass Morphism Effects** - Modern backdrop blur and transparency effects

### 🚀 Interactive Features
- **Mobile Navigation** - Hamburger menu for mobile devices
- **Smooth Scrolling** - Smooth navigation between sections
- **Parallax Effects** - Floating icons with parallax scrolling
- **Hover Animations** - Interactive hover effects on cards and buttons
- **Ripple Effects** - Material design-inspired button click effects
- **Typing Animation** - Hero title with typewriter effect
- **Counter Animations** - Animated statistics counters
- **Form Validation** - Contact form with real-time validation
- **Notification System** - Toast notifications for user feedback

### 🎮 Fun Extras
- **Konami Code Easter Egg** - Try ↑↑↓↓←→←→BA for a surprise!
- **Sound Effects** - Subtle audio feedback on button clicks
- **Rainbow Mode** - Easter egg that activates rainbow colors
- **Performance Optimized** - Throttled scroll events for smooth performance

## 📁 File Structure

```
Agent_P_3/
├── index.html          # Main HTML structure
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript functionality
└── README.md           # Project documentation
```

## 🛠️ Technologies Used

- **HTML5** - Semantic markup structure
- **CSS3** - Modern styling with CSS Grid, Flexbox, and animations
- **JavaScript (ES6+)** - Interactive functionality and animations
- **Google Fonts** - Poppins font family
- **Font Awesome** - Icon library for social media icons

## 🎯 Sections

1. **Hero Section** - Welcome banner with animated character
2. **Trending Anime** - Popular anime cards with ratings
3. **Genres** - Anime genre categories
4. **About** - Company information and statistics
5. **Contact** - Contact form and information
6. **Footer** - Links and social media

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies required

### Installation
1. Clone or download the project files
2. Open `index.html` in your web browser
3. Enjoy the anime website! 🎉

### Running Locally
```bash
# Navigate to the project directory
cd Agent_P_3

# Open with a local server (optional)
# Using Python 3
python -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server

# Then open http://localhost:8000 in your browser
```

## 🎨 Color Palette

The website uses a professional, subdued color scheme:

- **Primary**: `#6366f1` (Indigo)
- **Secondary**: `#8b5cf6` (Purple)
- **Accent**: `#f59e0b` (Amber)
- **Text Primary**: `#1f2937` (Dark Gray)
- **Text Secondary**: `#6b7280` (Medium Gray)
- **Background**: `#ffffff` (White)
- **Background Secondary**: `#f8fafc` (Light Gray)

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: 480px - 767px
- **Small Mobile**: Below 480px

## 🎭 Animations Included

- **Floating Icons** - Continuous floating animation with parallax
- **Pulse Effects** - Logo and genre icons
- **Bounce Animation** - Hero character emoji
- **Rotate Animation** - Character circle background
- **Fade In/Up** - Section elements on scroll
- **Zoom In** - Genre cards on scroll
- **Hover Transforms** - Cards and buttons
- **Ripple Effects** - Button click animations
- **Typing Effect** - Hero title animation
- **Counter Animation** - Statistics counting up

## 🔧 Customization

### Changing Colors
Edit the CSS custom properties in `styles.css`:
```css
:root {
    --primary-color: #6366f1;
    --secondary-color: #8b5cf6;
    --accent-color: #f59e0b;
    /* ... other colors */
}
```

### Adding New Anime
Add new anime cards in the trending section:
```html
<div class="anime-card" data-aos="fade-up">
    <div class="anime-image">
        <span class="anime-emoji">🎮</span>
    </div>
    <div class="anime-info">
        <h3>Your Anime Title</h3>
        <p>Description here</p>
        <div class="rating">
            <span class="stars">⭐⭐⭐⭐⭐</span>
            <span class="score">9.0</span>
        </div>
    </div>
</div>
```

### Modifying Floating Icons
Edit the floating icons in `index.html`:
```html
<div class="floating-icons">
    <div class="floating-icon" data-speed="2">🎌</div>
    <div class="floating-icon" data-speed="1.5">⚡</div>
    <!-- Add more icons here -->
</div>
```

## 🎮 Easter Eggs

### Konami Code
Try entering the Konami code: **↑↑↓↓←→←→BA**
- Activates rainbow mode for 5 seconds
- Shows a success notification

### Console Messages
Check the browser console for fun messages and hints!

## 📞 Support

For questions or support, you can:
- Check the contact form on the website
- Email: hello@animeverse.com
- Phone: +1 (555) 123-4567

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Google Fonts for the Poppins font family
- Font Awesome for the icon library
- The anime community for inspiration
- Modern web design principles and best practices

---

**Built with ❤️ for anime lovers everywhere! 🌟**

*Enjoy exploring AnimeVerse! 🎌* 