# Personal Portfolio Website

A modern, responsive portfolio website for software engineers built with HTML, CSS, and JavaScript. Features a clean design, smooth animations, and sections for showcasing projects, skills, and contact information.

## 🌟 Features

- **Responsive Design**: Fully responsive layout that works on all devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Project Showcase**: Display your work with beautiful project cards
- **Skills Section**: Organized categorization of your technical skills
- **Contact Form**: Built-in contact form (ready for backend integration)
- **Smooth Scrolling**: Seamless navigation between sections
- **Interactive Elements**: Hover effects, animations, and parallax scrolling
- **Mobile Menu**: Hamburger menu for mobile devices
- **Scroll to Top**: Convenient button to return to the top
- **SEO Friendly**: Semantic HTML and meta tags

## 🚀 Quick Start

### View Locally

1. Clone or download this repository
2. Open `index.html` in your web browser
3. That's it! No build process or dependencies required.

### Deploy to the Web

You can deploy this website to various free hosting platforms:

#### Netlify (Recommended)
1. Sign up at [netlify.com](https://www.netlify.com/)
2. Drag and drop the project folder
3. Your site is live!

#### GitHub Pages
1. Create a GitHub repository
2. Push your code to the repository
3. Go to Settings > Pages
4. Select the main branch and save
5. Your site will be live at `https://yourusername.github.io/repository-name`

#### Vercel
1. Sign up at [vercel.com](https://vercel.com/)
2. Import your project
3. Deploy with one click

## 🎨 Customization

### Update Your Information

1. **Personal Details**: Open `index.html` and replace:
   - `Your Name` with your actual name
   - `your.email@example.com` with your email
   - Social media links with your profiles
   - Location and phone number

2. **About Section**: Edit the about text to reflect your experience and background

3. **Projects**: Update the project cards with your actual projects:
   - Change project titles and descriptions
   - Update project images (replace placeholder URLs)
   - Modify technology tags
   - Add links to live demos and GitHub repos

4. **Skills**: Customize the skills sections with your technologies

5. **Colors**: Edit the CSS variables in `styles.css` to change the color scheme:
```css
:root {
    --primary-color: #667eea;
    --secondary-color: #764ba2;
    --accent-color: #f093fb;
    /* ... more colors */
}
```

### Add Your Project Images

Replace the placeholder images with your actual project screenshots:
1. Add your images to an `images` folder
2. Update the `src` attribute in the image tags
3. Recommended size: 600x400px for consistency

### Contact Form Integration

The contact form is currently set up with a basic JavaScript handler. To make it functional, integrate with one of these services:

#### Option 1: Formspree (Easiest)
1. Sign up at [formspree.io](https://formspree.io/)
2. Add this to your form tag:
```html
<form class="contact-form" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

#### Option 2: EmailJS
1. Sign up at [emailjs.com](https://www.emailjs.com/)
2. Follow their integration guide
3. Update the JavaScript in `script.js`

#### Option 3: Netlify Forms
1. Add `netlify` attribute to your form tag
2. Deploy to Netlify
3. Forms will automatically work

## 📁 Project Structure

```
personal-website/
│
├── index.html          # Main HTML file
├── styles.css          # All styling
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🎯 Sections Included

1. **Navigation**: Fixed navbar with smooth scrolling
2. **Hero**: Eye-catching introduction with call-to-action buttons
3. **About**: Personal introduction and statistics
4. **Projects**: Showcase of 6 featured projects with tags
5. **Skills**: Categorized skills in 6 areas (Frontend, Backend, Database, DevOps, Mobile, Tools)
6. **Contact**: Contact form and information
7. **Footer**: Copyright and credits

## 🛠️ Technologies Used

- HTML5
- CSS3 (with CSS Variables and Grid/Flexbox)
- Vanilla JavaScript (ES6+)
- Font Awesome Icons (via CDN)

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 💡 Tips for Success

1. **High-Quality Projects**: Showcase your best 4-6 projects rather than listing everything
2. **Professional Photos**: Use clear, professional screenshots for your projects
3. **Keep It Updated**: Regularly update your portfolio with new projects and skills
4. **Test Responsiveness**: Check your site on multiple devices
5. **Optimize Images**: Compress images for faster loading
6. **Add Analytics**: Consider adding Google Analytics to track visitors
7. **Custom Domain**: Use a custom domain for a more professional appearance

## 📝 Customization Ideas

- Add a blog section
- Include testimonials from clients/colleagues
- Add a resume/CV download button
- Integrate with GitHub API to show latest repositories
- Add a dark/light mode toggle
- Include certifications section
- Add achievement badges
- Create a timeline of your career

## 🔧 Optional Enhancements

The `script.js` file includes commented code for optional features:
- Typing animation effect
- Project filtering by technology
- Theme toggle (light/dark mode)

Uncomment and customize these as needed!

## 📧 Contact Form Backend

For a production-ready contact form, consider these options:
- **Formspree**: Free tier available, easy setup
- **EmailJS**: Send emails directly from JavaScript
- **Netlify Forms**: Built-in if hosting on Netlify
- **Custom Backend**: Node.js + Nodemailer or similar

## 🎓 Learning Resources

If you want to extend this portfolio further:
- [MDN Web Docs](https://developer.mozilla.org/)
- [CSS-Tricks](https://css-tricks.com/)
- [JavaScript.info](https://javascript.info/)

## 📄 License

Feel free to use this template for your personal portfolio! No attribution required, though it's appreciated.

## 🤝 Contributing

Found a bug or have a suggestion? Feel free to fork this project and submit improvements!

---

**Built with ❤️ and code**

Good luck with your portfolio! 🚀

