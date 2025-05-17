# R. Lucian Vault Webflow Component Guide

## Layout Sections:
- Hero Section: 'WELCOME TO THE VAULT' + CTA Button (class: hero-banner)
- Vault Tools Grid: 4 clickable cards (class: vault-tool-card)
- Interactive Panels: Two lower sections for embeds or toggles (class: panel-interactive)
- Footer: Minimal with badge + contact (class: vault-footer)

## Key Components:
- `div.hero-banner`
- `button.enter-btn`
- `div.vault-tool-card` (with `img.thumbnail` + `button.tool-label`)
- `div.panel-interactive`
- `footer.vault-footer`

## Interactions:
- Hover on vault cards: glow effect
- Button click: scroll to anchor or open modal
- Footer auto-animates in on scroll
