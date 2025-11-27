# Maher Lahlouh - Personal Portfolio Website

A modern, responsive personal portfolio website showcasing my skills, experience, projects, and achievements as a Mobile & Web Developer.

## 🚀 Features

- **Modern & Clean Design**: Professional UI with smooth animations and transitions
- **Fully Responsive**: Works seamlessly on desktop, tablet, and mobile devices
- **Dark/Light Mode**: Toggle between dark and light themes with persistent preference
- **Smooth Scrolling**: Enhanced navigation experience with smooth scroll behavior
- **Interactive Sections**: 
  - Home with hero section
  - About me with professional summary
  - Skills (Technical & Soft) with expandable accordions
  - Professional Experience timeline
  - Projects showcase with hover effects
  - Education details
  - Certificates gallery
  - Contact form and information
- **Sticky Navigation**: Header stays visible while scrolling
- **Scroll to Top**: Quick navigation back to top
- **Download CV**: Direct link to download resume

## 📁 File Structure

```
My Portfolio/
│
├── index.html          # Main HTML file with all sections
├── style.css           # Complete styling with dark/light theme support
├── script.js           # JavaScript for interactivity and animations
├── README.md           # Project documentation
│
└── assets/             # Assets folder (images, icons, documents)
    ├── profile.jpg      # Profile picture (to be added)
    ├── project-techspot.jpg  # Project screenshot (to be added)
    └── CV_Maher_Lahlouh.pdf  # Resume PDF (to be added)
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with CSS Variables, Flexbox, Grid
- **JavaScript (Vanilla)**: No frameworks, pure JavaScript
- **Google Fonts**: Poppins & Inter font families
- **Font Awesome**: Icons library

## 📋 Setup Instructions

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- A code editor (VS Code, Sublime Text, etc.)
- Basic knowledge of HTML, CSS, and JavaScript (for customization)

### Installation

1. **Clone or Download** this repository to your local machine

2. **Navigate** to the project directory:
   ```bash
   cd "My Portfolio"
   ```

3. **Add Required Assets**:
   - Add your profile picture as `assets/profile.jpg` (recommended: 200x200px or larger, square format)
   - Add project screenshots (e.g., `assets/project-techspot.jpg`)
   - Add your CV PDF as `assets/CV_Maher_Lahlouh.pdf`

4. **Open** `index.html` in your web browser:
   - Double-click the file, or
   - Use a local server (recommended for development):
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # Using Node.js (http-server)
     npx http-server
     
     # Using PHP
     php -S localhost:8000
     ```
   - Then visit `http://localhost:8000` in your browser

## 🎨 Customization Guide

### Changing Colors

The color scheme is controlled by CSS variables in `style.css`. To change the primary color:

1. Open `style.css`
2. Find the `:root` section
3. Modify the `--hue-color` variable:
   ```css
   --hue-color: 250; /* Purple: 250, Green: 142, Blue: 230, Pink: 340 */
   ```

### Updating Content

#### Personal Information
- Edit the `<title>` tag in `index.html`
- Update name, title, and description in the Home section
- Modify contact information in the Contact section

#### Skills
- Add or remove skills in the Skills section
- Adjust skill percentages in `style.css` (e.g., `.skills__cpp { width: 90%; }`)

#### Experience & Education
- Update job titles, companies, dates, and descriptions
- Add or remove experience entries

#### Projects
- Add new project cards in the Projects section
- Update project images, descriptions, and tech stacks

#### Certificates
- Add or remove certificate cards
- Update certificate names

### Adding New Sections

1. Add HTML structure in `index.html`
2. Add corresponding styles in `style.css`
3. Update navigation menu if needed
4. Add any JavaScript functionality in `script.js`

## 🚀 Deployment

### GitHub Pages

1. **Create a GitHub repository** (if you haven't already)

2. **Push your code** to GitHub:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/yourusername/your-repo-name.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**:
   - Go to your repository on GitHub
   - Click on **Settings**
   - Scroll down to **Pages** section
   - Under **Source**, select `main` branch
   - Click **Save**
   - Your site will be available at `https://yourusername.github.io/your-repo-name/`

### Netlify

1. **Sign up/Login** to [Netlify](https://www.netlify.com/)

2. **Deploy via Drag & Drop**:
   - Go to Netlify dashboard
   - Drag and drop your project folder
   - Your site will be live instantly!

3. **Deploy via Git**:
   - Connect your GitHub repository
   - Netlify will automatically deploy on every push
   - Customize build settings if needed (not required for static sites)

4. **Custom Domain** (Optional):
   - Go to **Domain settings**
   - Add your custom domain
   - Follow DNS configuration instructions

### Vercel

1. **Sign up/Login** to [Vercel](https://vercel.com/)

2. **Import your project**:
   - Click **New Project**
   - Import from GitHub or upload directly
   - Deploy!

### Other Hosting Options

- **Firebase Hosting**: `firebase deploy`
- **AWS S3 + CloudFront**: Static website hosting
- **Surge.sh**: `surge` command-line tool
- **Any web hosting service**: Upload files via FTP

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🔧 Troubleshooting

### Images Not Showing
- Ensure image files are in the `assets/` folder
- Check file names match exactly (case-sensitive)
- Verify image file extensions (.jpg, .png, etc.)

### Dark Mode Not Working
- Clear browser cache
- Check browser console for JavaScript errors
- Ensure `script.js` is properly linked in `index.html`

### Contact Form Not Sending
- The contact form is currently UI-only (no backend)
- To make it functional, integrate with:
  - Formspree
  - EmailJS
  - Your own backend API
  - Netlify Forms (if deployed on Netlify)

### Styling Issues
- Clear browser cache
- Check CSS file is properly linked
- Verify CSS syntax is correct
- Use browser DevTools to inspect elements

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

**Maher Lahlouh**
- Email: maherlahlouh6@gmail.com
- Phone: +962 782913566
- GitHub: [github.com/MaherLahlouh](https://github.com/MaherLahlouh)

## 🙏 Acknowledgments

- Design inspiration from modern portfolio templates
- Icons by [Font Awesome](https://fontawesome.com/)
- Fonts by [Google Fonts](https://fonts.google.com/)

## 📄 Notes

- Remember to add your actual profile picture and project images to the `assets/` folder
- Update the CV PDF link with your actual resume
- Customize colors, fonts, and content to match your personal brand
- Test the website on multiple devices and browsers before deploying
- Consider adding analytics (Google Analytics) for tracking visitors

---

**Built with ❤️ by Maher Lahlouh**


