# 🍜 Hapjesfestival Website

Een lichtgewicht, responsieve website voor het Hapjesfestival evenement in Kudelstaart.

## 📁 Project Structuur

```
hapjesfestival-website/
├── index.html          # Hoofdpagina
├── styles.css          # Styling en responsive design
├── script.js           # Interactiviteit en animaties
├── images/             # Afbeeldingen
│   ├── banner landingspagina.jpg
│   └── HKK Flyer.jpg
├── README.md           # Deze documentatie
└── DEPLOYMENT.md       # Uitgebreide deployment instructies
```

## ✨ Functies

- ✅ **Volledig responsive** - Werkt op alle apparaten
- ✅ **Snel laadtijd** - Geoptimaliseerd voor snelheid (<1-2MB)
- ✅ **Countdown timer** - Telt af tot het evenement
- ✅ **Smooth scrolling** - Vloeiende navigatie
- ✅ **Mobile menu** - Hamburger menu voor mobiel
- ✅ **Social sharing** - Deel via Facebook, Twitter, Email
- ✅ **Scroll animaties** - Subtiele fade-in effecten
- ✅ **WhatsApp integratie** - Direct contact button
- ✅ **SEO geoptimaliseerd** - Meta tags voor betere vindbaarheid

## 🎨 Ontwerp

- **Kleurenpalet**: Warme oranje en aardse tinten
- **Typografie**: Poppins (hoofd) + Caveat (decoratief)
- **Thema**: Multicultureel, gezellig, community-focused
- **Secties**: 
  - Hero met banner
  - Event details
  - Over het festival
  - Programma & workshops
  - Ticketinformatie
  - Contact

## 🚀 Deployment Opties

### Optie 1: Netlify Drop (MAKKELIJKST - AANBEVOLEN)

**Voordelen:**
- ✅ Geen account nodig voor deployment
- ✅ Sleepbaar interface
- ✅ Direct human-readable URL
- ✅ Gratis SSL certificaat

**Stappen:**
1. Ga naar [drop.netlify.com](https://drop.netlify.com)
2. Sleep de hele `hapjesfestival-website` map naar de website
3. Wacht 10-20 seconden
4. Ontvang je URL (bijv. `happy-hapjes-festival-xyz.netlify.app`)
5. Optioneel: Maak een gratis account aan om de URL aan te passen

**URL aanpassen (optioneel):**
1. Klik op "Claim this site" na deployment
2. Ga naar Site Settings → Domain Management
3. Wijzig subdomain naar: `hapjesfestival` of `hkkfestival`
4. Je nieuwe URL: `hapjesfestival.netlify.app`

### Optie 2: GitHub Pages

**Voordelen:**
- ✅ Versie controle
- ✅ Gratis hosting
- ✅ Makkelijk updaten

**Stappen:**
1. Maak een GitHub account aan (gratis)
2. Maak een nieuwe repository: `hapjesfestival`
3. Upload alle bestanden
4. Ga naar Settings → Pages
5. Selecteer branch: `main`
6. Selecteer folder: `/root`
7. Klik op Save
8. Je URL: `jouwgebruikersnaam.github.io/hapjesfestival`

### Optie 3: Vercel

**Voordelen:**
- ✅ Snelle deployment
- ✅ Gratis SSL
- ✅ Goede performance

**Stappen:**
1. Ga naar [vercel.com](https://vercel.com)
2. Maak gratis account aan
3. Klik op "Add New" → "Project"
4. Upload de map via drag & drop
5. Klik op "Deploy"
6. Je URL: `hapjesfestival-xyz.vercel.app`

## 📝 Afbeeldingen Vervangen

Als je andere afbeeldingen wilt gebruiken:

1. Plaats je nieuwe afbeeldingen in de `images/` map
2. Update de bestandsnamen in `index.html`:
   - Regel 36: Banner afbeelding
   - Regel 112: About sectie afbeelding

**Aanbevolen afbeelding formaten:**
- Banner: 1920x1080px (landscape)
- Flyer: 800x1200px (portrait)
- Formaat: JPG of PNG
- Maximale grootte: 500KB per afbeelding

## 🔧 Website Aanpassen

### Tekst aanpassen
Open `index.html` en zoek de relevante sectie:
- Hero tekst: regel 45-50
- Event details: regel 62-87
- Over sectie: regel 100-108
- Programma: regel 123-178
- Tickets: regel 189-234
- Contact: regel 245-280

### Kleuren aanpassen
Open `styles.css` en pas de CSS variabelen aan (regel 12-22):
```css
--primary-orange: #FF6B35;    /* Hoofdkleur */
--secondary-orange: #F7931E;  /* Accent kleur */
--dark-brown: #4A4A4A;        /* Donkere tekst */
```

### Event datum aanpassen
Open `script.js` en pas de datum aan (regel 41):
```javascript
const eventDate = new Date('2026-06-27T13:00:00').getTime();
```

## 📱 Contact Informatie Updaten

### WhatsApp nummer wijzigen
In `index.html`, zoek naar `https://wa.me/` en vervang het nummer

### Email adres wijzigen
Zoek naar `info@inkudelstaart.nl` en vervang met jouw email

## 🗑️ Website Verwijderen (na 1 maand)

### Netlify:
1. Log in op netlify.com
2. Ga naar je site
3. Settings → General → Delete site

### GitHub Pages:
1. Log in op github.com
2. Ga naar je repository
3. Settings → Danger Zone → Delete repository

### Vercel:
1. Log in op vercel.com
2. Ga naar je project
3. Settings → Delete Project

## ⚡ Performance Tips

- **Afbeeldingen comprimeren**: Gebruik [TinyPNG.com](https://tinypng.com) voor kleinere bestanden
- **Google PageSpeed Insights**: Test je website op [pagespeed.web.dev](https://pagespeed.web.dev)
- **Caching**: Netlify, GitHub Pages en Vercel hebben automatische caching

## 🎯 SEO Verbeteringen (Optioneel)

De website bevat al basis SEO:
- Meta descriptions
- Open Graph tags voor social media
- Semantic HTML
- Alt tekst voor afbeeldingen

### Extra toevoegen:
1. **Google Analytics** (optioneel):
   - Maak account aan op [analytics.google.com](https://analytics.google.com)
   - Voeg tracking code toe voor `</head>` in index.html

2. **Sitemap** (optioneel voor zoekmachines):
   - Maak `sitemap.xml` aan
   - Submit aan Google Search Console

## 🆘 Hulp Nodig?

**Veel voorkomende problemen:**

1. **Afbeeldingen laden niet**
   - Controleer of paden kloppen (`./images/bestandsnaam.jpg`)
   - Controleer of bestanden in de juiste map staan

2. **Website niet responsive**
   - Check of `viewport` meta tag aanwezig is
   - Test in verschillende browsers

3. **Countdown werkt niet**
   - Controleer datum formaat in script.js
   - Controleer browser console voor errors (F12)

4. **Deployment mislukt**
   - Zorg dat alle bestanden aanwezig zijn
   - Check of er geen speciale tekens in bestandsnamen zitten

## 📄 Licentie

Deze website is gemaakt voor het Hapjesfestival evenement in Kudelstaart.
Vrij te gebruiken en aan te passen voor je eigen evenement.

## 🙏 Credits

- Ontwerp en ontwikkeling: Custom voor Hapjesfestival
- Fonts: Google Fonts (Poppins, Caveat)
- Icons: Unicode emoji's (geen externe dependencies)

---

**Veel succes met je evenement! 🍜✨**

Voor vragen: info@inkudelstaart.nl
