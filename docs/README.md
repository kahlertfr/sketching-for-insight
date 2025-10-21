# Sketching for Insight - GitHub Pages

This is the GitHub Pages website for the "Sketching for Insight" conference poster presentation.

## How to Customize the Content

### 1. Update the Title and Header
Edit `index.html` and modify:
- Line 9: `<title>` tag - Update the page title
- Line 17: `<h1>` tag - Update the main heading
- Line 18: `.subtitle` - Update the subtitle

### 2. Update the Abstract
Edit `index.html` in the abstract section (around line 25):
- Replace the placeholder text with your actual abstract
- Add or remove paragraphs as needed

### 3. Replace the Teaser Image
Replace the file `assets/teaser.png` with your own image:
- Recommended size: 400x300 pixels or similar aspect ratio
- Formats: PNG, JPG, or SVG
- Keep the filename as `teaser.png` or update the image source in `index.html`

### 4. Add Your Paper PDF
Replace `assets/paper.pdf` with your actual 2-page paper:
- Format: PDF
- Keep filename as `paper.pdf` or update the link in `index.html`

### 5. Add Your Poster PDF
Replace `assets/poster.pdf` with your actual poster:
- Format: PDF
- Keep filename as `poster.pdf` or update the link in `index.html`

### 6. Replace the Poster Preview Image
Replace `assets/poster-preview.png` with an image of your poster:
- Recommended size: 800x1000 pixels or similar portrait aspect ratio
- Formats: PNG or JPG
- Keep the filename or update the image source in `index.html`

### 7. Update Contact Information
Edit `index.html` in the contact section (around line 66):
- Line 68: Replace "Your Name" with your actual name
- Line 69: Replace "Position/Title" with your job title
- Line 70: Replace with your university and department
- Line 71: Update the link to your university profile page

### 8. Customize Colors and Styling
Edit `style.css` to change:
- Line 21-22: Header gradient colors
- Line 76: Section heading color
- Other styling as needed

## File Structure

```
docs/
├── index.html          # Main HTML page
├── style.css           # Stylesheet
├── README.md           # This file
└── assets/
    ├── teaser.png      # Teaser image (replace this)
    ├── poster-preview.png  # Poster preview (replace this)
    ├── paper.pdf       # 2-page paper (replace this)
    └── poster.pdf      # Full poster (replace this)
```

## Testing Locally

To test the page locally before publishing:
1. Open `index.html` in a web browser
2. Check that all links work
3. Verify images display correctly
4. Test download links

## Publishing

The GitHub Pages site is automatically published from the `docs/` folder. Any changes pushed to the repository will be reflected on the live site after a few minutes.

The site will be available at: `https://[username].github.io/sketching-for-insight/`

## Tips

- Keep file sizes reasonable for web loading (images under 2MB, PDFs under 10MB)
- Use descriptive alt text for images for accessibility
- Test the site on different devices (desktop, tablet, mobile)
- Ensure all links are working before sharing the URL
