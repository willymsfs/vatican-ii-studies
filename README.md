# Vatican II: The Battle for Meaning - Website

A comprehensive digital resource exploring Massimo Faggioli's analysis of the Second Vatican Council and its ongoing interpretation debates. This website preserves and organizes detailed theological discussions, historical context, and scholarly analysis in an elegant, accessible format.

## Features

- **Royal Academic Design**: Sophisticated styling with deep navy blue, rich gold, and ivory colors
- **Responsive Layout**: Optimized for desktop, tablet, and mobile devices
- **Comprehensive Content**: All original headings and detailed explanations preserved
- **Easy Navigation**: Organized across multiple pages for better user experience
- **Accessibility**: Screen reader friendly with proper semantic structure

## Website Structure

### Main Pages
- `index.html` - Homepage with overview and navigation
- `chapter1.html` - A Short History of the Debate on Vatican II
- `chapter2.html` - Questioning the Legitimacy of Vatican II
- `chapter3.html` - Vatican II: Beyond Rome
- `theologians.html` - The Theologians of Vatican II: A Clash of Visions

### Additional Pages (Template Ready)
- `chapter4.html` - The Church and the World: Augustinians and Thomists
- `chapter5.html` - The Clash of Narratives
- `chapter6.html` - Macro-Issues of the Debate About Vatican II
- Theme-specific pages for key topics and controversies

## Deployment to GitHub Pages

### Option 1: Direct Repository Deployment

1. **Create a new GitHub repository**:
   - Go to GitHub.com and create a new repository
   - Name it something like `vatican-ii-studies` or `vatican-ii-website`
   - Make it public for GitHub Pages to work

2. **Upload files**:
   - Upload all files from the `vatican-ii-website` folder to your repository
   - Maintain the folder structure (css/, js/, images/)

3. **Enable GitHub Pages**:
   - Go to repository Settings
   - Scroll down to "Pages" section
   - Under "Source", select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click "Save"

4. **Access your website**:
   - Your site will be available at: `https://[username].github.io/[repository-name]`
   - It may take a few minutes to deploy

### Option 2: Using docs/ Folder

1. **Create docs folder structure**:
   ```
   repository/
   ├── docs/
   │   ├── index.html
   │   ├── css/
   │   ├── js/
   │   └── [all other files]
   └── README.md
   ```

2. **In GitHub Pages settings**:
   - Choose "main" branch and "/docs" folder as source

### Option 3: Using GitHub Desktop

1. **Clone or create repository locally**
2. **Copy all website files to the repository folder**
3. **Commit and push changes**
4. **Enable GitHub Pages in repository settings**

## File Structure

```
vatican-ii-website/
├── index.html              # Homepage
├── chapter1.html           # Chapter 1 page
├── chapter2.html           # Chapter 2 page
├── chapter3.html           # Chapter 3 page
├── theologians.html        # Theologians page
├── css/
│   └── styles.css          # Main stylesheet
├── js/
│   └── main.js             # JavaScript functionality
├── images/                 # Image assets (if any)
└── README.md               # This file
```

## Customization

### Colors
The color palette is defined in CSS variables in `styles.css`:
- `--primary-navy: #1B365D`
- `--rich-gold: #D4AF37`
- `--ivory-cream: #F8F6F0`
- `--burgundy: #8B1538`

### Fonts
- Headings: Playfair Display (Google Fonts)
- Body text: Source Sans Pro (Google Fonts)

### Adding New Pages
1. Copy the structure from any existing page
2. Update the content in the main container
3. Add navigation links in the main index.html
4. Ensure consistent styling and navigation

## Browser Compatibility

- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile responsive design
- Progressive enhancement for older browsers

## Content Attribution

This website is an educational resource based on Massimo Faggioli's scholarly work "Vatican II: The Battle for Meaning." All content is preserved in its original form for academic and educational purposes.

## Technical Notes

- Pure HTML/CSS/JavaScript (no build process required)
- Google Fonts loaded via CDN
- Semantic HTML structure for accessibility
- CSS Grid and Flexbox for responsive layout
- Smooth scrolling and interactive elements

## Support

For technical issues or questions about deployment, refer to the [GitHub Pages documentation](https://docs.github.com/en/pages).

---

**Note**: This is an educational resource designed for scholarly research and study of Vatican II and its theological implications.

