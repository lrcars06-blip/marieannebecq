# Marie-Anne Becq — site vitrine

Tapissière, couture d'ameublement — Rampont (Meuse).

## Structure
```
index.html      page unique (HTML + CSS + JS inline)
images/         78 photos optimisées (≤1800 px, JPEG progressif)
```

## Dépendances (CDN, aucune installation)
- GSAP 3.12.5 + ScrollTrigger — cdnjs
- Lenis 1.1.18 — jsdelivr (smooth scroll ; retirer la balise `<script>` pour s'en passer)
- Google Fonts : Fraunces, Instrument Sans, Pinyon Script

## Lancer en local
```
npx serve .
```
ou ouvrir `index.html` dans Chrome/Safari (les animations au scroll ont besoin d'une vraie fenêtre).

## Déployer
GitHub Pages / Vercel / Netlify : déposer le dossier tel quel, `index.html` à la racine.

## Sections
intro manuscrite + rideau · hero parallaxe · marquee · manifeste mot à mot · avant/après épinglés (11 paires, curseur) · galerie sièges horizontale pilotée au scroll · mosaïque + lightbox · chapitres rideaux / scène / hôtels · nounours · maisons de tissus · mobilier de créateurs · portrait · plan d'atelier animé semaine par semaine · contact

## À brancher
- Formulaire : actuellement `mailto:` → Formspree / Resend.
- Photos nounours : captures 480 px, à remplacer par les originaux.
- Plan de l'atelier : schéma de principe, dimensions à valider avec la cliente.
- Chiffres (800+ sièges, 10 ans) : à valider.
