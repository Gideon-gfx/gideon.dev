# Gideon Solomon - Web Developer Portfolio

A modern, responsive portfolio website showcasing your web development skills and projects.

## 📁 Project Structure

```
My portfolio/
├── index.html       # Main HTML file
├── styles.css       # Styling and responsive design
├── script.js        # Interactive features
└── README.md        # This file
```

## ✨ Features

- **Modern Design**: Clean and professional layout with gradient accents
- **Fully Responsive**: Works seamlessly on desktop, tablet, and mobile devices
- **Smooth Animations**: CSS animations and transitions for better UX
- **Interactive Elements**: Mobile menu toggle, smooth scrolling, form handling
- **Dark Mode Ready**: Easy to customize color scheme
- **TypeWriter Effect**: Animated subtitle on hero section
- **Project Showcase**: Display your featured projects with descriptions
- **Skills Section**: Organized by categories (Frontend, Backend, Database, Tools)
- **Contact Form**: Get in touch section with form validation
- **Social Links**: Easy access to your social profiles

## 🎨 Customization Guide

### 1. **Contact Information**
Replace the placeholder contact details in `index.html`:

```html
<a href="mailto:your.email@example.com">your.email@example.com</a>
<a href="tel:+234XXXXXXXXXX">+234 XXX XXX XXXX</a>
<a href="#">www.gideonsolomon.dev</a>
```

### 2. **Social Media Links**
Update the social links in the contact section:

```html
<a href="https://github.com/yourusername" class="social-link"><i class="fab fa-github"></i></a>
<a href="https://linkedin.com/in/yourusername" class="social-link"><i class="fab fa-linkedin"></i></a>
<a href="https://twitter.com/yourusername" class="social-link"><i class="fab fa-twitter"></i></a>
```

### 3. **Profile Picture**
Replace the image placeholder with your actual profile picture:

```html
<div class="about-image">
    <img src="path/to/your/photo.jpg" alt="Your Name" class="profile-img">
</div>
```

Add this CSS for the image:
```css
.profile-img {
    width: 300px;
    height: 300px;
    border-radius: 20px;
    object-fit: cover;
    box-shadow: var(--shadow);
}
```

### 4. **Color Scheme**
Customize the color palette in `styles.css`:

```css
:root {
    --primary-color: #6366f1;      /* Main color */
    --secondary-color: #ec4899;    /* Accent color */
    --dark-bg: #0f172a;
    --light-bg: #f8fafc;
    --text-dark: #1e293b;
    --text-light: #64748b;
}
```

### 5. **Add More Projects**
Add additional projects by duplicating the project card:

```html
<div class="project-card">
    <div class="project-image">
        <i class="fas fa-icon-name"></i>
    </div>
    <div class="project-content">
        <h3 class="project-title">Your Project Name</h3>
        <p class="project-description">Your project description</p>
        <div class="project-tech">
            <span class="tech-tag">Technology</span>
        </div>
        <a href="project-link" target="_blank" class="project-link">Visit Project <i class="fas fa-arrow-right"></i></a>
    </div>
</div>
```

### 6. **Update Skills**
Edit the skills section in `index.html` to add/remove skills as needed.

### 7. **Email Form Setup**
For fully functional email sending, you have a few options:

**Option A: Use Formspree (Simple)**
```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST" class="contact-form">
    <!-- form fields -->
</form>
```

**Option B: Use EmailJS (JavaScript)**
Visit [EmailJS](https://www.emailjs.com/) and follow their setup guide.

**Option C: Use a Backend Service**
Connect to a backend API for handling form submissions.

## 🚀 Deployment

### Option 1: **GitHub Pages**
1. Create a GitHub account if you don't have one
2. Create a new repository named `portfolio`
3. Push the files to the repository
4. Go to Settings → Pages → Select main branch
5. Your portfolio will be live at `https://yourusername.github.io/portfolio`

### Option 2: **Netlify**
1. Go to [Netlify](https://www.netlify.com/)
2. Sign up with GitHub
3. Click "New site from Git"
4. Connect your portfolio repository
5. Deploy automatically on each push

### Option 3: **Vercel**
1. Go to [Vercel](https://vercel.com/)
2. Sign up with GitHub
3. Import your portfolio repository
4. Your site will be live instantly

### Option 4: **Traditional Hosting**
Upload the files to your web hosting provider via FTP or File Manager.

## 🛠️ Tools Used

- **HTML5**: Semantic markup structure
- **CSS3**: Modern styling with flexbox and grid
- **JavaScript**: Interactive features and animations
- **Font Awesome**: Icon library
- **Google Fonts**: Typography (can be added)

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📝 Important Notes

1. Update all placeholder text with your actual information
2. Replace contact email and phone number
3. Update social media profile links
4. Add your actual profile picture
5. Keep the projects section updated as you complete new projects
6. Test responsiveness on different devices

## 🎯 SEO Tips

1. Update the page title in `index.html`
2. Add meta description: `<meta name="description" content="Your portfolio description">`
3. Add meta keywords if needed
4. Ensure all images have alt text
5. Use semantic HTML tags

## 💡 Performance Tips

1. Optimize images before adding them
2. Use WebP format for better compression
3. Minify CSS and JavaScript for production
4. Enable caching on your hosting
5. Use a CDN for assets

## 📞 Support & Resources

- [MDN Web Docs](https://developer.mozilla.org/)
- [CSS Tricks](https://css-tricks.com/)
- [JavaScript Info](https://javascript.info/)
- [Web Design Resources](https://www.webdesignresources.net/)

## 📄 License

This portfolio template is free to use and customize for personal use.

---

**Happy coding! 🚀**

Feel free to modify and personalize this portfolio to match your unique style and needs.
