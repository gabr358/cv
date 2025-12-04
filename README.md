# 3D CV Website 🚀

A stunning, modern CV/Resume website with awesome 3D animations and interactive elements.

## Features ✨

- **3D Animations**: Floating background shapes, rotating profile card, and interactive 3D card effects
- **Smooth Animations**: Micro-animations, hover effects, and scroll-based transitions
- **Modern Design**: Gradient colors, glassmorphism, and premium aesthetics
- **Fully Responsive**: Looks great on all devices
- **Interactive Elements**: Animated skill bars, timeline, and parallax effects
- **Easy to Customize**: Simple placeholders for your personal information

## How to Use 📝

### 1. Replace Profile Picture

Replace `profile-placeholder.jpg` with your own photo. For best results:
- Use a square image (recommended: 800x800px or larger)
- Save it as `profile-placeholder.jpg` or update the `src` in `index.html`

### 2. Update Your Information

Open `index.html` and find these elements with IDs. Update the content:

**Hero Section:**
- `#userName` - Your name
- `#userTitle` - Your job title/profession
- `#userBio` - Short bio description

**About Section:**
- `#fullName` - Your full name
- `#location` - Your city and country
- `#email` - Your email address
- `#phone` - Your phone number

**Contact Section:**
- `#contactEmail` - Email (update here too)
- `#contactPhone` - Phone (update here too)
- `#contactLocation` - Location (update here too)

**Footer:**
- `#footerName` - Your name for copyright

### 3. Customize Skills

In the Skills Section, modify the skill items:
- Change skill names
- Update percentages
- Adjust the progress bar widths (in the `style` attribute)

### 4. Update Experience/Education

Edit the timeline items in the Experience section:
- Job titles and positions
- Company names
- Dates
- Descriptions of your work

### 5. Modify Interests

In the About section, change the interest tags to match your interests.

## Running the Website 🌐

Simply open `index.html` in your web browser:

1. **Double-click** `index.html`, or
2. **Right-click** → Open with → Your preferred browser, or
3. Use a local server (recommended for development):
   ```
   python -m http.server 8000
   ```
   Then visit `http://localhost:8000`

## Customization Tips 🎨

### Change Colors

Open `style.css` and modify the CSS variables at the top:

```css
:root {
    --primary-color: hsl(260, 85%, 60%);  /* Main purple */
    --accent-color: hsl(330, 85%, 60%);   /* Pink accent */
    --secondary-color: hsl(200, 85%, 55%); /* Blue */
    /* ... more colors */
}
```

### Add More Sections

You can add more sections by copying the existing section structure and following the same pattern.

### Modify Animations

All animations are defined in `style.css`. Look for `@keyframes` rules to adjust animation speeds, effects, and timings.

## Browser Support 🌍

Works best in modern browsers:
- Chrome/Edge (recommended)
- Firefox
- Safari
- Opera

## What Makes This Special? 💎

1. **3D Profile Card** - Floating, rotating card with glow effects
2. **Animated Background** - Smooth floating gradient shapes
3. **Interactive Cards** - Tilt on mouse movement with 3D perspective
4. **Smooth Scrolling** - Butter-smooth navigation and scroll effects
5. **Skill Bars** - Animated progress bars with shimmer effects
6. **Timeline** - Beautiful vertical timeline with pulse animations
7. **Premium Aesthetics** - Modern gradients and glassmorphism

## Tips for Best Results 📸

- Use a high-quality profile photo with good lighting
- Keep descriptions concise and impactful
- Update all placeholder text with your real information
- Test on multiple devices to ensure responsiveness
- Consider deploying to GitHub Pages, Netlify, or Vercel for free hosting

## Need Help? 🤝

- All content is in `index.html`
- All styling is in `style.css`
- All interactivity is in `script.js`

Enjoy your awesome CV website! 🎉
