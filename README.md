# VictoryEdge Solution Provider Website

A modern, professional, and accessible website for VictoryEdge Solution Provider - a professional development and business transformation company.

## 🚀 Features

- **4 Complete Pages**: Home, About & Services, Blog & Testimonials, Contact & Application
- **Modern Design**: Clean, professional, and mobile-responsive design
- **Accessibility**: WCAG AA compliant with keyboard navigation and screen reader support
- **Performance**: Optimized for speed with lazy loading and efficient animations
- **SEO Ready**: Complete meta tags, structured data, sitemap, and robots.txt
- **Interactive Elements**: Forms, testimonials carousel, smooth animations
- **Brand Consistency**: Exact brand colors and typography as specified

## 🎨 Brand Guidelines

### Colors
- **Brand Green**: `#078634` (CTAs and accents)
- **Background Dark**: `#0A0F14` (main background)
- **Text White**: `#FFFFFF` (primary text)
- **Muted Gray**: `#BFBFBF` (secondary text)

### Typography
- **Font**: Poppins (Google Fonts)
- **Weights**: 300, 400, 600, 700

## 📁 Project Structure

```
/
├── index.html              # Homepage
├── about.html              # About & Services
├── blog.html               # Blog & Testimonials
├── contact.html            # Contact & Application
├── css/
│   └── style.css          # Main stylesheet
├── js/
│   └── main.js            # JavaScript functionality
├── assets/
│   └── images/            # Images directory
├── robots.txt             # SEO robots file
├── sitemap.xml            # XML sitemap
└── README.md              # This file
```

## 📝 How to Edit Content

### Text Content
All text content is directly in the HTML files. Search for the text you want to change and replace it directly.

**Key areas to edit:**
- Page titles and meta descriptions (in `<head>` section)
- Hero headlines and content
- Program descriptions
- Testimonials
- Contact information
- Footer content

### Images
1. Place new images in the `assets/images/` directory
2. Update image paths in HTML files
3. For hero images, ensure they're high quality and optimized
4. Add descriptive alt text for accessibility

### Programs/Services
Edit the program cards in `about.html`. Each program is contained in a `.card` element with:
- Program title
- Duration and format
- Description
- Learning outcomes/benefits
- Call-to-action button

### Testimonials
Update testimonials in `index.html` and `blog.html`. Each testimonial includes:
- Quote text
- Author name
- Author title/position
- Avatar (currently using initials)

## 🔧 Technical Setup

### Local Development
1. Clone or download the project files
2. Open a terminal in the project directory
3. Start a local server:
   ```bash
   python -m http.server 8000
   ```
4. Open `http://localhost:8000` in your browser

### Form Configuration
The contact form currently uses client-side validation. To enable actual form submission:

**Option 1: EmailJS (Recommended)**
1. Sign up at [EmailJS](https://www.emailjs.com/)
2. Create a new email service
3. Replace the form submission code in `main.js` with EmailJS integration

**Option 2: Google Forms**
1. Create a Google Form with matching fields
2. Get the form submission URL
3. Update the form action to point to the Google Forms URL

**Option 3: Custom Backend**
- Create an API endpoint to handle form submissions
- Update the form submission code in `main.js` to POST to your endpoint

## 🚀 Deployment

### Option 1: Netlify (Recommended)
1. Create a Netlify account
2. Drag and drop your project folder to Netlify
3. Your site will be live instantly with a custom URL
4. Configure custom domain and SSL in Netlify settings

### Option 2: Vercel
1. Create a Vercel account
2. Import your project from GitHub or upload directly
3. Deploy with zero configuration
4. Custom domain and SSL automatically configured

### Option 3: GitHub Pages
1. Create a GitHub repository
2. Upload all files to the repository
3. Enable GitHub Pages in repository settings
4. Your site will be available at `username.github.io/repository-name`

### Option 4: Traditional Hosting
1. Upload all files to your web server via FTP
2. Ensure `index.html` is in the root directory
3. Configure SSL certificate (Let's Encrypt recommended)
4. Point your domain to the server

## 🛠️ Customization

### Color Scheme
Colors are defined in CSS custom properties in `style.css`:
```css
:root {
  --brand-green: #078634;
  --bg-dark: #0A0F14;
  --text-white: #FFFFFF;
  --muted-gray: #BFBFBF;
}
```

### Animations
Animations are configured in `main.js`. You can:
- Adjust animation durations
- Change scroll trigger points
- Modify easing functions
- Add new animation types

### Responsive Breakpoints
The site uses three breakpoints:
- Mobile: up to 640px
- Tablet: 641px - 1024px
- Desktop: 1025px and above

## 📊 Performance Optimization

### Current Performance Targets
- Lighthouse Score: >90 Desktop, >70 Mobile
- First Contentful Paint: <2s
- Largest Contentful Paint: <3s
- Cumulative Layout Shift: <0.1

### Optimization Features
- Lazy loading for images
- Optimized CSS and JavaScript
- Efficient animations with CSS transforms
- Compressed assets
- Proper font loading strategy

## 🔍 SEO Features

### Meta Tags
- Title tags for all pages
- Meta descriptions (150-160 chars)
- Open Graph tags for social sharing
- Twitter Card tags
- Canonical URLs

### Structured Data
- Organization schema
- Website schema
- BreadcrumbList schema

### Technical SEO
- XML Sitemap
- Robots.txt
- Clean URL structure
- Semantic HTML markup
- Alt text for images

## ♿ Accessibility Features

### WCAG AA Compliance
- 4.5:1 contrast ratio for normal text
- 3:1 contrast ratio for large text
- Keyboard navigation support
- Focus indicators
- Screen reader compatibility

### Specific Features
- Skip to content link
- ARIA labels and roles
- Semantic HTML structure
- Alt text for all images
- Form labels and validation
- Reduced motion support

## 📱 Mobile Optimization

### Responsive Design
- Mobile-first approach
- Flexible grid system
- Touch-friendly buttons (44px minimum)
- Optimized typography scaling
- Mobile-optimized navigation

### Performance
- Optimized images with srcset
- Minimal JavaScript on mobile
- Efficient CSS animations
- Fast loading times

## 🎨 Design System

### Spacing
Based on 8px rhythm:
- Small: 8px
- Medium: 16px
- Large: 24px
- XL: 32px
- XXL: 48px

### Typography Scale
- H1: 3.5rem (56px)
- H2: 2.5rem (40px)
- H3: 2rem (32px)
- H4: 1.5rem (24px)
- Body: 1rem (16px)

### Component Library
- Buttons (primary, secondary)
- Cards
- Forms
- Navigation
- Testimonials
- Newsletter signup

## 🐛 Troubleshooting

### Common Issues
1. **Images not loading**: Check file paths and ensure images are in `assets/images/`
2. **Forms not working**: Configure form submission backend
3. **Mobile layout issues**: Check CSS breakpoints
4. **Slow loading**: Optimize images and enable compression

### Browser Support
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 📞 Support

For technical support or questions:
- Email: victoryedgesolutionprovider@gmail.com
- WhatsApp: +234 806 479 8876
- Response time: Within 24 hours

## 📄 License

This project is created for VictoryEdge Solution Provider. All rights reserved.

---

**Built with ❤️ for your success**