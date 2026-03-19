# Worship Leadership Catalog

A comprehensive resource catalog for worship leaders, featuring 78+ videos, 35 scriptures, and 27 practical frameworks.

## 🎯 Features

- **78 Video Resources** from top worship leaders and teachers
- **35 Scripture Applications** for worship leadership
- **27 Practical Frameworks** for leading worship teams
- **10 Sections** covering all aspects of worship leadership
- **Beautiful UI** with accordion cards and full-page modal views
- **Responsive Design** works on desktop, tablet, and mobile
- **Search & Filter** by ministry, content type, and title

## 📦 What's Included

### Sections
1. **Biblical Foundation** - Scripture and theology of worship
2. **Song Selection** - Choosing the right songs for your congregation
3. **Setlist Building** - Creating flow and momentum in worship
4. **Leading Worship** - Platform presence and leading with authority
5. **Team Pastoring** - Shepherding and developing your worship team
6. **Rehearsal & Prep** - Running effective rehearsals and preparation
7. **Vocal Techniques** - Singing with skill and protecting your voice
8. **Spiritual Foundation** - Personal devotion and spiritual disciplines
9. **Conflict Resolution** - Handling team conflict biblically
10. **Technical Excellence** - Sound, lighting, and production

### Featured Ministries
- Elevation Worship
- Bethel Music
- Hillsong Worship
- Jesus Culture
- Church of the Highlands
- John Piper
- Matt Chandler
- Tim Keller
- And many more...

## 🚀 Quick Start

### Option 1: GitHub Pages (Easiest)

1. Fork or clone this repository
2. Go to Settings → Pages
3. Select "Deploy from branch" → main → root
4. Your site will be live at `https://yourusername.github.io/worship-catalog/`

### Option 2: Local Development

1. Clone the repository:
```bash
git clone https://github.com/yourusername/worship-catalog.git
cd worship-catalog
```

2. Open `index.html` in your browser:
```bash
open index.html
# or
python3 -m http.server 8000
# then visit http://localhost:8000
```

### Option 3: Deploy Anywhere

Upload `index.html` to any static hosting:
- Netlify
- Vercel
- AWS S3
- Any web server

## 💻 Technical Details

- **Pure HTML/CSS/JS** - No build process required
- **Self-contained** - Single HTML file
- **No dependencies** - Works offline after first load
- **Mobile responsive** - Looks great on all devices
- **Accessibility** - Keyboard navigation and screen reader friendly

## 🎨 Design Features

- **Blue color scheme** - Professional and calming
- **Accordion cards** - Clean, focused browsing
- **Full-page modals** - Immersive video viewing
- **Sticky section headers** - Easy navigation
- **Smooth animations** - Premium feel

## 📝 Customization

### Change Colors

Edit the CSS variables in `index.html`:

```css
:root {
    --primary: #4A90E2;        /* Main blue */
    --primary-dark: #357ABD;   /* Darker blue */
    --primary-light: #6BA3E8;  /* Lighter blue */
}
```

### Add New Resources

Add new video cards in the HTML:

```html
<div class="resource-card">
    <div class="card-header">
        <div class="card-title-area">
            <span class="source-tag">MINISTRY NAME</span>
            <h3>Video Title</h3>
        </div>
    </div>
    <div class="card-body">
        <div class="video-container">
            <iframe src="https://www.youtube.com/embed/VIDEO_ID?enablejsapi=1" 
                    frameborder="0" allowfullscreen></iframe>
        </div>
        <div class="quote-block">
            <p class="quote-text">Key quote from the video...</p>
        </div>
        <div class="takeaways">
            <h4>Key Takeaways:</h4>
            <ul class="takeaway-list">
                <li>Takeaway 1</li>
                <li>Takeaway 2</li>
            </ul>
        </div>
    </div>
</div>
```

## 📄 License

This is a resource catalog created for worship leaders. Feel free to use, modify, and share!

## 🙏 Credits

Created for Revitalize Church, Kalamazoo, MI
**"For Kalamazoo, not just IN Kalamazoo"**

## 📧 Contact

Questions or suggestions? Feel free to open an issue!

---

**Made with ❤️ for worship leaders everywhere**
