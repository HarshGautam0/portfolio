# Harsh Gautam – ECE Portfolio

A single-page portfolio for an Electronics and Communication Engineering graduate. The page is styled like real hardware (brushed-metal panels, LEDs, a power switch, push-buttons) and has 11 switchable visual skins.

**Live site:** https://harshgautam0.github.io/portfolio/ (available once GitHub Pages is enabled, see below)

## Features

- **Power switch intro:** flip the switch in the hero to boot the LCD with a typed intro message.
- **Project selector:** push-buttons load each hardware project onto an LCD, with its components shown as IC chips.
- **11 skins:** switch the look from the SKIN buttons.
  - Skeuomorphic: Metal, Bakelite, Cream, Arduino, Breadboard
  - Flat and modern: Terminal, Blueprint, Neo-brutal, Glass, Minimal, Neon
- **Responsive:** works on desktop and mobile, with visible keyboard focus and reduced-motion support.
- **No build step:** one HTML file with inline CSS and JavaScript. The only external resource is Google Fonts.

## Sections

| Section | Content |
| --- | --- |
| Hero | Name, role and the power-on intro |
| Hardware projects | 3D Scanner, Solar-Powered Rover, LPG Gas Detection and Prevention System, Laser Door Security Alarm |
| Web projects | Fitsphere, weather app, currency converter, Netflix/Hotstar/Amazon homepage clones, games, mini tools |
| Publication | "3D Scanner", IJRASET, Vol. 13, Issue V, May 2025 (DOI: 10.22214/ijraset.2025.70429) |
| Background | Education, internship and certifications |
| Skills | Sensing, actuation, systems and web |
| Contact | Email, phone, LinkedIn, GitHub |

## Tech stack

HTML, CSS (custom properties, gradients, SVG) and vanilla JavaScript. Fonts: Saira Condensed, Barlow and VT323 from Google Fonts.

## Run locally

```bash
git clone https://github.com/HarshGautam0/portfolio.git
cd portfolio
```

Open `index.html` in a browser. To use a local server instead:

```bash
python -m http.server 8000
```

Then visit http://localhost:8000.

## Deploy with GitHub Pages

1. Open the repository on GitHub, then go to **Settings > Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select the `main` branch and the `/ (root)` folder, then click **Save**.
4. After a minute, the site is live at `https://harshgautam0.github.io/portfolio/`.

## Customise

- **Project text:** edit the `P` array in the `<script>` block at the bottom of `index.html`.
- **Skins:** each skin is a `:root[data-skin=...]` block in the CSS. To add one, add its CSS and then add it to the `SK` array in the script.
- **Contact links:** edit the `.jack` links in the Contact section.

## Author

**Harsh Gautam**, B.Tech in Electronics and Communication Engineering (2025)

- Email: hg699810@gmail.com
- LinkedIn: https://www.linkedin.com/in/harsh-gautam-23625127a/
- GitHub: https://github.com/HarshGautam0
