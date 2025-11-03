# monoya Connect - Landing Page

A modern, mobile-first, responsive SaaS landing page for monoya Connect - an AI-powered inquiry management service for Japanese manufacturers.

## 🎨 Design System

### Colors
- **URUSHI** `#0D0E11` - Primary text and dark elements
- **COTTON** `#FAF6ED` - Light background
- **LINEN** `#D7D1C3` - Secondary background
- **CLAY** `#7F7667` - Secondary text
- **ASH** `#C4BFB9` - Neutral elements
- **RUST** `#864636` - Call-to-action buttons
- **NIGHT FOG** `#43464D` - Accent dark

### Typography
- Font Stack: `system-ui, -apple-system, BlinkMacSystemFont, "Hiragino Sans", "Noto Sans JP", sans-serif`
- Japanese-optimized for excellent readability

### Layout
- Max width: 1180px (centered)
- Border radius: 16-20px
- Subtle shadows for depth
- Mobile padding: 24px
- Desktop padding: 48px

## 📱 Responsive Breakpoints

### Mobile (≤ 480px)
- Single column layout
- Hero image displays below text
- Sticky bottom CTA button
- Vertical card stacking

### Tablet (768px - 1024px)
- Two-column hero layout
- Cards in 2-column grid
- Full-width video player
- Desktop navigation visible

### Desktop (≥ 1200px)
- Hero layout: 60/40 split (text/image)
- Three-column feature cards
- Horizontal flow steps
- Centered video (max 960px)

## 🚀 Getting Started

### Quick Start
Simply open `index.html` in a web browser:
```bash
open index.html
```

### Local Development Server (Optional)
For a better development experience with live reload:

**Using Python:**
```bash
python3 -m http.server 8000
```
Then visit: `http://localhost:8000`

**Using Node.js:**
```bash
npx serve
```

## 📁 File Structure

```
monoya Connect Website/
├── assets/             # Brand assets (logo + favicon)
│   ├── favicon.svg
│   ├── logo-dark.svg
│   └── logo-light.svg
├── index.html          # Main HTML structure
├── styles.css          # All styling and responsive design
├── script.js           # Interactive functionality
└── README.md           # This file
```

## ✨ Features

### Sections Included
1. **Sticky Header** - Navigation with CTA button
2. **Hero Section** - Product introduction with mockup
3. **Demo Video** - Video placeholder with key benefits
4. **Problem Section** - Three manufacturer pain points
5. **Service Overview Section** - AI+monoya team features with icons
6. **Impact Metrics Section** - Results-driven metrics (95%, 70%, 3x)
7. **Flow Section** - Four-step process visualization
8. **Contact Form** - Lead capture with 5 fields
9. **Footer** - Company information
10. **Mobile Sticky CTA** - Fixed bottom button on mobile

### Interactive Elements
- ✅ Smooth scroll navigation
- ✅ Scroll-triggered animations
- ✅ Form validation and submission
- ✅ Hover effects on cards and buttons
- ✅ Header shadow on scroll
- ✅ Responsive mobile menu (ready for enhancement)

## 🎯 Target Audience
Japanese craft and small manufacturers looking to:
- Handle overseas OEM inquiries
- Automate initial communication with buyers
- Screen and qualify leads efficiently
- Reduce sales overhead

## 🔧 Customization

### Updating Colors
Edit CSS custom properties in `styles.css`:
```css
:root {
    --rust: #864636;  /* Change CTA button color */
    --cotton: #FAF6ED; /* Change background color */
    /* ... */
}
```

### Updating Logo / Favicon
Replace the SVGs under `assets/` or swap the `<img>` references in `index.html` if you introduce alternative marks.

### Adding Real Video
Replace video placeholder in `script.js`:
```javascript
// In the video click handler, add your video URL:
videoPlaceholder.innerHTML = '<iframe src="YOUR_VIDEO_URL" ...></iframe>';
```

### Form Integration
Connect the form to your backend in `script.js`:
```javascript
// Replace console.log with actual API call
fetch('YOUR_API_ENDPOINT', {
    method: 'POST',
    body: JSON.stringify(formData),
    headers: { 'Content-Type': 'application/json' }
});
```

## 📊 Performance Optimizations
- Mobile-first approach
- Minimal JavaScript
- Pure CSS animations
- Optimized load order
- No external dependencies
- Clean, semantic HTML

## 🌐 Browser Support
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- iOS Safari 12+
- Android Chrome

## 📝 Content Structure

All Japanese content is inline in `index.html`. To update copy:
1. Open `index.html`
2. Find the relevant section
3. Edit the Japanese text directly
4. Save and refresh browser

## 🎨 Design Inspiration
Modern SaaS landing pages with:
- Clean, card-based layouts
- Soft color palette
- Clear visual hierarchy
- Strong CTAs
- Mobile-first responsive design

## 📞 Contact
monoya株式会社  
渋谷区猿楽町17-10 代官山アートヴィレッジ2C  
www.monoya.com

---

**Built with ❤️ for Japanese manufacturers**

