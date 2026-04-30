# Project Status — Compagnie des Pâtissiers
> Mis à jour : avril 2025

---

## État général
Site vitrine statique (HTML/CSS/Tailwind) — en cours de développement.
Repo Git initialisé sur `master`.

---

## Assets & structure (✓ Terminé)

- Repo git initialisé sur `master`
- Structure `brand_assets/` complète : `logos/`, `photography/ambiance|team|products/`
- 37 assets photo téléchargés depuis compagniedespatissiers.com
  - team ×10, flans-crus ×10, fonds-de-tarte ×11, clafoutis-crus ×5, categories ×2, ambiance ×1
- `CLAUDE.md` mis à jour avec la section `brand_assets/`
- `.gitignore` en place (`.env`, `.tmp/`, `credentials`)

---

## Pages

### index.html (✓ Terminé)
Single file · Tailwind CDN · Playfair Display + Inter · Palette brand exacte

| Section | Statut |
|---|---|
| Nav fixe (transparent → sombre au scroll) | ✓ |
| Hero plein écran (slider-groupe-mas.png) | ✓ |
| Positionnement (grille 2 colonnes) | ✓ |
| Nos gammes (3 cartes sur fond noir) | ✓ |
| Innovation 2025 (3 nouveautés) | ✓ |
| Équipe (mosaïque 3 colonnes) | ✓ |
| Footer 4 colonnes + Groupe MAS | ✓ |

**Corrections appliquées :**
- Badge "CRU SURGELÉ" → glass effect + texte noir
- Badge "INNOVATION" retiré du header Innovation
- Boutons "FICHE PRODUIT" → alignés au même niveau
- Mosaïque équipe → `height: 220px` fixe + `object-top` pour les visages
- "Depuis 1986" → corrigé en "Depuis 1997"
- "La Compagnie" → corrigé en "Compagnie des Pâtissiers"

### Pages internes (✗ À faire)
- `nos-gammes.html` — catalogue produits
- `nos-patissiers.html` — équipe
- `notre-histoire.html` — à propos
- `contact.html` — formulaire de contact

---

## Backlog — par priorité

| Priorité | Tâche | Statut |
|---|---|---|
| 🔴 Haute | Vérifier responsive mobile | À faire |
| 🔴 Haute | Créer les pages internes | À faire |
| 🟡 Moyenne | SEO meta tags + Open Graph | À faire |
| 🟡 Moyenne | Formulaire de contact fonctionnel | À faire |
| 🟢 Basse | `logo-white.png` (remplacé par CSS invert) | À faire |
| 🟢 Basse | `serve.mjs` / `screenshot.mjs` (Node absent) | Bloqué |

---

## Comment reprendre une session Claude Code

Au début de chaque nouvelle session, colle cette instruction :

```
Lis workflows/project-status.md et brand_assets/brand_guidelines.md, puis on continue le projet.
```

---

## Commits clés
- `b4b5f6c` — Init repo + structure brand_assets
- `9f8f905` — Téléchargement assets photo
- `c7e12ee` — CLAUDE.md mis à jour
- `7fd2791` — index.html v1
- `a734820` — Corrections visuelles
- `5794b2f` — Corrections contenu (1997, Compagnie)
- `9b7009b` — Boutons et mosaïque équipe
