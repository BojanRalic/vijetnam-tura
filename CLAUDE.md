# CLAUDE.md — Queen of Compass: Vijetnam 2026

## Projekat

Višestranični sajt na srpskom jeziku za luksuzno grupno putovanje kroz Vijetnam.

- **Brend:** Queen of Compass
- **Voditelji:** Irena i Bojan (žive u Vijetnamu 5 godina)
- **Termin:** 8–22. april 2026. (15 dana)
- **Cena:** 1890 EUR po osobi
- **Maks. putnika:** 12
- **Instagram:** @queenofcompass

---

## Dizajn

**Stil:** Luksuzni travel magazin — upečatljiv, nezaboravan, NON-GENERIC. Nikada generički AI dizajn, predvidivi layouti, dosadni šabloni.

### Boje (CSS varijable)
```css
--tamno-zelena: #4d5b28;   /* Dominantna */
--zuta: #ffff00;            /* Akcentna */
--ljubicasta: #b282ff;      /* Akcentna */
--narandzasta: #ff9812;     /* Akcentna */
--roza: #e35eee;            /* Akcentna */
```

### Fontovi
- **Naslovi / Display:** Playfair Display (Google Fonts)
- **Tekst / Body:** DM Sans (Google Fonts)

### Animacije
- Page load: staggered reveal (elementi ulaze jedan po jedan)
- Scroll-triggered animacije (IntersectionObserver)
- Hover efekti na svim interaktivnim elementima

### Layout
- Asimetričan, neočekivan
- Grid-breaking elementi gde ima smisla
- Pozadine: teksture, gradient mesh, dubina — nikada plosnate boje

---

## Stranice

| Fajl | Stranica |
|---|---|
| `index.html` | Početna — hero, kratki opisi svih sekcija sa CTA |
| `itinerar.html` | Plan i program (8–22. april, svaki dan posebno) |
| `galerija.html` | Fotografije Vijetnama |
| `smestaji.html` | Smeštaji (placeholder) |
| `cena.html` | Šta je uključeno / nije, cena 1890 EUR |
| `za-koga.html` | Za koga jeste i za koga nije ovo putovanje |
| `faq.html` | Često postavljana pitanja |
| `kontakt.html` | Instagram @queenofcompass + email forma |

---

## Navigacija

- Header sa logom i linkovima na sve stranice
- Aktivan link vizuelno označen
- Mobile responsive hamburger meni

---

## Fiksni elementi (sve stranice)

**WhatsApp dugme** — fiksirano dole desno, otvara novi tab:
```
https://wa.me/381640440467?text=Zdravo!%20Zanima%20me%20putovanje%20u%20Vijetnam%20u%20aprilu%202026.%20Mo%C5%BEete%20li%20mi%20re%C4%87i%20vi%C5%A1e%3F
```

---

## Slike

Slike se serviraju sa: `https://vietnam-trip-website.vercel.app`

### Dostupne slike
- `/images/logo.webp`
- `/images/8-april.webp` do `/images/22-april.webp` (svaki dan itinerera)
- `/images/istrazujemo-1.webp` do `/images/istrazujemo-4.webp`
- `/images/hvala-1.webp` do `/images/hvala-4.webp`
- `/images/za-koga-nije.webp`

Dodatne slike: Unsplash (Vietnam tema)

---

## Ton pisanja

- Srpski jezik
- Jednostavan, bez komplikovanih reči
- Direktan, topao, prijateljski
- Kratak tekst — pravo na stvar

---

## Odbrojavanje

Countdown do 8. aprila 2026. na početnoj stranici.
Nakon polaska ostaje vidljiv kao uspomena.

---

## Tehničko

- Čist HTML/CSS/JS (bez framework-a)
- Svaka stranica je poseban `.html` fajl
- Shared header/footer kroz JavaScript include ili copy-paste
- SEO optimizovan: meta tagovi, og:image, schema markup
- Mobile first, fully responsive
