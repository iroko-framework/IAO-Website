# Ilé Aña Olofí, Inc. — Website

Static site for [ileanaolofi.org](https://ileanaolofi.org), deployed via GitHub Pages.

Ilé Aña Olofí, Inc. is a 501(c)(3) religious and cultural organization dedicated to the preservation, practice, and transmission of Afro-Atlantic sacred traditions. The organization serves as the fiscal and organizational sponsor of the [Iroko Historical Society](https://www.irokosociety.org).

---

## Site Structure

```
IAO-Website/
├── index.html          # Homepage — mission, sponsored projects, organizational standing
├── about.html          # About the organization and founder
├── projects.html       # Sponsored projects: IHS, La Redentora, community engagement
├── community.html      # Community and religious engagement
├── contact.html        # Contact and correspondence
├── style.css           # Shared stylesheet (brand colors, typography)
├── CNAME               # Custom domain (ileanaolofi.org)
└── assets/             # Logos and images
```

---

## Design System

### Palette

| Token          | Hex       | Use                              |
|----------------|-----------|----------------------------------|
| `--navy`       | `#0F2044` | Nav, hero, dark section backgrounds |
| `--gold`       | `#C49A28` | Accents, borders, buttons        |
| `--gold-light` | `#E0B840` | Display text on dark backgrounds |
| `--cream`      | `#F5F2E8` | Page background                  |
| `--cream-mid`  | `#EDE8D8` | Alternate section backgrounds    |
| `--text-muted` | `#4A4A6A` | Body text, labels                |

### Typography

- **Display / Signature:** [Rye](https://fonts.google.com/specimen/Rye) (Google Fonts) — falls back to Poor Richard on Windows
- **Body:** [EB Garamond](https://fonts.google.com/specimen/EB+Garamond) (Google Fonts)
- **UI / Labels:** [Source Sans 3](https://fonts.google.com/specimen/Source+Sans+3) (Google Fonts)

---

## Relationship to Iroko Historical Society

Ilé Aña Olofí, Inc. is the parent 501(c)(3) organization and fiscal sponsor of the Iroko Historical Society. The two sites are intentionally distinct in visual identity while sharing institutional DNA:

| | Ilé Aña Olofí | Iroko Historical Society |
|---|---|---|
| Register | Ceremonial, personal, religious | Institutional, scholarly, archival |
| Palette | Navy + Gold | Forest Green + Cream |
| Display font | Rye | Playfair Display |
| Hosted at | ileanaolofi.org | irokosociety.org |
| Ontology | — | ontology.irokosociety.org |

---

## Deployment

### GitHub Pages

Site deploys automatically from the `main` branch root on every push.

Live at: **https://ileanaolofi.org**

### DNS (managed via Squarespace)

| Type  | Host | Data                      |
|-------|------|---------------------------|
| A     | @    | 185.199.108.153            |
| A     | @    | 185.199.109.153            |
| A     | @    | 185.199.110.153            |
| A     | @    | 185.199.111.153            |
| CNAME | www  | iroko-framework.github.io |

Email handled by Google Workspace MX records — do not modify.

---

## Updating the Site

All pages share `style.css`. To update content, edit the relevant HTML file and push to `main`. GitHub Pages rebuilds within 1–2 minutes.

To update across all pages simultaneously (footer, nav, contact email), find and replace in all `.html` files before committing.

---

## Affiliated

- [Iroko Historical Society](https://www.irokosociety.org)
- [Iroko Framework Ontology](https://ontology.irokosociety.org)
- [Iroko Framework White Paper](https://ontology.irokosociety.org/whitepaper)

---

© 2021–2026 Ilé Aña Olofí, Inc. · A 501(c)(3) Religious & Cultural Organization
