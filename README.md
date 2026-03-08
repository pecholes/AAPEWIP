# AAPE - In-Home Professional Education Nursing Aides Website

A professional, responsive website for in-home nursing aide services built with HTML, CSS, and JavaScript. Features a sophisticated gold, black, and white color scheme.

## 🎨 Color Scheme

- **Gold (Primary)**: #D4AF37
- **Black (Secondary)**: #1A1A1A  
- **White (Accent)**: #FFFFFF
- **Light Gray**: #F5F5F5

## 📁 Project Structure

```
AAPEWIP/
├── index.html              # Home page
├── services.html           # Services offered
├── about.html              # About the company and team
├── contact.html            # Contact form and information
├── css/
│   └── style.css          # Main stylesheet (gold/black/white theme)
├── js/
│   └── script.js          # Interactive functionality
├── assets/                # Media files and images (placeholders)
├── .github/
│   └── copilot-instructions.md  # Project instructions
└── README.md              # This file
```

## ✨ Features

- ✅ Fully responsive mobile-first design
- ✅ Professional gold, black, and white aesthetic
- ✅ Service descriptions and offerings
- ✅ Team member profiles section
- ✅ Contact form with client-side validation
- ✅ Smooth scrolling navigation
- ✅ Accessibility compliant (WCAG standards)
- ✅ SEO optimized HTML structure
- ✅ Interactive form handling
- ✅ Sticky navigation bar

## 🚀 Getting Started

### Prerequisites

No special dependencies required! This is pure HTML, CSS, and JavaScript.

### Running Locally

1. Open any of the HTML files directly in your web browser
2. Or use a local server:

**Using Python 3:**
```bash
python -m http.server 8000
```

**Using Python 2:**
```bash
python -m SimpleHTTPServer 8000
```

**Using Node.js (with http-server):**
```bash
npm install -g http-server
http-server
```

Then visit `http://localhost:8000` in your browser.

## 📋 Pages

### Home (index.html)
- Hero section with call-to-action
- Services preview cards
- "Why Choose Us" section with features
- Footer with contact information

### Services (services.html)
- Detailed service descriptions
- 8 comprehensive care services listed
- Call-to-action for booking

### About (about.html)
- Company story and mission
- Team member profiles (4 team members)
- Core company values
- Professional team credentials

### Contact (contact.html)
- Contact information (phone, email, address)
- Business hours
- Contact form with validation
- Form submission handling

## 🛠️ Customization

### Update Company Information

Edit the following in each HTML file:
- Phone number: `(555) 123-4567`
- Email: `care@aape.com`
- Address: `123 Care Street, Wellness City, ST 12345`

### Add Images

Place your images in the `assets/` folder and update:
- Hero background: `css/style.css` (line with `hero-bg.jpg`)
- Team member photos: Update `.member-image` classes in `about.html`

### Modify Services

Edit the service cards in:
- `index.html` - Services Preview section
- `services.html` - Full services list

### Update Team Members

Edit team member information in `about.html` with actual names, titles, and descriptions.

## 🎯 Next Steps

1. **Add Real Content**
   - Replace placeholder text with actual company information
   - Add team member photos to assets folder

2. **Set Up Backend**
   - Configure a backend service to handle contact form submissions
   - Update `js/script.js` to send data to your server

3. **Deploy**
   - Upload to web hosting service
   - Configure domain name
   - Set up SSL certificate

4. **SEO Optimization**
   - Add meta descriptions to each page
   - Set up Google analytics
   - Create sitemap.xml

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🔧 Form Handling

Currently, the contact form displays a success message client-side. To make it functional:

1. Set up a backend endpoint to receive form data
2. Update the `handleFormSubmission()` function in `js/script.js`
3. Add a fetch request to your backend API

Example backend integration:
```javascript
// In js/script.js - handleFormSubmission()
fetch('/api/contact', {
    method: 'POST',
    headers: {
        'Content-Type': 'application/json',
    },
    body: JSON.stringify(data)
})
.then(response => response.json())
.then(data => console.log('Success:', data))
.catch(error => console.error('Error:', error));
```

## 📄 License

This project template is free to use and modify for your nursing aide business.

## 📞 Support

For customization or technical support with this website template, please refer to the project documentation or contact your web developer.

## 🎨 Design Notes

- All colors use hex values for consistency across browsers
- Font: 'Segoe UI' with fallbacks to system fonts
- Line height: 1.6 for optimal readability
- Max-width container: 1200px for desktop alignment
- Responsive breakpoints: 768px and 480px

---

**Built with** ❤️ **for professional nursing care services**
