# Daphné Jouanneteau - Portfolio Website

## What's Included

This folder contains your complete portfolio website:

- `index.html` - The main website file (all your content)
- `styles.css` - The design/styling file (colors, fonts, spacing)
- `images/` - Folder with all your photos
- `README.md` - This instruction file

## How to View Locally

1. Open the `index.html` file in any web browser (Chrome, Safari, Firefox)
2. That's it! Your site will display exactly as it will online.

## How to Edit Content

### Editing Text

1. Open `index.html` in any text editor (Notepad, TextEdit, VS Code, etc.)
2. Find the text you want to change
3. Edit it directly
4. Save the file
5. Refresh your browser to see changes

**Example locations:**
- Your bio: Look for `<div class="bio">`
- Project titles: Look for `<h3 class="project-title">`
- Project descriptions: Look for `<p class="project-description">`

### Editing Design (Colors, Fonts, Sizes)

1. Open `styles.css` in a text editor
2. At the very top, you'll see "CSS VARIABLES"
3. Edit these values to change the design

**What you can easily change:**

```css
/* COLORS */
--color-background: #f9f7f2;    /* Page background color */
--color-text-primary: #3d2f2a;  /* Main text color */
--color-accent: #c9b499;        /* Accent color */

/* FONT SIZES */
--text-bio: 22px;              /* Bio text size */
--text-project-title: 20px;    /* Project title size */
--text-project-desc: 15px;     /* Project description size */

/* SPACING */
--spacing-lg: 80px;            /* Large spacing between sections */
```

### Updating Your Email

In `index.html`, find:
```html
<a href="mailto:daphne@example.com">Get in touch</a>
```

Replace `daphne@example.com` with your actual email.

## Deployment Options

### Option 1: Squarespace (What you mentioned)

You'll need to manually recreate this design in Squarespace:
1. Use their page builder
2. Set fonts to Spectral and IBM Plex Mono
3. Match the colors from the CSS variables
4. Copy/paste your text content
5. Upload the images

**Note:** This is more work but gives you Squarespace's CMS.

### Option 2: Netlify (Recommended - FREE & EASY)

1. Go to [netlify.com](https://www.netlify.com)
2. Sign up (free)
3. Drag the entire `portfolio-site` folder onto their dashboard
4. Done! Your site is live with a URL like `yourname.netlify.app`
5. You can add a custom domain later

**To update:**
- Edit files on your computer
- Drag the folder back to Netlify
- Site updates automatically

### Option 3: GitHub Pages (FREE)

1. Create a GitHub account
2. Create a new repository
3. Upload these files
4. Enable GitHub Pages in settings
5. Site goes live at `yourusername.github.io/repository-name`

## Need Help?

If you run into issues:
- Text me what's not working
- Send a screenshot
- I can walk you through any step

## File Structure

```
portfolio-site/
├── index.html              (Your main page)
├── styles.css              (All design/styling)
├── images/
│   ├── daphne-portrait.jpg (Your bio photo)
│   ├── lightbox-1.jpg      (Project images)
│   ├── lightbox-2.jpg
│   ├── mbsc.jpg
│   ├── alchemy.jpg
│   └── les-champs.jpg
└── README.md               (This file)
```

---

**Remember:** The site is fully functional right now. Open `index.html` in a browser to see it working.
