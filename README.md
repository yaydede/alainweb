# Alain Carpenter - Math & Science Tutoring Website

A professional, warm, and modern website for Alain Carpenter's tutoring services, featuring automated scheduling capabilities and a responsive design.

## 🌟 Features

- **Responsive Design**: Works beautifully on desktop, tablet, and mobile devices
- **Warm Professional Aesthetic**: Uses earth tones and modern typography
- **Multiple Scheduling Options**: Integrated with popular scheduling platforms
- **Smooth Animations**: Fade-in effects and smooth scrolling
- **Contact Form**: Built-in contact functionality
- **SEO Friendly**: Semantic HTML structure

## 📁 File Structure

```
alainweb/
├── index.html           # Main website
├── styles.css          # Styling and design
├── script.js           # JavaScript functionality
├── booking-form.html   # Custom booking form
├── scheduling-setup.html # Scheduling setup guide
└── README.md          # This file
```

## 🚀 Quick Start

1. **Open the Website**
   - Simply open `index.html` in your web browser
   - Or use a local server for best results

2. **Set Up Scheduling** (Choose one option)
   - Open `scheduling-setup.html` for detailed instructions
   - Options include:
     - Cal.com (Recommended - Free)
     - Calendly
     - Custom booking form
     - Google Calendar

## 📅 Scheduling Setup

### Option 1: Cal.com (Recommended)
1. Create a free account at [cal.com](https://cal.com)
2. Set up your availability and event types
3. Update line 143 in `script.js`:
   ```javascript
   const calUsername = 'your-actual-username';
   ```

### Option 2: Custom Booking Form
- Use `booking-form.html` as a standalone booking page
- Integrate with EmailJS for email notifications:
  1. Sign up at [emailjs.com](https://emailjs.com)
  2. Add your credentials to `booking-form.html`

## 📧 Contact Form Setup

To enable email functionality in the contact form:

1. **Using EmailJS** (Free up to 200 emails/month)
   - Sign up at [emailjs.com](https://emailjs.com)
   - Create an email service and template
   - Add your Public Key to the script

2. **Using a Backend Service**
   - Connect to your preferred backend
   - Update the form submission handler in `script.js`

## 🎨 Customization

### Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #8b7355;      /* Warm brown */
    --secondary-color: #4a90e2;    /* Professional blue */
    --accent-color: #d4a574;       /* Light brown accent */
    --bg-light: #faf8f5;          /* Light warm background */
}
```

### Content
- Update contact information in `index.html`
- Modify course listings in the Courses section
- Update testimonials with real student feedback
- Replace placeholder email and phone numbers

### Images
The website uses SVG graphics for illustrations. To add real photos:
1. Create an `images` folder
2. Add your images
3. Replace SVG elements with `<img>` tags

## 📱 Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🔧 Technical Details

- **No Build Process Required**: Pure HTML, CSS, and JavaScript
- **No Dependencies**: Runs without any npm packages
- **Google Fonts**: Inter and Merriweather (loaded from CDN)
- **Mobile First**: Responsive design with breakpoint at 768px

## 📝 TODO for Production

Before going live, make sure to:

- [ ] Update all contact information
- [ ] Set up scheduling system (Cal.com or alternative)
- [ ] Configure email service for forms
- [ ] Add real testimonials
- [ ] Update meta tags for SEO
- [ ] Add Google Analytics (optional)
- [ ] Test on multiple devices
- [ ] Set up domain and hosting

## 🚀 Deployment Options

1. **GitHub Pages** (Free)
   - Push to GitHub repository
   - Enable GitHub Pages in settings

2. **Netlify** (Free tier available)
   - Drag and drop the folder to Netlify
   - Automatic HTTPS

3. **Traditional Hosting**
   - Upload files via FTP
   - Works with any web host

## 📞 Support

For questions about setup or customization:
- Review `scheduling-setup.html` for detailed scheduling instructions
- Check browser console for any JavaScript errors
- Ensure all file paths are correct

## 📄 License

This website template is provided for Alain Carpenter's tutoring services. Feel free to modify as needed.

---

**Created with care for effective math and science tutoring** 🎓
