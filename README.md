# noahtech.health

Official website for **NoahTech, Corp.** — a Nevada-based clinical-stage neuroscience company developing regenerative and cognitive-enhancement therapies, with a focus on Mild Cognitive Impairment (MCI) and brain-aging prevention.

🌐 **Live site:** [www.noahtech.health](https://www.noahtech.health)

---

## About

NoahTech combines certified MoCA cognitive screening, mesenchymal stem-cell regenerative medicine, and active clinical-trial research (NCT07214974) to advance brain health and longevity. This repository contains the static marketing and informational website for the company.

---

## Site Structure

| Page | Path | Purpose |
|---|---|---|
| Home | `index.html` | Landing page introducing NoahTech's services |
| Brain Aging Prevention | `cognit.html` | Certified MoCA cognitive assessment overview |
| MoCA Assessment | `MCItest.html` | Information on the MoCA Cognitive Assessment iOS/iPadOS/macOS app |
| Memory Enhancement | `memen.html` | Memory enhancement program details |
| Clinical Trial | `trial.html` | Active trial NCT07214974 — recruiting, MCI cognitive enhancement |
| Contact & Service Guide | `contact.html` | Service guide PDF, contact info, scheduling |
| Sales Training | `training.html` | Sales agent training manual |
| SaMD Project | `SaMD.html` | MCI Suite SaMD project management dashboard |
| Support | `support.html` | App and service support contact |
| Privacy Policy | `privacy.html` | HIPAA / GDPR / CCPA compliance |
| Terms of Use | `terms.html` | Nevada-governed legal terms |

---

## Tech Stack

- **HTML5** — semantic, static markup
- **Bootstrap 4** — responsive layout grid
- **Vanilla JavaScript** + **jQuery** — interaction
- **Font Awesome** & **IcoFont** — iconography
- **Google Fonts (Poppins)** — typography
- No build step required — pure static files

### Project Layout

```
.
├── index.html                  # Home
├── cognit.html                 # Brain aging prevention
├── MCItest.html                # MoCA Assessment app
├── memen.html                  # Memory enhancement
├── trial.html                  # Clinical trial NCT07214974
├── contact.html                # Contact & service guide
├── support.html                # App / service support
├── privacy.html                # Privacy policy
├── terms.html                  # Terms of use
├── training.html               # Sales agent training manual
├── SaMD.html                   # SaMD project dashboard
├── style.css                   # Site-wide styles
├── css/                        # Vendor + responsive CSS
├── js/                         # jQuery, Bootstrap, plugins
├── img/                        # Logos, photos, OG images, badges
└── NoahTech MSCGuid.pdf        # Downloadable service guide
```

---

## Local Development

Since the site is fully static, any local web server will do.

```bash
# Python 3
python3 -m http.server 8000

# Node (with http-server installed globally)
npx http-server -p 8000
```

Then open <http://localhost:8000> in your browser.

---

## Deployment

The site is deployed at **www.noahtech.health**. To publish updates, upload the contents of this repository to the web server's document root (or sync via your hosting provider's standard workflow). All paths are relative, so the same files work in any subdirectory.

---

## Contact

| Inquiry | Email |
|---|---|
| General | info@noahtech.life |
| Privacy | privacy@noahtech.life |
| Legal | legal@noahtech.life |
| App / Service Support | help@noahtech.life |

**Headquarters**
NoahTech, Corp.
930 S 4th St Ste 209
Las Vegas, NV 89101, USA

**Schedule a call:** [calendly.com/noahtech-info/30min](https://calendly.com/noahtech-info/30min)

---

## License & Copyright

© 2024–present NoahTech, Corp. All rights reserved.

The content, design, branding, and all related intellectual property on this site are owned by NoahTech, Corp. and protected by U.S. and international copyright, trademark, and trade-secret laws. See [`terms.html`](terms.html) for the full terms of use.

---

## Medical Disclaimer

The content on this site is for informational purposes only and is **not** intended as a substitute for professional medical advice, diagnosis, or treatment. Clinical-trial information is provided for transparency; participation requires separate, IRB-approved informed consent.
