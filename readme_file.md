# Southpaw Handmade Blog

A whimsical, creative blog for makers who believe ordinary is overrated. Part of the "Permission to Play" series.

## 📋 Overview

This is a static HTML/CSS/JS blog designed for Southpaw Handmade, a surface pattern and sewing business that transforms everyday projects into whimsical adventures. The blog celebrates creativity, whimsy, and the importance of play in adult life.

## 🎨 Design Features

- **Color Palette:**
  - Primary Purple: `#6B4C9A`
  - Teal Blue: `#5B9AA6`
  - Mint Green: `#9DD9C5`
  - Cream: `#FAF3E0`
  - Pale Grey: `#E8E8E8`

- **Responsive Design:** Works beautifully on desktop, tablet, and mobile
- **Smooth Animations:** Hover effects, floating elements, gradient backgrounds
- **Accessibility:** Semantic HTML, proper contrast ratios

## 📁 File Structure

```
southpaw-blog/
├── index.html (or blog.html)           # Main blog landing page
├── coming-soon.html                     # Placeholder for future pages
├── whatever-happened-to-whimsy.html     # Sample blog post
└── README.md                            # This file
```

## 🚀 Quick Start

### Installation

1. Download all files to your computer
2. Keep them in the same folder/directory
3. Upload to your web hosting via FTP or hosting control panel

### Going Live

**Option 1: Standard Hosting**
- Upload files via FTP to your web host
- Rename `index.html` to match your hosting requirements if needed
- Navigate to your domain to view

**Option 2: Quick Testing Locally**
- Double-click `index.html` (or `blog.html`) to open in your browser
- Test all links and functionality
- When ready, upload to your hosting

### Recommended File Names
- Main blog page: `blog.html` or `index.html`
- Individual posts: Use descriptive URLs like `whatever-happened-to-whimsy.html`

## ✍️ Adding New Blog Posts

### Step 1: Create the Post File

1. Duplicate `whatever-happened-to-whimsy.html`
2. Rename it (e.g., `magic-in-details.html`)
3. Open in a text editor

### Step 2: Update the Content

Edit these sections in your new file:

```html
<!-- Line 6: Page Title -->
<title>Your New Title | Southpaw Handmade</title>

<!-- Line 7: Meta Description -->
<meta name="description" content="Your post description">

<!-- Line 238: Post Title -->
<h1 class="post-title">Your New Title</h1>

<!-- Line 240: Date and Read Time -->
<span>📅 January 15, 2026</span>
<span>☕ 5 min read</span>

<!-- Line 244: Featured Image Icon -->
<div class="featured-image">🌟</div>

<!-- Inside .post-content: Replace all blog text -->
```

### Step 3: Link from Main Blog Page

In `index.html` (or `blog.html`), find the blog card you want to update:

```html
<!-- Change this: -->
<a href="#" class="read-more">Read More →</a>

<!-- To this: -->
<a href="your-new-post.html" class="read-more">Read More →</a>
```

### Step 4: Update Related Posts

At the bottom of each blog post, update the "Continue Reading" section to link to your other posts.

## 🎯 Customization Guide

### Changing Colors

Edit the CSS variables in any HTML file:

```css
:root {
    --primary: #6B4C9A;      /* Main purple */
    --secondary: #5B9AA6;    /* Teal blue */
    --accent: #9DD9C5;       /* Mint green */
    --cream: #FAF3E0;        /* Background cream */
    --pale-grey: #E8E8E8;    /* Light grey */
}
```

### Changing Fonts

Current fonts:
- Headers: 'Brush Script MT' (cursive)
- Body: 'Georgia' (serif)
- Buttons/Nav: 'Trebuchet MS' (sans-serif)

To change, edit the `font-family` properties in the CSS.

### Adding Social Media Links

In the footer, update these placeholders:

```html
<a href="#" title="Instagram">📷</a>          <!-- Add your Instagram URL -->
<a href="#" title="Pinterest">📌</a>          <!-- Add your Pinterest URL -->
<a href="#" title="Facebook">👍</a>           <!-- Add your Facebook URL -->
<a href="#" title="YouTube">▶️</a>            <!-- Add your YouTube URL -->
```

### Replacing Emoji Placeholders

The featured images use emojis as placeholders. To use actual images:

```html
<!-- Current: -->
<div class="featured-image">🎨</div>

<!-- Replace with: -->
<div class="featured-image" style="background-image: url('images/your-photo.jpg'); background-size: cover;">
</div>
```

## 📝 Content Guidelines

### Blog Post Best Practices

1. **Title:** Use the blog post title format: Creative, engaging, question-based
2. **Length:** Aim for 1,000-2,000 words (5-10 min read)
3. **Structure:** Use H2 and H3 headers to break up content
4. **Tone:** Warm, encouraging, whimsical but authentic
5. **CTAs:** Include 1-2 calls-to-action linking to patterns/products

### SEO Tips

- Fill in meta descriptions (155 characters max)
- Use descriptive file names (e.g., `permission-to-play.html` not `post1.html`)
- Add alt text to images when you replace emoji placeholders
- Keep titles under 60 characters for search results

## 🛠️ Troubleshooting

### Links Not Working?
- Ensure all files are in the same directory
- Check file names match exactly (case-sensitive on some servers)
- Verify file extensions are `.html`

### Styles Look Broken?
- Make sure you copied the entire HTML file including all CSS in `<style>` tags
- Clear your browser cache (Ctrl+F5 or Cmd+Shift+R)

### Images Not Showing?
- Check image file paths are correct
- Ensure images are uploaded to your server
- Verify image file extensions match (`.jpg`, `.png`, etc.)

## 🔄 Future Development

**Upcoming Pages:**
- Patterns page
- Shop page
- About page
- Contact page

All currently redirect to `coming-soon.html` until developed.

**Potential Enhancements:**
- Email newsletter signup form
- Search functionality
- Categories/tags for posts
- Comments section
- RSS feed

## 📱 Browser Support

Tested and working on:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📄 License

All content and design © 2026 Southpaw Handmade. All rights reserved.

## 💬 Support

For questions or help with your blog, contact Southpaw Handmade through:
- Website contact form (coming soon)
- Social media links in footer

## 🎉 Credits

**Brand:** Southpaw Handmade  
**Tagline:** "Your creativity deserves better than basic, and you don't need anyone's permission to make something wonderful."  
**Blog Series:** Permission to Play

---

**Last Updated:** January 11, 2026  
**Version:** 1.0