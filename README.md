# MGenie Pages

This is the public website repository for **MGenie**, a macOS teleprompter app that floats over your screen, scrolls at your pace, transcribes your words, and generates AI-powered answers.

## Repository Structure

```
MGenie-pages/
├── index.html                 # Landing page (hero, features)
├── 404.html                   # Custom 404 page
├── README.md                  # This file
│
├── guide/                     # User documentation & tutorials
│   ├── index.html
│   ├── 00-introduction.html
│   ├── 01-scrum-standup.html
│   ├── 02-team-meetings.html
│   ├── 03-presentations.html
│   ├── 04-discussions.html
│   ├── 05-interviews.html
│   └── 06-knowledge-base.html
│
├── docs/                      # Technical documentation
│   ├── index.html             # Documentation hub
│   ├── installation.html      # Download & setup guide
│   ├── requirements.html      # System requirements
│   └── build.html             # Build from source
│
├── downloads/                 # Download page
│   └── index.html
│
├── feedback/                  # Feedback & bug reports
│   └── index.html
│
├── blog/                      # Release notes & announcements (future)
│   └── index.html
│
├── screenshots/               # App screenshots & demos
│   └── README.md
│
└── assets/                    # Shared resources
    ├── css/
    │   ├── main.css           # Landing page styles
    │   └── guide.css          # Guide page styles
    ├── js/
    │   └── app.js             # JavaScript utilities
    └── images/
        ├── logo.svg
        └── icons/
```

## Pages

### Landing Page (`/index.html`)
- Hero section with download CTA
- Feature highlights
- Quick link to user guide
- Links to GitHub and releases

### User Guide (`/guide/`)
- 7 chapters covering common workflows
- Scrum standups, team meetings, presentations, discussions, interviews, knowledge base
- Sidebar navigation with active state
- Responsive design

### Documentation (`/docs/`)
- **Installation** - Download and setup instructions
- **System Requirements** - OS, hardware, and permission requirements
- **Build from Source** - Xcode and development setup
- **Documentation Hub** - Overview of all resources

### Feedback (`/feedback/`)
- Links to GitHub Issues for bug reports
- Feature request templates
- Discussion forum
- Guidelines for good feedback

### Downloads (`/downloads/`)
- Latest release download
- Release information (version, file size, platform)
- Link to all versions
- Auto-update information

### 404 Page (`/404.html`)
- Custom error page with helpful links
- Styled to match the site theme

## Styling

The site uses a dark GitHub-inspired theme with a system-ui font stack.

### CSS Files
- `assets/css/main.css` - Landing page, docs, feedback, download pages
- `assets/css/guide.css` - User guide sidebar layout

### Color Palette
- Background: `#0d1117`
- Text: `#c9d1d9`
- Accent: `#58a6ff`
- Success: `#238636`
- Cards: `#161b22`

## Local Development

### Preview Locally
```bash
# Using Python 3
python3 -m http.server 8000

# Using Node.js http-server
npx http-server -p 8000
```

Visit `http://localhost:8000` in your browser.

### Edit Content
- HTML files are self-contained with embedded styles
- Update navigation links consistently across all pages
- Maintain the same layout structure for new pages

## Deployment

This site is deployed using GitHub Pages. Push changes to the `main` branch to deploy automatically.

### To Deploy
```bash
git add .
git commit -m "Update content"
git push origin main
```

## Browser Support

- ✅ Safari (macOS, iOS)
- ✅ Chrome / Chromium
- ✅ Firefox
- ✅ Edge

Best experience on macOS Safari due to custom font rendering.

## License

Website content © 2026 MGenie. All rights reserved.

## Related Resources

- **[Main MGenie Repo](https://github.com/ampclaw/MGenie)** - Source code, issues, releases
- **[MGenie Pages (This Repo)](https://github.com/ampclaw/MGenie-pages)** - Website & documentation

---

For questions or contributions, visit the [main repository](https://github.com/ampclaw/MGenie) or open an issue.
