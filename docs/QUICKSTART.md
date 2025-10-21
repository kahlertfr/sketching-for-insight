# Quick Start Guide - Customizing Your Conference Poster Page

This guide will help you quickly customize the GitHub Pages site for your conference poster.

## Minimum Required Changes

To get your site up and running with your content, you need to change at least these items:

### 1. Title (2 locations)
- **File:** `index.html`
- **Line 9:** Browser tab title
- **Line 17:** Main page heading

```html
<title>Your Project Title - Conference Poster</title>
...
<h1>Your Project Title</h1>
```

### 2. Abstract Text
- **File:** `index.html`
- **Lines 31-42:** Replace placeholder paragraphs with your abstract

### 3. Contact Information
- **File:** `index.html`
- **Lines 68-72:** Update with your details

```html
<h3>Dr. Jane Smith</h3>
<p class="contact-title">Research Scientist</p>
<p class="contact-affiliation">MIT, Computer Science Department</p>
<a href="https://www.mit.edu/~jsmith" class="contact-link" target="_blank">
    View University Profile →
</a>
```

### 4. Images
Replace these files in `assets/` folder:
- **teaser.png** - Small image for abstract section (400x300 recommended)
- **poster-preview.png** - Large preview of your poster (800x1000 recommended)

### 5. PDFs
Replace these files in `assets/` folder:
- **paper.pdf** - Your 2-page conference paper
- **poster.pdf** - Your full poster PDF

## Optional Customizations

### Change Color Scheme
Edit `style.css`, line 21-22 and 76:

```css
/* Header gradient - change these color codes */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);

/* Heading color - matches the gradient */
color: #667eea;
```

Popular color schemes:
- Blue/Teal: `#667eea` → `#2b5876` 
- Green: `#56ab2f` → `#a8e063`
- Orange/Red: `#f46b45` → `#eea849`
- Pink/Purple: `#ee0979` → `#ff6a00`

### Add Social Media Links
Add to the contact section in `index.html`:

```html
<div class="social-links">
    <a href="https://twitter.com/yourusername">Twitter</a>
    <a href="https://linkedin.com/in/yourprofile">LinkedIn</a>
    <a href="https://github.com/yourusername">GitHub</a>
</div>
```

### Add More Sections
You can add additional sections like "Methodology", "Results", or "Acknowledgments" by copying the section structure:

```html
<section class="your-section-class">
    <h2>Your Section Title</h2>
    <div>
        <!-- Your content here -->
    </div>
</section>
```

## Testing Your Changes

1. Open `index.html` in a web browser
2. Check all text displays correctly
3. Click download buttons to test PDFs
4. Verify images show up
5. Test the page on mobile (resize browser window)

## Publishing to GitHub Pages

1. Push your changes to GitHub
2. Go to repository Settings → Pages
3. Under "Source", select:
   - Branch: `main` (or your working branch)
   - Folder: `/docs`
4. Click "Save"
5. Wait 2-3 minutes for deployment
6. Your site will be at: `https://kahlertfr.github.io/sketching-for-insight/`

## Tips

- Keep image file sizes under 2MB for fast loading
- Use descriptive filenames if you change asset names
- Test locally before pushing to GitHub
- Check the site works on mobile devices
- Consider adding alt text to images for accessibility

## Getting Help

For detailed instructions, see the main `README.md` in the docs folder.

For questions about GitHub Pages, visit: https://docs.github.com/en/pages
