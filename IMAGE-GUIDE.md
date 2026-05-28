# 🖼️ IMAGE REPLACEMENT GUIDE

## Huidige Afbeeldingen

De website gebruikt 2 afbeeldingen:

1. **Banner (Hero Section)**
   - Bestand: `banner landingspagina.jpg`
   - Locatie: `images/banner landingspagina.jpg`
   - Huidige grootte: 176 KB
   - Gebruikt: Grote achtergrond op hoofdpagina

2. **Flyer (About Section)**
   - Bestand: `HKK Flyer.jpg`
   - Locatie: `images/HKK Flyer.jpg`
   - Huidige grootte: 404 KB
   - Gebruikt: Rechts in de "Over" sectie

---

## ✅ Eigen Afbeeldingen Toevoegen

### Optie 1: Zelfde Bestandsnamen (Makkelijkst)

Als je dezelfde namen gebruikt, hoef je niks aan te passen in de code!

**Stappen:**
1. Hernoem je nieuwe banner naar: `banner landingspagina.jpg`
2. Hernoem je nieuwe flyer naar: `HKK Flyer.jpg`
3. Vervang de bestanden in de `images/` map
4. Upload naar Netlify
5. Klaar! ✅

### Optie 2: Andere Bestandsnamen

Als je andere namen wilt gebruiken:

**Stappen:**
1. Plaats je afbeeldingen in de `images/` map
2. Open `index.html`
3. Zoek naar deze regels en pas aan:

**Voor de banner (regel ~36):**
```html
<!-- OUD: -->
<img src="./images/banner landingspagina.jpg" alt="Hapjesfestival Banner" loading="eager">

<!-- NIEUW (vervang bestandsnaam): -->
<img src="./images/jouw-banner-naam.jpg" alt="Hapjesfestival Banner" loading="eager">
```

**Voor de flyer (regel ~112):**
```html
<!-- OUD: -->
<img src="./images/HKK Flyer.jpg" alt="Hapjesfestival Flyer" loading="lazy">

<!-- NIEUW (vervang bestandsnaam): -->
<img src="./images/jouw-flyer-naam.jpg" alt="Hapjesfestival Flyer" loading="lazy">
```

---

## 📏 Aanbevolen Afbeelding Specificaties

### Banner (Hero Image):
```
✅ Formaat: Landscape (breed)
✅ Afmetingen: 1920 x 1080 pixels (Full HD)
✅ Minimaal: 1200 x 675 pixels
✅ Bestandstype: JPG of PNG
✅ Maximale grootte: 500 KB
✅ Aspect ratio: 16:9
```

**Tips voor banner:**
- Gebruik horizontale foto's
- Zorg voor vrije ruimte in het midden (daar komt tekst)
- Heldere, kleurrijke foto's werken het best
- Vermijd te donkere foto's

### Flyer (About Image):
```
✅ Formaat: Portrait (staand) of vierkant
✅ Afmetingen: 800 x 1200 pixels
✅ Minimaal: 600 x 800 pixels
✅ Bestandstype: JPG of PNG
✅ Maximale grootte: 500 KB
✅ Aspect ratio: 2:3 of 3:4
```

**Tips voor flyer:**
- Poster-formaat werkt perfect
- Kan ook vierkante afbeelding zijn
- Zorg voor goede resolutie
- Vermijd te veel kleine tekst (niet leesbaar op mobiel)

---

## 🎨 Afbeeldingen Optimaliseren

**Te grote afbeeldingen vertragen je website!**

### Online Tools (Gratis & Makkelijk):

#### 1. TinyPNG (Beste keuze!)
```
Website: https://tinypng.com
✅ Sleep je afbeelding
✅ Wacht op compressie
✅ Download geoptimaliseerde versie
✅ Vaak 50-70% kleiner!
```

#### 2. Squoosh (Google)
```
Website: https://squoosh.app
✅ Meer controle over kwaliteit
✅ Zie preview van voor/na
✅ Verschillende formaten (JPG, WebP)
```

#### 3. ImageOptim (Mac)
```
Download: https://imageoptim.com
✅ Sleep afbeeldingen in de app
✅ Automatische optimalisatie
✅ Behoudt kwaliteit
```

#### 4. GIMP (Windows/Mac/Linux)
```
Download: https://www.gimp.org
✅ Gratis fotobewerkingsprogramma
✅ Exporteer met "Save for Web"
✅ Veel opties
```

### Handmatige Optimalisatie:

**Stap voor stap:**
```
1. Open afbeelding in GIMP of Photoshop
2. Verklein afmetingen naar aanbevolen grootte
3. Exporteer als JPG met kwaliteit 80-85%
4. Check bestandsgrootte (moet <500KB zijn)
5. Als te groot: verlaag kwaliteit naar 70-75%
6. Bewaar geoptimaliseerde versie
```

---

## 🔄 Afbeeldingen Vervangen - Complete Workflow

### Stap-voor-stap proces:

#### 1. Voorbereiding
```
☐ Kies je nieuwe afbeeldingen
☐ Check afmetingen (gebruik tips hierboven)
☐ Optimaliseer met TinyPNG
☐ Bevestig bestandsgrootte <500KB
```

#### 2. Bestanden Klaarmaken
```
☐ Hernoem naar juiste namen (of noteer nieuwe namen)
☐ Plaats in de `images/` map
☐ Verwijder oude afbeeldingen (optioneel)
```

#### 3. Code Aanpassen (als nieuwe namen)
```
☐ Open index.html
☐ Zoek regel met oude bestandsnaam
☐ Vervang door nieuwe bestandsnaam
☐ Bewaar bestand
```

#### 4. Testen Lokaal (optioneel)
```
☐ Open index.html in browser
☐ Check of afbeeldingen laden
☐ Test op verschillende schermgroottes
```

#### 5. Online Zetten
```
☐ Log in op Netlify/Vercel/GitHub
☐ Upload nieuwe bestanden
☐ Wacht op deployment (30 sec - 2 min)
☐ Test live website
```

---

## 🎯 Extra Afbeeldingen Toevoegen

Wil je meer afbeeldingen toevoegen aan de website?

### Voor Programma Items:

Je kunt emoji's vervangen door echte foto's!

**Stappen:**
1. Voeg afbeelding toe aan `images/` map
2. Vind het programma item in `index.html` (regel ~123-178)
3. Vervang deze code:

```html
<!-- OUD (met emoji): -->
<div class="program-flag">🇨🇳</div>

<!-- NIEUW (met foto): -->
<div class="program-flag">
    <img src="./images/dumpling-workshop.jpg" alt="Dumpling Workshop" style="width:80px;height:80px;border-radius:50%;object-fit:cover;">
</div>
```

### Voor Gallery Sectie (Nieuwe sectie):

Als je een fotogallery wilt toevoegen:

**Plaats deze code in index.html (voor de footer, regel ~285):**

```html
<!-- Photo Gallery Section -->
<section id="gallery" class="gallery">
    <div class="container">
        <h2 class="section-title">Impressie</h2>
        <div class="gallery-grid">
            <img src="./images/foto1.jpg" alt="Festival foto 1" loading="lazy">
            <img src="./images/foto2.jpg" alt="Festival foto 2" loading="lazy">
            <img src="./images/foto3.jpg" alt="Festival foto 3" loading="lazy">
            <img src="./images/foto4.jpg" alt="Festival foto 4" loading="lazy">
        </div>
    </div>
</section>
```

**Voeg deze CSS toe aan styles.css (onderaan, voor de media queries):**

```css
/* Gallery Section */
.gallery {
    background: var(--white);
    padding: var(--spacing-xl) 0;
}

.gallery-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: var(--spacing-md);
}

.gallery-grid img {
    width: 100%;
    height: 250px;
    object-fit: cover;
    border-radius: 12px;
    box-shadow: var(--shadow-md);
    transition: transform var(--transition-normal);
    cursor: pointer;
}

.gallery-grid img:hover {
    transform: scale(1.05);
    box-shadow: var(--shadow-lg);
}
```

---

## ⚠️ Veelvoorkomende Problemen

### Afbeelding laadt niet:
```
❌ Bestandsnaam klopt niet (hoofdlettergevoelig!)
❌ Afbeelding staat niet in de images/ map
❌ Pad in HTML is verkeerd
✅ Check: is het pad `./images/bestandsnaam.jpg`?
✅ Check: zijn spaties in bestandsnaam? (vermijd dit!)
```

### Afbeelding is wazig:
```
❌ Originele afbeelding is te klein
❌ Te veel gecomprimeerd
✅ Gebruik grotere originele afbeelding
✅ Verhoog compressie kwaliteit naar 85-90%
```

### Afbeelding laadt langzaam:
```
❌ Bestand is te groot (>1MB)
❌ Niet geoptimaliseerd
✅ Comprimeer met TinyPNG
✅ Verklein afmetingen
✅ Check bestandsgrootte (<500KB)
```

### Verkeerde proporties:
```
❌ Aspect ratio klopt niet
✅ Banner moet liggend zijn (16:9)
✅ Flyer moet staand/vierkant zijn
✅ Crop afbeelding naar juiste verhouding
```

---

## 📱 Test Checklist

Na het vervangen van afbeeldingen:

```
Desktop Tests:
☐ Banner laadt correct
☐ Banner is scherp
☐ Flyer zichtbaar in About sectie
☐ Geen witte vlekken/gaps
☐ Kleuren zien er goed uit

Mobiel Tests:
☐ Banner past op scherm
☐ Flyer niet te groot
☐ Alles leesbaar
☐ Snelle laadtijd

Performance:
☐ Totale pagina <2MB
☐ Laadtijd <3 seconden
☐ Lighthouse score >90
```

---

## 🎨 Image Formats Vergelijken

| Format | Voordelen | Nadelen | Gebruik |
|--------|-----------|---------|---------|
| **JPG** | Klein bestand, breed ondersteund | Geen transparantie | Foto's ✅ |
| **PNG** | Transparantie, hoge kwaliteit | Grote bestanden | Logo's, iconen |
| **WebP** | Kleinste bestanden, goede kwaliteit | Minder browser support | Modern alternatief |
| **SVG** | Schaalbaar, klein | Alleen voor vectoren | Icons, logo's |

**Aanbeveling voor deze website: JPG** ✅

---

## 🆘 Hulp Nodig?

**Afbeeldingen werken niet na alle stappen?**

1. Check browser console (F12)
2. Zoek naar rode errors
3. Check of pad correct is
4. Upload opnieuw naar hosting

**Email support:**
info@inkudelstaart.nl

**WhatsApp:**
06-16067577

---

**Veel succes met je afbeeldingen! 📸✨**
