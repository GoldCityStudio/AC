# 冷氣GUY - Air Conditioning Service Website

A modern, responsive website for AC Guy (冷氣GUY), a Hong Kong-based air conditioning service company. This website replicates the design and functionality of [acguy.com.hk](https://acguy.com.hk/) with a professional, user-friendly interface.

## 🌟 Features

### Design & Layout
- **Modern, Professional Design**: Clean and modern interface with a blue color scheme
- **Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **Hong Kong Chinese Typography**: Uses Noto Sans HK font for authentic local feel
- **Smooth Animations**: CSS animations and JavaScript interactions for enhanced UX

### Navigation & User Experience
- **Fixed Header**: Sticky navigation with smooth scroll effects
- **Mobile Menu**: Hamburger menu for mobile devices with smooth transitions
- **Smooth Scrolling**: Anchor links with smooth scroll behavior
- **Scroll to Top**: Floating button to return to the top of the page
- **WhatsApp Integration**: Direct WhatsApp contact button with number 85270173695

### Content Sections
1. **Hero Section**: Eye-catching landing area with call-to-action buttons
2. **About Section**: Company introduction and mission statement
3. **Services Section**: Three main service offerings with icons
4. **Process Section**: 5-step service workflow with detailed explanations
5. **Cases Section**: Portfolio of completed projects with pricing
6. **Knowledge Section**: Blog articles and educational content
7. **Footer**: Contact information and social media links

### Interactive Features
- **Hover Effects**: Cards and buttons with smooth hover animations
- **Counter Animations**: Animated case numbers when scrolling into view
- **Loading Screen**: Professional loading animation on page load
- **Form Validation**: Built-in form validation for contact forms
- **Image Lazy Loading**: Optimized image loading for better performance

### Technical Features
- **Cross-browser Compatible**: Works on all modern browsers
- **SEO Optimized**: Semantic HTML structure and meta tags
- **Accessibility**: ARIA labels and keyboard navigation support
- **Performance Optimized**: Debounced scroll events and optimized animations

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- No server setup required - runs entirely in the browser

### Installation
1. Clone or download the project files
2. Open `index.html` in your web browser
3. The website will load immediately with all features functional

### File Structure
```
AC/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
├── README.md           # Project documentation
└── .github/workflows/  # GitHub Actions deployment
    └── deploy.yml      # GitHub Pages deployment workflow
```

## 🌐 Deployment

### GitHub Pages (Recommended)
This repository is configured for automatic deployment to GitHub Pages:

1. **Repository Setup**: The code is already pushed to [https://github.com/GoldCityStudio/AC](https://github.com/GoldCityStudio/AC)
2. **Enable GitHub Pages**:
   - Go to repository Settings
   - Navigate to "Pages" section
   - Select "Deploy from a branch"
   - Choose "gh-pages" branch
   - Click "Save"
3. **Automatic Deployment**: Every push to main branch triggers automatic deployment
4. **Live URL**: Your site will be available at `https://goldcitystudio.github.io/AC/`

### Manual Deployment
For other hosting platforms:
1. Upload all files to your web server
2. Ensure `index.html` is in the root directory
3. The website will work immediately

## 🎨 Design System

### Color Palette
- **Primary Blue**: `#2563eb` - Main brand color
- **Secondary Blue**: `#1d4ed8` - Hover states
- **Light Blue**: `#dbeafe` - Background accents
- **Dark Gray**: `#1e293b` - Footer background
- **Text Gray**: `#64748b` - Secondary text
- **White**: `#ffffff` - Background and text
- **WhatsApp Green**: `#25d366` - WhatsApp button

### Typography
- **Font Family**: Noto Sans HK (Google Fonts)
- **Weights**: 300, 400, 500, 700
- **Language**: Traditional Chinese (Hong Kong)

### Layout
- **Container Width**: 1200px max-width
- **Grid System**: CSS Grid and Flexbox
- **Spacing**: Consistent 20px padding and margins
- **Border Radius**: 15px for cards, 25px for buttons

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: 480px - 767px
- **Small Mobile**: Below 480px

## 🔧 Customization

### Changing Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #1d4ed8;
    --accent-color: #dbeafe;
    --dark-color: #1e293b;
    --text-color: #64748b;
}
```

### Adding Content
1. **New Sections**: Add HTML structure in `index.html`
2. **Styling**: Add corresponding CSS in `styles.css`
3. **Functionality**: Add JavaScript in `script.js`

### Modifying Images
Replace the Unsplash image URLs with your own images:
```html
<img src="your-image-url.jpg" alt="Description">
```

### Changing WhatsApp Number
Update the WhatsApp button number in `script.js`:
```javascript
whatsappBtn.href = 'https://wa.me/YOUR_NUMBER_HERE';
```

## 🌐 Browser Support

- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 📈 Performance

- **Page Load**: Optimized for fast loading
- **Images**: Lazy loading and error handling
- **Animations**: Hardware-accelerated CSS transforms
- **Scrolling**: Debounced scroll events for smooth performance

## 🔒 Accessibility

- **Keyboard Navigation**: Full keyboard support
- **Screen Readers**: ARIA labels and semantic HTML
- **Focus Indicators**: Clear focus states for all interactive elements
- **Color Contrast**: WCAG AA compliant color combinations

## 📞 Contact Information

The website displays the following contact information:
- **Phone**: 2555 6622
- **WhatsApp**: 85270173695 (direct button)
- **Social Media**: Facebook, Instagram, YouTube links

## 🛠️ Development

### Adding New Features
1. **JavaScript**: Add event listeners and functionality in `script.js`
2. **CSS**: Add styles in `styles.css` with appropriate media queries
3. **HTML**: Update structure in `index.html`

### Testing
- Test on multiple devices and browsers
- Verify responsive behavior at all breakpoints
- Check accessibility with screen readers
- Validate HTML and CSS

### Deployment Workflow
1. Make changes to your local files
2. Commit changes: `git add . && git commit -m "Description"`
3. Push to GitHub: `git push origin main`
4. GitHub Actions will automatically deploy to GitHub Pages

## 📄 License

This project is created for educational and demonstration purposes. The design is inspired by [acguy.com.hk](https://acguy.com.hk/).

## 🙏 Acknowledgments

- **Original Design**: AC Guy (冷氣GUY) - [acguy.com.hk](https://acguy.com.hk/)
- **Icons**: Font Awesome 6.0
- **Fonts**: Google Fonts - Noto Sans HK
- **Images**: Unsplash (placeholder images)
- **Deployment**: GitHub Pages & GitHub Actions

---

**冷氣GUY** - Your trusted air conditioning service partner in Hong Kong! 🏠❄️

## 🔗 Live Demo

Visit the live website: [https://goldcitystudio.github.io/AC/](https://goldcitystudio.github.io/AC/) 