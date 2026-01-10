# CogCompNeuro Journal Club Website

## Folder Structure

```
cogcompneuro-jc/
├── index.html
├── images/
│   ├── elizabeth.jpg
│   ├── jerome.jpg
│   ├── kaiwen.jpg
│   ├── mikaela.jpg
│   └── kwon.jpg
└── README.md
```

## Adding Photos

1. Add member photos to the `images/` folder with these exact filenames:
   - `elizabeth.jpg`
   - `jerome.jpg`
   - `kaiwen.jpg`
   - `mikaela.jpg`
   - `kwon.jpg`

2. **Recommended photo specs:**
   - Square aspect ratio (1:1)
   - At least 300x300 pixels
   - JPG or PNG format
   - If using PNG, change the file extensions in `index.html`

## Deploying to GitHub Pages

1. Create a new repository on GitHub (e.g., `cogcompneuro-jc`)
2. Upload all files maintaining the folder structure
3. Go to **Settings** → **Pages**
4. Under "Source", select `main` branch and click Save
5. Your site will be live at `https://[username].github.io/cogcompneuro-jc/`

## Customizing

### Update placeholder links
Search for `href="#"` in `index.html` and replace with actual URLs:
- Sign-up sheet (Google Form/Sheet)
- Calendar invite link
- Speaker guidelines doc
- Email address
- Slack channel
- Google Drive folder

### Add new sessions
Find the `schedule-body` div and add new `schedule-item` blocks.

### Add past sessions
Find the `past-grid` div and add new `past-card` blocks.

---
© 2025 CogCompNeuro Journal Club · Stanford University
