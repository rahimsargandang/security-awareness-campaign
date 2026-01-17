# PASSGUARD - Password Security Awareness

A comprehensive, interactive password security awareness website designed to educate home users about password best practices and protection strategies.

## Features

### Interactive Tools
- **Password Knowledge Quiz** - 8-question quiz testing password security awareness with instant feedback and detailed results
- **Password Strength Checker** - Real-time password analysis with crack time estimates (all processing done locally)
- **Password Generator** - Generate strong random passwords with customizable length (8-40 chars) and character types, with one-click copy
- **Password Ranking Game** - Drag-and-drop game to rank passwords from weakest to strongest across 3 rounds (mobile touch supported)

### Learning Modules

#### Creating Strong Passwords
- Passphrase method
- Random generator approach
- Sentence method
- Base + modifier system
- Golden rules of password creation

#### Attack Types Explained
- Brute force attacks
- Dictionary attacks
- Credential stuffing
- Phishing
- Keylogging
- Social engineering
- Crack time comparison table

#### Password Managers
- Why you need one
- What to look for (zero-knowledge encryption, 2FA, breach monitoring)
- Trusted options (Bitwarden, 1Password, Dashlane, KeePassXC)

#### Two-Factor Authentication (2FA)
- How 2FA works
- Authenticator apps (recommended)
- Hardware security keys (most secure)
- SMS/Email codes (weaker options)
- Backup codes importance

#### Real World Breaches
- RockYou2024 (10 billion passwords)
- LinkedIn (700 million records)
- Collection #1-5 (2.2 billion combinations)
- Yahoo (3 billion accounts)

#### Password Myths Debunked
- "Change passwords every 90 days"
- "Special characters make passwords secure"
- "Writing passwords down is always bad"
- "I'm not important enough to be hacked"
- "Browser password saving is unsafe"

### Resources
- **Security Checklist** - 10-item actionable checklist with progress saved locally
- **Quick Reference** - Key rules summary

## Tech Stack
- HTML5
- Tailwind CSS (CDN)
- Vanilla JavaScript
- Google Fonts (IBM Plex Mono, Syne)

## Design
- Dark vault aesthetic with emerald green accents
- Clean, professional interface
- Subtle animations and glow effects
- Card-based content organization

## Mobile Responsive
Fully optimized for all devices:

- **Mobile Navigation** - Hamburger menu with smooth toggle
- **Responsive Typography** - Text scales appropriately across screen sizes
- **Touch-Friendly** - All interactive elements meet 44px minimum touch target
- **Adaptive Layout** - Grids and cards stack properly on smaller screens
- **Responsive Buttons** - CTAs stack vertically on mobile

Tested on:
- iPhone / Android phones
- iPad / Android tablets
- Desktop browsers (Chrome, Firefox, Safari, Edge)

## Local Development
Simply open `index.html` in a browser. No build process required.

```bash
# Clone the repository
git clone https://github.com/rahimsargandang/security-awareness-campaign.git

# Open in browser
open index.html
```

## Deployment
This is a static site that can be deployed to:
- GitHub Pages
- Netlify
- Vercel
- Cloudflare Pages
- Any static hosting

## License
MIT License - Feel free to use and modify for educational purposes.
