# Emmanuel Stanslaus - Portfolio Website

A modern, responsive portfolio website showcasing Emmanuel Stanslaus's skills, projects, and professional experience as a Software Engineering student.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations and transitions
- **Interactive Navigation**: Smooth scrolling and mobile-friendly hamburger menu
- **Profile Picture Placeholder**: Dedicated space for adding your professional photo
- **Skill Showcase**: Organized display of technical skills and competencies
- **Project Portfolio**: Detailed project descriptions with icons and hover effects
- **Contact Section**: Easy-to-reach contact information and buttons

## Sections

1. **Hero Section**: Introduction with profile picture placeholder
2. **About Me**: Professional summary and contact information
3. **Technical Skills**: Categorized display of programming and technical skills
4. **Projects**: Showcase of key projects with detailed descriptions
5. **Education**: Academic background and relevant coursework
6. **Academic Strengths**: Visual representation of core competencies
7. **Contact**: Direct contact options

## How to Add Your Profile Picture

1. **Prepare your photo**: Use a professional headshot (square format works best)
2. **Upload the image**: Place your photo in the same folder as `index.html`
3. **Update the HTML**: Replace the placeholder div in the hero section:
   
   ```html
   <!-- Replace this: -->
   <div class="profile-picture-placeholder">
       <i class="fas fa-user"></i>
       <p>Your Photo Here</p>
       <small>Add your profile picture</small>
   </div>
   
   <!-- With this: -->
   <img src="your-photo-name.jpg" alt="Emmanuel Stanslaus" class="profile-picture">
   ```

4. **Update the CSS**: Add styles for your profile picture in `styles.css`:
   
   ```css
   .profile-picture {
       width: 300px;
       height: 300px;
       border-radius: 50%;
       object-fit: cover;
       border: 4px solid rgba(255, 255, 255, 0.3);
       box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
   }
   ```

## Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript**: Interactive features and smooth animations
- **Font Awesome**: Professional icons
- **Google Fonts**: Inter font family for clean typography

## Customization

### Colors
The main color scheme uses:
- Primary: `#2563eb` (Blue)
- Secondary: `#667eea` to `#764ba2` (Purple gradient)
- Background: `#f8f9fa` (Light gray)
- Text: `#333` (Dark gray)

To change colors, modify the CSS variables at the top of `styles.css`.

### Fonts
The site uses Inter font from Google Fonts. To change:
1. Update the Google Fonts link in `index.html`
2. Modify the `font-family` property in `styles.css`

### Content
All content is easily editable in `index.html`. Simply update the text within the appropriate sections.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance

- Optimized images and assets
- Minimal JavaScript for fast loading
- CSS animations using GPU acceleration
- Responsive images for different screen sizes

## Deployment

This portfolio can be easily deployed to:
- Netlify
- Vercel
- GitHub Pages
- Any static hosting service

Simply upload the three files (`index.html`, `styles.css`, `script.js`) to your hosting platform.

## File Structure

```
PORTFOLIO/
├── index.html          # Main HTML structure
├── styles.css          # All styling and responsive design
├── script.js           # Interactive features and animations
└── README.md          # This documentation file
```

## Getting Started

1. Open `index.html` in your web browser to view the portfolio
2. Customize the content with your personal information
3. Add your profile photo (see instructions above)
4. Deploy to your preferred hosting platform

## Support

If you need help customizing or have questions about the portfolio, feel free to reach out to Emmanuel Stanslaus at estanslaus26@gmail.com.

---

© 2024 Emmanuel Stanslaus. All rights reserved.
