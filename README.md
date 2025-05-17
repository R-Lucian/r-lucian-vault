# R. Lucian Vault Interface

This repository contains the public-facing Vault interface for [rlucian.com/vault](https://rlucian.com/vault). It serves as the mission control for R. Lucian’s creative ecosystem — connecting viewers with product drops, interactive tours, sound kits, and exclusive content.

---

## 🔧 Project Structure

```
/HTML_Export/
├── index.html           # Main interface structure
├── style.css            # Vault theme styling
/Webflow_Guide/
└── Vault_Layout_Components.md  # Webflow-friendly layout and class naming guide
```

---

## 💡 Features

- Modular 4-panel Vault layout: Drop, Tour, Break, Console
- Hero section with ENTER call-to-action
- Responsive design with Orbitron font and dark sci-fi theme
- Scalable layout for OBS integration, Webflow, or static hosting
- Easily extendable with audio embeds, buttons, or login tiers

---

## 🛠️ Setup (for Devs)

1. Clone the repo:
```bash
git clone https://github.com/YOUR_USERNAME/r-lucian-vault.git
```

2. Open in your preferred IDE and launch with a local server:
```bash
# Using Python for quick preview
cd HTML_Export
python -m http.server
```

3. For Webflow: use `Vault_Layout_Components.md` to mirror layout structure using Webflow's Designer.

---

## 🚀 Deployment

You can deploy this site via:
- **GitHub Pages** (for static hosting)
- **Netlify / Vercel**
- **Webflow** (if rebuilt natively)

---

## 🎯 To-Do (Next Dev Steps)

- [ ] Add animation logic for button interactions
- [ ] Link each Vault Tool to specific product/media
- [ ] Embed video/audio trailers
- [ ] Setup Vault access tiers (optional)
- [ ] Add mobile responsiveness refinements

---

## 👁️ Preview

This layout is designed to match the visual Vault identity:
- Deep navy backgrounds
- Gold accents
- Minimalist, modular, terminal-like layout

---

## License

This project is proprietary to R. Lucian. Contact [rlucian.com](https://rlucian.com) for collaboration or deployment use.
