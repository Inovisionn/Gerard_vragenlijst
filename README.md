# Gerard Peeters – DBA Research Landing Page

Landingspagina voor het DBA-onderzoek van Gerard Peeters naar ESG en duurzame verpakkingsinkoop in Nederland.

## Inhoud

- `index.html` – de volledige landingspagina (HTML + CSS in één bestand)

## Deployen op Vercel

### Stap 1 – GitHub repository aanmaken

1. Ga naar [github.com/new](https://github.com/new)
2. Geef de repository een naam, bijv. `gerard-peeters-landing`
3. Laat de repository **Public** staan (vereist voor gratis Vercel-hosting)
4. Klik op **Create repository**

### Stap 2 – Bestanden uploaden naar GitHub

**Optie A – via de GitHub website (geen Git vereist):**
1. Open de zojuist aangemaakte repository
2. Klik op **Add file → Upload files**
3. Sleep `index.html` naar het uploadvenster
4. Klik op **Commit changes**

**Optie B – via de terminal:**
```bash
git init
git add index.html
git commit -m "Initial commit: landing page"
git branch -M main
git remote add origin https://github.com/JOUW-GEBRUIKERSNAAM/gerard-peeters-landing.git
git push -u origin main
```

### Stap 3 – Verbinden met Vercel

1. Ga naar [vercel.com](https://vercel.com) en log in (of maak een gratis account aan)
2. Klik op **Add New → Project**
3. Klik op **Import Git Repository** en selecteer jouw GitHub repository
4. Vercel herkent automatisch dat het een statische HTML-pagina is
5. Klik op **Deploy**

Na een paar seconden is de pagina live op een gratis `.vercel.app` URL.

### Optioneel – eigen domeinnaam koppelen

In het Vercel-dashboard onder **Settings → Domains** kun je een eigen domeinnaam toevoegen.

---

*DBA Research | Gerard Peeters – Onderzoek naar ESG en duurzame verpakkingsinkoop in Nederland*
