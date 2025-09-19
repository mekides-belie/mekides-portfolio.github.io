# Mekides Portfolio

A modern, responsive portfolio website built with Jekyll and GitHub Pages. This portfolio showcases professional work, skills, and community involvement in a clean, professional design.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations
- **Fast Loading**: Optimized for performance and SEO
- **Easy Customization**: Simple to modify content and styling
- **GitHub Pages Ready**: Deploy directly to GitHub Pages

## Pages

- **Home**: Hero section with featured work preview
- **About**: Detailed information about skills, experience, and education
- **My Work**: Comprehensive project showcase with categories
- **Involvement**: Community activities, speaking engagements, and awards

## Getting Started

### Prerequisites

- Ruby (for Jekyll)
- Git
- GitHub account (for deployment)

### Installation

1. **Clone or download this repository**
   ```bash
   git clone [your-repo-url]
   cd MekidesPortifolio
   ```

2. **Install dependencies**
   ```bash
   bundle install
   ```

3. **Run locally**
   ```bash
   bundle exec jekyll serve
   ```

4. **View your site**
   Open `http://localhost:4000` in your browser

## Customization Guide

### 1. Update Personal Information

Edit `_config.yml` to update:
- Site title and description
- Your name and email
- Social media links
- Site URL

### 2. Replace Content

**Homepage (`index.markdown`)**:
- Update hero section text
- Modify featured work projects
- Change contact information

**About Page (`about.markdown`)**:
- Replace placeholder text with your story
- Update skills and technologies
- Add your actual experience and education
- Replace `[Your Photo Here]` with your actual photo

**My Work Page (`mywork.md`)**:
- Replace sample projects with your actual work
- Update project descriptions and technologies
- Add real project links

**Involvement Page (`involvement.md`)**:
- Update community involvement activities
- Add your actual speaking engagements
- Replace awards and recognition

### 3. Add Your Photos

1. Place your photos in `assets/images/`
2. Update image references in the HTML
3. Replace placeholder divs with actual `<img>` tags

### 4. Customize Styling

Edit `assets/css/main.css` to:
- Change color scheme
- Modify fonts
- Adjust layout and spacing
- Add custom animations

### 5. Update Social Links

In `_layouts/default.html`, update the social media links in the footer:
```html
<a href="https://github.com/yourusername" class="social-link">
<a href="https://linkedin.com/in/yourusername" class="social-link">
<a href="https://twitter.com/yourusername" class="social-link">
```

## Deployment

### GitHub Pages (Recommended)

1. **Push to GitHub**
   ```bash
   git add .
   git commit -m "Initial portfolio setup"
   git push origin main
   ```

2. **Enable GitHub Pages**
   - Go to your repository settings
   - Scroll to "GitHub Pages" section
   - Select "main" branch as source
   - Your site will be available at `https://yourusername.github.io/repository-name`

### Other Hosting Options

- **Netlify**: Drag and drop the `_site` folder
- **Vercel**: Connect your GitHub repository
- **Traditional hosting**: Upload the `_site` folder to your web server

## File Structure

```
MekidesPortifolio/
├── _config.yml          # Jekyll configuration
├── _layouts/
│   └── default.html     # Main layout template
├── assets/
│   ├── css/
│   │   └── main.css     # Main stylesheet
│   ├── js/
│   │   └── main.js      # JavaScript functionality
│   └── images/          # Your images here
├── index.markdown       # Homepage
├── about.markdown       # About page
├── mywork.md           # Work showcase
├── involvement.md      # Community involvement
├── Gemfile             # Ruby dependencies
└── README.md           # This file
```

## Customization Tips

### Adding New Pages

1. Create a new `.md` file in the root directory
2. Add front matter:
   ```yaml
   ---
   layout: default
   title: Your Page Title
   ---
   ```
3. Add the page to navigation in `_layouts/default.html`

### Adding Blog Posts

1. Create posts in `_posts/` directory
2. Use filename format: `YYYY-MM-DD-title.md`
3. Add front matter with layout: `post`

### Changing Colors

Update CSS variables in `assets/css/main.css`:
```css
:root {
  --primary-color: #2563eb;
  --secondary-color: #1f2937;
  --accent-color: #667eea;
}
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance Optimization

- Images are optimized for web
- CSS and JS are minified
- Font Awesome icons are loaded from CDN
- Google Fonts are loaded efficiently

## SEO Features

- Meta tags for all pages
- Open Graph tags for social sharing
- Structured data markup
- Sitemap generation
- Robots.txt included

## Support

If you need help customizing your portfolio:

1. Check the Jekyll documentation: https://jekyllrb.com/docs/
2. Review the GitHub Pages documentation: https://pages.github.com/
3. Look at the original repository for reference

## License

This project is open source and available under the [MIT License](LICENSE).

## Credits

- Built with [Jekyll](https://jekyllrb.com/)
- Icons by [Font Awesome](https://fontawesome.com/)
- Fonts by [Google Fonts](https://fonts.google.com/)
- Deployed on [GitHub Pages](https://pages.github.com/)

---

**Happy coding! 🚀**
