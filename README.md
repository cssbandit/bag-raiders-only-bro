# BRO - Bag Raiders Only

A dynamic, interactive website for BRO token with floating elements, drag functionality, and Raid Mode.

## Features

- 🚀 **Floating Elements**: Moon, rocket, arrows, and cash bag with parallax animations
- 🎮 **Interactive**: Drag elements around the screen
- ⚡ **Raid Mode**: Toggle to make everything wiggle and chart pulse
- ⌨️ **Keyboard Shortcut**: Press 'R' to toggle Raid Mode
- 📱 **Mobile Responsive**: Works on all devices
- 🎨 **Neobrutalism Design**: Bold colors and chunky elements

## Quick Deploy to Netlify

1. **Drag & Drop**: Simply drag this entire folder to [Netlify Drop](https://app.netlify.com/drop)
2. **GitHub**: Connect your GitHub repo to Netlify for automatic deployments
3. **CLI**: Use `netlify deploy` if you have the CLI installed

## File Structure

```
BRO WEBSITE/
├── index.html          # Main website file
├── netlify.toml        # Netlify configuration
├── README.md           # This file
└── img/
    ├── bro-logo.png    # BRO logo
    ├── moon.png        # Moon element
    ├── rocket.png      # Rocket element
    ├── arrow1.png      # Arrow element 1
    ├── arrow2.png      # Arrow element 2
    └── bag.png         # Cash bag element
```

## Customization

### Colors
Edit the CSS variables in `index.html`:
```css
:root{
  --bg:#082b22;        /* Background green */
  --ink:#fff;          /* Text color */
  --accent:#ffe84a;    /* Accent yellow */
}
```

### Links
Update the button URLs in the HTML:
```html
<a class="btn" href="YOUR_BUY_URL">Buy $BRO</a>
<a class="btn" href="YOUR_CHART_URL">Chart</a>
<a class="btn" href="YOUR_COMMUNITY_URL">Community</a>
```

### Elements
Add more floating elements by copying this line:
```html
<img class="orb moon" style="left:10%; top:20%; width:80px" src="./img/your-element.png" alt="description" />
```

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- Images optimized for web
- No external dependencies
- Minimal JavaScript
- Fast loading times

---

**BRO - Bag Raiders Only • 2025**
*If you are not raiding, you are the bag.*
