# Mostafa Elsayed - Professional Portfolio

A modern, responsive professional portfolio website for Mostafa Elsayed Mohamed Ahmed - General Accountant.

## 🎨 Theme & Design

This portfolio features a **professional accounting/finance theme** with:

- **Color Scheme**: 
  - Navy Blue (#1a365d) - Professional and trustworthy
  - Teal (#2c7a7b) - Stability and growth
  - Gold (#d69e2e) - Excellence and achievement
  
- **Design Philosophy**: Clean, corporate, and professional layout suitable for the financial sector

- **Key Differences from Amr's Portfolio**:
  - Finance-focused color palette (blue/teal/gold vs. construction colors)
  - Professional corporate style vs. technical/trade style
  - Work Experience & Internships instead of project gallery
  - Skills visualization with progress bars
  - Timeline layout for career progression
  - Formal business tone throughout

## 📋 Features

- ✅ Fully responsive design (mobile, tablet, desktop)
- ✅ Smooth scrolling and animations
- ✅ Interactive skill progress bars
- ✅ Timeline-based experience display
- ✅ Animated statistics counter
- ✅ Contact form with email integration
- ✅ Back-to-top button
- ✅ Professional typography and spacing
- ✅ Optimized for performance

## 📁 Structure

```
mostafa_portfolio/
├── index.html          # Main HTML file
├── styles.css          # Professional styling
├── script.js           # Interactive functionality
└── README.md          # This file
```

## 🚀 Quick Start

1. **Open the portfolio**: Simply open `index.html` in any modern web browser

2. **Customize Content**: 
   - Edit personal information in `index.html`
   - Update contact details
   - Modify experience and education sections

3. **Customize Colors** (Optional):
   - Open `styles.css`
   - Modify CSS variables in the `:root` section:
     ```css
     :root {
         --primary-color: #1a365d;
         --secondary-color: #2c7a7b;
         --accent-color: #d69e2e;
     }
     ```

## 📱 Sections

1. **Home/Hero**: Introduction with key statistics (GPA, Experience, Certifications)
2. **About**: Professional summary and contact information
3. **Education**: Academic background with timeline
4. **Experience**: Work experience and banking internships
5. **Skills**: Technical skills with progress bars, personal skills, courses, and languages
6. **Contact**: Contact information and message form

## 🎯 Key Highlights

- **Excellence Grade**: 3.7 GPA prominently displayed
- **Banking Experience**: Multiple internships at major banks (NBE, Banque Misr, CIB)
- **Professional Skills**: Excel, Power BI, Financial Reporting, Audit Procedures
- **Personal Qualities**: Leadership, Critical Thinking, Communication, Integrity

## 💻 Technologies Used

- HTML5
- CSS3 (with CSS Grid and Flexbox)
- Vanilla JavaScript (ES6+)
- Font Awesome Icons (v6.4.0)

## 📧 Contact Integration

The contact form is integrated with:
- Email client (mailto:)
- Pre-filled subject and message format
- Form validation

To customize the recipient email, update in both:
1. `index.html` - Email links
2. `script.js` - Contact form handler

## 🌐 Deployment Options

### Option 1: GitHub Pages (Free)
1. Create a GitHub repository
2. Upload all files
3. Go to Settings → Pages
4. Select main branch
5. Your site will be live at: `https://yourusername.github.io/repository-name`

### Option 2: Netlify (Free)
1. Create account at netlify.com
2. Drag and drop the folder
3. Your site will be live instantly

### Option 3: Local Hosting
- Simply open `index.html` in any browser
- No server required

## ✏️ Customization Guide

### Update Personal Information
1. Open `index.html`
2. Search for "Mostafa Elsayed" and replace with your name
3. Update email addresses, phone numbers, LinkedIn URL
4. Modify education, experience, and skills sections

### Change Profile Photo (Optional)
To add a profile photo:
1. Add an image to the folder (e.g., `profile.jpg`)
2. In `index.html`, replace the hero icon section:
   ```html
   <div class="hero-image">
       <img src="profile.jpg" alt="Mostafa Elsayed">
   </div>
   ```
3. Add CSS styling in `styles.css`:
   ```css
   .hero-image img {
       width: 300px;
       height: 300px;
       border-radius: 50%;
       object-fit: cover;
       border: 5px solid var(--accent-color);
   }
   ```

### Update Color Scheme
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #1a365d;      /* Main brand color */
    --secondary-color: #2c7a7b;    /* Secondary accent */
    --accent-color: #d69e2e;       /* Highlight color */
}
```

## 📊 SEO Optimized

The portfolio includes:
- Meta tags for search engines
- Open Graph tags for social media
- Semantic HTML structure
- Optimized page title and description

## 🔧 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers

## 📝 License

This portfolio template is free to use and modify for personal purposes.

## 👨‍💼 About Mostafa Elsayed

**General Accountant** with excellence grade from Alexandria University. Experienced in:
- Accounts Receivable & Payable
- Treasury & Cash Operations
- Banking Operations
- Financial Reporting & Analysis

**Contact**: MostafaElsayed0556@gmail.com

---

**Built with** ❤️ **for professional success**

