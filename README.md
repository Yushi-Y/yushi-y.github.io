# Personal Website

A simple and aesthetically pleasing personal website built for GitHub Pages.

## Features

- Clean, minimalist design
- Responsive layout (mobile-friendly)
- Smooth scrolling navigation
- Animated elements
- Social media integration
- Project showcase section

## Setup Instructions

### 1. Customize Your Information

Edit the following in `index.html`:

- Replace "Your Name" with your actual name
- Update the tagline/description
- Add your bio in the About section
- Update social media links (GitHub, LinkedIn, Email)
- Add your projects with descriptions and links
- Replace `profile.jpg` with your own profile picture

### 2. Deploy to GitHub Pages

#### Option A: Deploy to yourusername.github.io

1. Create a new repository on GitHub named `yourusername.github.io` (replace `yourusername` with your actual GitHub username)
2. Add the remote and push:

```bash
cd personal-website
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/yourusername/yourusername.github.io.git
git push -u origin main
```

3. Your site will be live at `https://yourusername.github.io`

#### Option B: Deploy to a project repository

1. Create a new repository on GitHub (any name)
2. Push your code:

```bash
cd personal-website
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/yourusername/repository-name.git
git push -u origin main
```

3. Go to repository Settings > Pages
4. Under "Source", select "main" branch and "/" (root) folder
5. Click Save
6. Your site will be live at `https://yourusername.github.io/repository-name`

## Customization

### Colors

Edit the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #2c3e50;
    --secondary-color: #3498db;
    --text-color: #333;
    --light-text: #666;
    --bg-color: #ffffff;
    --bg-secondary: #f8f9fa;
    --border-color: #e9ecef;
    --hover-color: #2980b9;
}
```

### Adding a Profile Picture

1. Add your image file to the repository (e.g., `profile.jpg`)
2. Update the image source in `index.html`:

```html
<img src="profile.jpg" alt="Your Name">
```

### Adding More Sections

Copy the section structure and customize:

```html
<section id="new-section" class="section">
    <h2>Section Title</h2>
    <p>Your content here</p>
</section>
```

Don't forget to add a navigation link:

```html
<a href="#new-section" class="nav-link">New Section</a>
```

## File Structure

```
personal-website/
├── index.html       # Main HTML file
├── styles.css       # Stylesheet
├── script.js        # JavaScript for interactions
├── README.md        # This file
└── profile.jpg      # Your profile picture (add this)
```

## Technologies Used

- HTML5
- CSS3 (with CSS Grid and Flexbox)
- Vanilla JavaScript
- Google Fonts (Inter)

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

Feel free to use this template for your own personal website.
