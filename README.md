# Landon Brown - Professional Website

A modern, responsive personal website showcasing academic achievements, professional experience, creative projects, and artistic work.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations
- **Multi-page Structure**: Separate pages for About, Resume, Projects, Art, and Contact
- **GitHub Pages Ready**: Optimized for easy deployment on GitHub Pages
- **SEO Friendly**: Proper meta tags and semantic HTML structure

## Pages

1. **About** (`index.html`) - Personal introduction and background
2. **Resume** (`resume.html`) - Education, experience, and awards
3. **Projects** (`projects.html`) - Academic and professional projects
4. **Art** (`art.html`) - Creative work and musical compositions
5. **Contact** (`contact.html`) - Contact information and links

## Hosting on GitHub Pages

### Method 1: Using GitHub's Web Interface

1. **Create a new repository** on GitHub named `yourusername.github.io` (replace `yourusername` with your actual GitHub username)

2. **Upload files** to the repository:
   - Go to your repository on GitHub
   - Click "Add file" → "Upload files"
   - Drag and drop all the website files (HTML, CSS, JS, and public folder)
   - Commit the changes

3. **Enable GitHub Pages**:
   - Go to repository Settings
   - Scroll down to "Pages" section
   - Under "Source", select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click "Save"

4. **Access your website** at `https://yourusername.github.io`

### Method 2: Using Git Command Line

1. **Initialize git repository** in your project folder:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   ```

2. **Create GitHub repository** and push:
   ```bash
   git remote add origin https://github.com/yourusername/yourusername.github.io.git
   git branch -M main
   git push -u origin main
   ```

3. **Enable GitHub Pages** (same as Method 1, step 3)

## File Structure

```
website/
├── index.html          # Homepage (About page)
├── resume.html         # Resume/CV page
├── projects.html       # Projects page
├── art.html           # Art & Music page
├── contact.html       # Contact page
├── styles.css         # Main stylesheet
├── script.js          # JavaScript functionality
├── README.md          # This file
└── public/
    ├── images/        # All images and logos
    └── background/    # Background media files
```

## Customization

### Updating Content

- **Personal Information**: Edit the content in each HTML file
- **Images**: Replace images in the `public/images/` folder
- **Styling**: Modify `styles.css` for design changes
- **Colors**: Update CSS custom properties for theme changes

### Adding New Pages

1. Create a new HTML file following the existing structure
2. Add navigation link in all HTML files' nav menus
3. Update the navigation in `script.js` if needed

## Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript**: Interactive features and animations
- **Google Fonts**: Inter font family
- **SVG Icons**: Scalable vector graphics for social links

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance Features

- Optimized images and assets
- Efficient CSS with minimal redundancy
- Smooth animations and transitions
- Mobile-first responsive design
- Fast loading times

## License

This project is open source and available under the MIT License.

## Contact

For questions about this website template or to report issues, please contact [your-email@example.com](mailto:your-email@example.com).
# personal-website
# personal-website
