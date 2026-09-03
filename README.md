# RoomVibe 🏠

**Design your room in seconds**

Upload a photo of your room, add furniture suggestions, pick color themes, and download your styled design instantly.

---

## Features

✅ **Photo Upload** — Drag & drop or select an image  
✅ **Furniture Library** — 8+ furniture types to try  
✅ **Color Themes** — 5 pre-built color palettes  
✅ **Drag & Place** — Easy drag-drop interface  
✅ **Download Design** — Export your styled room as PNG  
✅ **No Account Needed** — Works entirely in your browser

---

## Quick Start

### 1. Install dependencies
```bash
npm install
```

### 2. Run development server
```bash
npm run dev
```

Open `http://localhost:3000` in your browser

### 3. Build for production
```bash
npm run build
```

### 4. Deploy to Vercel (one command)
```bash
npm install -g vercel
vercel
```

---

## Project Structure

```
roomvibe/
├── src/
│   ├── RoomVibe.jsx      # Main component
│   ├── App.jsx           # App wrapper
│   ├── main.jsx          # React entry point
│   └── index.css         # Global styles
├── index.html            # HTML template
├── package.json          # Dependencies
├── tailwind.config.js    # Tailwind config
├── vite.config.js        # Vite config
└── README.md             # This file
```

---

## Tech Stack

- **React 18** — UI framework
- **Vite** — Lightning-fast build tool
- **Tailwind CSS** — Utility-first styling
- **Canvas API** — Image manipulation & download

---

## How It Works

1. **Upload** — Drop a room photo
2. **Design** — Drag furniture onto your room
3. **Style** — Pick a color theme
4. **Download** — Export as PNG

---

## Future Roadmap (Phase 2)

- 🤖 AI furniture detection (auto-detect existing furniture)
- 🔄 360° room view with Three.js
- 🛒 Shopping list with retailer links
- 💾 Save designs to cloud
- 📱 Mobile app (React Native)

---

## Development

### Add new furniture types
Edit `src/RoomVibe.jsx` and add to `furnitureTypes` array:
```jsx
{ name: 'Desk', icon: '🖥️', color: '#8B6F47' }
```

### Add new color themes
Edit `colorThemes` array:
```jsx
{ name: 'Ocean', overlay: 'rgba(100,150,200,0.12)', wallColor: '#E6F2FF', accentColor: '#0066CC' }
```

---

## License

MIT — Free to use and modify

---

## Built by

**SAPD LABS** — AI-powered custom web development studio

---

## Support

Questions? Found a bug? [Open an issue](https://github.com/parvtech/roomvibe/issues) or reach out to hello@sapdlabs.com
