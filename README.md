# Professional Portfolio Website

A clean, responsive, and professional portfolio website built with HTML5, CSS3, and vanilla JavaScript.

## Features

✨ **Responsive Design** - Fully responsive layout that works perfectly on mobile, tablet, and desktop devices

🎨 **Modern UI** - Clean and professional design with a light color theme

⚡ **Smooth Animations** - Fade-in effects, smooth scrolling, and hover animations

📱 **Mobile Menu** - Hamburger menu that automatically appears on mobile devices

🎯 **Interactive Elements** - Contact form, project showcase, and smooth navigation

## Project Structure

```
Portfolio/
├── index.html      # Main HTML file with semantic structure
├── styles.css      # Responsive CSS with animations
├── script.js       # Vanilla JavaScript for interactivity
├── profile.jpg     # Profile picture (replace with your own)
├── resume.pdf      # Resume file (optional)
└── README.md       # This file
```

## Sections

1. **Navbar** - Fixed navigation with smooth scrolling and mobile hamburger menu
2. **Hero Section** - Profile picture, name, tagline, and CV download button
3. **About Me** - Professional bio, education, and career goals
4. **Skills** - Display of technical skills with hover animations
5. **Projects** - Showcase of 6 projects with descriptions and tech stacks
6. **Contact** - Contact form and social media links
7. **Footer** - Copyright information

## Customization Guide

### 1. Update Personal Information

Edit `index.html`:
- Change "Your Name" to your actual name
- Update the tagline and bio
- Replace social media links with your profiles

### 2. Add Your Profile Picture

- Replace `profile.jpg` with your own image (350x350px recommended)
- Or update the image source in HTML:
```html
<img src="your-image.jpg" alt="Profile Picture" class="profile-pic">
```

### 3. Update Projects

Edit the projects section in `index.html`:
- Change project titles and descriptions
- Update tech stack tags
- Add links to GitHub and live projects
- Replace project images (`project1.jpg`, `project2.jpg`, etc.)

### 4. Add Resume/CV

- Create or prepare your resume as `resume.pdf`
- Place it in the Portfolio folder
- Update the CV button link:
```html
<a href="resume.pdf" class="cv-button" download>
    <i class="fas fa-download"></i> Download CV
</a>
```

### 5. Customize Colors

Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #1a1a1a;
    --accent-color: #3498db;
    /* Update these colors to match your branding */
}
```

### 6. Update Social Links

In the contact section, update:
- LinkedIn URL
- GitHub URL
- Email address
- Twitter/other social profiles

## How to Use

1. **Open in Browser**: Simply open `index.html` in your web browser
2. **Live Server**: Use VS Code's Live Server extension for development
3. **Deploy**: Upload all files to your web hosting service

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Features Breakdown

### Responsive Design
- Mobile-first approach
- Breakpoints at 768px (tablet) and 480px (mobile)
- Flexible grid layouts with CSS Grid and Flexbox

### JavaScript Functionality
- Mobile menu toggle with hamburger icon
- Smooth scroll navigation
- Active link highlighting based on scroll position
- Intersection Observer for scroll animations
- Contact form validation and submission handling
- Keyboard navigation support

### Accessibility
- Semantic HTML5 tags
- Proper heading hierarchy
- ARIA labels where needed
- Keyboard navigation support
- Good color contrast ratios

## Customization Tips

### Change Color Scheme
Update `styles.css` root variables for a different color scheme without modifying individual components.

### Add More Projects
Copy a project card in the HTML and update the content. JavaScript handles animations automatically.

### Modify Animations
Adjust animation timings in `styles.css` under `@keyframes` sections or in JavaScript `observerOptions`.

### Add Form Backend
Currently, the contact form shows a success message locally. To actually send emails:
- Use services like Formspree, Netlify Forms, or EmailJS
- Follow their integration guides

## Performance

- Lightweight (no heavy frameworks)
- Fast load times
- Smooth animations with CSS transitions
- Optimized images recommended

## Future Enhancements

- Add dark mode toggle
- Integrate backend for contact form
- Add blog section
- Add testimonials/reviews
- Add more detailed project pages
- Add loading states

## License

This project is free to use and modify for personal portfolio purposes.

## Support

For questions or issues with the template, feel free to customize and adapt it to your needs.

---

**Built with ❤️ using HTML5, CSS3, and Vanilla JavaScript**
