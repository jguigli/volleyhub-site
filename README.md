# volleyhub-site

Site vitrine de **VolleyHub** — landing page, politique de confidentialite et conditions d'utilisation.

## Structure

```
index.html        Landing page (hero, features, CTA)
privacy.html      Politique de confidentialite
terms.html        Conditions d'utilisation
style.css         Styles (responsive, mobile-first)
i18n.js           Traductions FR/EN pour la landing page
legal-i18n.js     Traductions FR/EN pour les pages legales
assets/
  logo.png        Logo VolleyHub
```

## Fonctionnalites

- **i18n FR/EN** : bouton de bascule dans le header, langue sauvegardee dans `localStorage` (`vh_lang`)
- **Pages legales dynamiques** : le contenu de `privacy.html` et `terms.html` est injecte via `legal-i18n.js` selon la langue
- **Responsive** : adapte mobile, tablette et desktop
- **Zero dependance** : HTML/CSS/JS vanilla, police Inter via Google Fonts

## Lancer en local

Ouvrir `index.html` dans un navigateur ou utiliser un serveur statique :

```bash
# avec Python
python3 -m http.server 8080

# avec npx
npx serve .
```

## Deploiement

Site statique deployable sur n'importe quel hebergeur (Netlify, Vercel, GitHub Pages, Cloudflare Pages, etc.).
