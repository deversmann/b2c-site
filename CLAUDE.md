# Between Two Chiefs - Project Instructions

## Project Overview
This is a "Coming Soon" landing page for a podcast called **"Between Two Chiefs"**.

### Podcast Details
- **Name:** Between Two Chiefs
- **Hosts:**
  - Francisco Ramirez (initials: FR)
  - Damien Eversmann (initials: DE)
- **Status:** Pre-launch / Coming Soon
- **Format:** Leadership and technology conversations

## Project Structure
```
/Users/deversma/Development/b2c/
├── index.html          # Single-file website with embedded CSS and JS
├── b2c.png            # Podcast logo image
└── CLAUDE.md          # This file
```

## Technical Stack
- **Single HTML file** with embedded CSS and JavaScript
- No external dependencies or frameworks
- Self-contained and portable

## Design Specifications

### Color Scheme
- Primary: `#2c3e50` (dark blue-gray)
- Secondary: `#e74c3c` (red)
- Accent: `#3498db` (blue)
- Background: `#ecf0f1` (light gray)

### Key Features
1. **Podcast Logo** - Prominent display in Hero section (b2c.png, 500px desktop / 280px mobile)
2. **Sticky Navigation** - Remains at top of viewport when scrolling
3. **Smooth Scrolling** - Animated transitions between sections
4. **Responsive Design** - Mobile-friendly layout
5. **Sections:**
   - Home (Hero with logo and "Coming Soon" badge)
   - About (podcast description)
   - Hosts (profiles with placeholder photos)
   - Subscribe (email notification form)
6. **Placeholder Host Photos** - Circular gradient avatars with initials

### Host Profiles
Both hosts have placeholder biographies that can be replaced with actual content when available.

## Development Guidelines

### When Making Updates
- Maintain the single-file architecture (no external CSS/JS files)
- Keep responsive design working across mobile and desktop
- Preserve the sticky navigation functionality
- Use the existing color scheme unless requested to change
- Keep animations subtle and professional

### Content Updates
- Logo image (b2c.png) can be replaced - positioned prominently in Hero section
- Host biographies can be updated with real information
- Placeholder photos can be replaced with actual images (update `.host-photo` styling)
- About section text can be expanded or modified
- Email form currently simulates submission - can be connected to real backend

### Future Enhancements (if requested)
- Connect email form to actual mailing list service
- Add social media links
- Include audio player for teaser/trailer
- Add episode calendar or release date
- Create favicon
- Add Open Graph meta tags for social sharing

## Deployment

### GitHub Pages
This site is ready for GitHub Pages deployment:

1. **Push to GitHub:**
   ```bash
   git remote add origin https://github.com/USERNAME/REPO.git
   git push -u origin main
   ```

2. **Enable GitHub Pages:**
   - Go to repository Settings → Pages
   - Source: Deploy from a branch
   - Branch: main / (root)
   - Save

3. **Access your site:**
   - URL will be: `https://USERNAME.github.io/REPO/`
   - Custom domain can be configured in Settings → Pages

### Local Testing
- Simply open `index.html` in a web browser
- No build process or server required
- Works offline

## Notes
- Project created: 2026-03-24
- Organized for GitHub Pages deployment
- No build process required - pure static HTML/CSS/JS
