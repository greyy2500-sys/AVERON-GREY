# Averon Grey - Luxury Streetwear Footwear Website

Welcome to the **Averon Grey** official website repository! This is a modern, responsive landing page for a premium streetwear footwear brand.

## 🎨 Features

- ✅ **Fully Responsive Design** - Mobile, tablet, and desktop optimized
- ✅ **Modern UI/UX** - Clean, minimalist aesthetic with smooth animations
- ✅ **Interactive Components** - Mobile menu, smooth scrolling, form handling
- ✅ **Fast Performance** - No external dependencies, pure HTML/CSS/JavaScript
- ✅ **Easy to Customize** - Well-organized code with clear sections
- ✅ **No Build Required** - Just open `index.html` in your browser

## 📦 What's Included

- **index.html** - Complete landing page with all sections
- **styles.css** - Custom CSS styling and animations
- **README.md** - Documentation (this file)

## 🚀 Getting Started

### View Locally
1. Clone this repository
2. Open `index.html` in your web browser
3. Done! The site will work perfectly offline

### Deploy to GitHub Pages
1. Go to repository Settings → Pages
2. Select "Deploy from a branch"
3. Choose `main` branch and `/root` folder
4. Save and your site will be live at `https://greyy2500-sys.github.io/AVERON-GREY/`

### Deploy to Other Platforms
- **Netlify**: Connect your repo and it auto-deploys
- **Vercel**: Same as Netlify, instant deployment
- **Traditional Hosting**: Upload `index.html` via FTP

## 🎯 Site Structure

### Sections
1. **Header** - Navigation bar with mobile menu
2. **Hero** - Brand intro with call-to-action
3. **About** - Brand story section
4. **Collection** - Product showcase (3 items)
5. **Features** - Why choose us section
6. **Newsletter** - Email subscription form
7. **Contact** - Social media and email
8. **Footer** - Copyright info

## 🛠️ Customization Guide

### Update Brand Information
Edit these in `index.html`:
```html
<h1>AVERON GREY</h1>  <!-- Brand name -->
<p>Luxury Streetwear Footwear Brand</p>  <!-- Tagline -->
```

### Change Colors
Modify the CSS in the `<style>` section:
```css
background: linear-gradient(135deg, #1f2937 0%, #111827 100%);  /* Hero background */
background: white;  /* Section backgrounds */
```

### Add Product Images
Replace placeholder image URLs:
```html
<img src="https://your-image-url.com/product.jpg" alt="Product Name" />
```

### Update Contact Information
```html
<p>📱 Instagram: <a href="https://instagram.com/yourusername">@yourusername</a></p>
<p>✉️ Email: <a href="mailto:your-email@example.com">your-email@example.com</a></p>
```

### Modify Social Links
Update the footer and contact section with your actual links.

## 📱 Responsive Breakpoints

- **Mobile**: < 768px - Stacked layout, hamburger menu
- **Tablet**: 768px - 1024px - Grid layout adjusts
- **Desktop**: > 1024px - Full multi-column layout

## ✨ Features Breakdown

### Mobile Menu
- Click the hamburger icon (☰) to toggle navigation
- Menu auto-closes when a link is clicked

### Smooth Scrolling
- All navigation links smoothly scroll to sections
- Enhanced UX on all browsers

### Newsletter Form
- Subscribe popup with email validation
- Placeholder form handling (connect to backend service)

### Interactive Hover Effects
- Product cards lift on hover
- Buttons scale and change on interaction
- Links have smooth color transitions

## 🔧 Advanced Customization

### Add New Sections
1. Create a new `<section>` with unique `id`
2. Add navigation link in the header
3. Style using existing CSS patterns

### Integrate Backend
To make forms work with a backend:
1. Update the `<form>` element with your endpoint
2. Remove the `onsubmit` JavaScript handler
3. Connect to your email service (Mailchimp, SendGrid, etc.)

### Add Analytics
Include tracking code in the `<head>`:
```html
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_ID"></script>
```

### Add a Blog
1. Create a `blog.html` page
2. Link from the navigation menu
3. Use the same styling for consistency

## 🐛 Troubleshooting

**Site not loading?**
- Make sure all files are in the same directory
- Check browser console for errors (F12)

**Images not showing?**
- Verify image URLs are correct
- Check for typos in file paths

**Mobile menu not working?**
- Clear browser cache (Ctrl+Shift+Delete)
- Test in incognito mode

**Styles looking off?**
- Try a different browser
- Clear all caches and refresh

## 📊 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers

## 📝 License

© 2026 Averon Grey. All rights reserved.

---

## 💡 Next Steps

1. **Customize** the content with your brand information
2. **Add real images** of your products
3. **Set up analytics** to track visitors
4. **Deploy** to production (GitHub Pages, Netlify, etc.)
5. **Connect a backend** for newsletter/contact forms
6. **Add more pages** for products, about, blog, etc.

Happy building! 🚀
