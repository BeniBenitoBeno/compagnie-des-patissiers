# Project Status — Compagnie des Pâtissiers
> Mis à jour : mai 2025

---

## État général
Site vitrine statique (HTML/CSS/Tailwind) — déployé sur GitHub Pages.
URL : https://benibenitobeno.github.io/compagnie-des-patissiers/
Repo : https://github.com/BeniBenitoBeno/compagnie-des-patissiers

---

## Pages (✓ Terminées)

### index.html
| Section | Statut |
|---|---|
| Nav fixe scroll-spy + hamburger mobile | ✓ |
| Hero plein écran | ✓ |
| "Depuis 1995" en blanc/50 | ✓ |
| Positionnement 2 colonnes | ✓ |
| Nos gammes (3 cartes cliquables) | ✓ |
| Nouveautés 2025 (images cliquables + zoom hover) | ✓ |
| Équipe aperçu mosaïque | ✓ |
| Footer avec liens corrects | ✓ |

### nos-gammes.html (✓ Terminée)
- Sticky tabs + scroll-spy
- 3 bandeaux (Flans crus / Fonds de tarte / Clafoutis crus) avec titre visible
- 21 produits en grille + modal fiche produit
- `.nojekyll` fixe le problème des `_hero.jpg` sur GitHub Pages

### nos-patissiers.html (✓ Terminée)
- 10 membres avec postes corrects
- Odiouma B. (CP-2002-24), Charlotte M. (CP-2002-9), Tomsey B. (CP-2002-41)
- Charlotte D., Nicolas A., Xavier R., Sébastien M., Nicolas B., Vincent P., Steve B.
- Mosaïque 4 colonnes avec photos patissier-1/2/3

### mentions-legales.html (✓ Terminée)
- Contenu légal complet (LCEN, RGPD)
- Lien depuis footer de toutes les pages

### espace-professionnel.html (✓ Terminée)
- 6 ressources (catalogue, tarifs, échantillons, innovations, commercial, newsletter)
- Section avantages
- Formulaire contact pro (mailto)

---

## Navigation
- Underline or animé au hover sur tous les liens nav principaux
- `current` persistant sur nos-gammes.html
- Scroll-spy sur index.html pour "Qui sommes-nous" / "Innovation"
- Lien "Rencontrer l'équipe" → nos-patissiers.html ✓
- Lien "Espace professionnel" → espace-professionnel.html ✓

---

## GitHub Pages
- Repo public : BeniBenitoBeno/compagnie-des-patissiers
- Branch : master, root /
- `.nojekyll` en place (nécessaire pour les fichiers `_hero.jpg`)
- Push via : `GH_TOKEN=$(gh auth token) git -c http.postBuffer=157286400 push`
- `gh` CLI : `/tmp/gh-cli/gh_2.69.0_macOS_arm64/bin/gh` (téléchargé manuellement, Xcode CLI absent)

---

## Backlog — par priorité

| Priorité | Tâche | Statut |
|---|---|---|
| 🔴 Haute | Vérifier responsive mobile | À faire |
| 🟡 Moyenne | SEO meta tags + Open Graph | À faire |
| 🟡 Moyenne | Formulaire de contact fonctionnel (service tiers) | À faire |
| 🟢 Basse | `logo-white.png` (CSS invert utilisé en attendant) | À faire |
| 🟢 Basse | notre-histoire.html | À faire |

---

## Commits clés (session actuelle)
- `0f54655` — nos-gammes + nos-patissiers + brand_assets restructuration
- `df8420c` — .nojekyll (fix GitHub Pages + _hero.jpg)
- `3ac1af1` — portraits CP-2002 corrects
- `e537016` — mentions-legales.html
- `b260683` — espace-professionnel.html + innovations cliquables
- `82375e6` — nav underline + zoom innovations
- `5c3d00b` — CLAUDE.md session management

---

## Comment reprendre une session Claude Code

```
Lis workflows/project-status.md et brand_assets/brand_guidelines_CP.md, puis on continue le projet.
```
