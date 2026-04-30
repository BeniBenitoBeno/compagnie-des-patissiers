# Brand Guidelines — Compagnie des Pâtissiers
> Évolution identitaire 2025 — Document de référence pour Claude Code & Claude Design

---

## 1. Positionnement

### Essence de marque
**"L'artisan à grande échelle"**
Le geste du pâtissier, reproduit avec exigence. Une élégance qui ne renonce pas à l'authenticité.

### Cible
- **Primaire (B2B)** : boulangers, pâtissiers artisanaux, restaurateurs, distributeurs, GMS
- **Secondaire (B2C)** : grand public sensible à la qualité et à l'origine

### Ton de marque
Confiant · Précis · Chaleureux · Sobre · Expert

Ne jamais utiliser : "exceptionnel", "incontournable", "passion", "authenticité" (trop galvaudés).
Phrases courtes. La qualité s'affirme, elle ne se crie pas.

### Ce que CDP est / n'est pas
| CDP est | CDP n'est pas |
|---|---|
| Élégant sans être froid | Une épicerie de village |
| Industriel sans être banal | Un chef étoilé inaccessible |
| Français sans être nostalgique | Une marque low-cost |
| Expert sans être hermétique | Une vitrine agro générique |

---

## 2. Logo

### Fichier
`brand_assets/logos/logo.png` — Cercle noir, version blanc à créer

### Description
Cercle noir · Typographie mixte : script serif pour "Pâtissiers", caps pour "COMPAGNIE DES" · Emblème épi de blé centré

### Règles d'usage
- **Sur fond clair** : logo noir (version par défaut)
- **Sur fond sombre** : logo blanc (inverser)
- **Zone de protection** : marge minimum = 1/4 du diamètre du cercle sur chaque côté
- Ne jamais déformer, recolorer, ou ajouter d'ombre portée au logo
- Ne jamais placer le logo sur fond jaune/or

### Appartenance groupe
La Compagnie des Pâtissiers appartient au **Groupe MAS** ("French Quality Food").
Le logo Groupe MAS peut apparaître en contexte institutionnel uniquement — jamais en compétition visuelle avec CDP.

---

## 3. Palette de couleurs

### Couleurs principales

| Nom | Hex | Usage |
|---|---|---|
| **Noir Fondateur** | `#1A1A18` | Primaire — textes, contours, header, footer |
| **Blanc Atelier** | `#FFFFFF` | Fond principal, texte sur noir |
| **Ivoire Doux** | `#F7F4EE` | Sections alternées, backgrounds secondaires |
| **Gris Atelier** | `#6B6860` | Corps de texte, labels, métadonnées |

### Couleur d'accent

| Nom | Hex | Usage |
|---|---|---|
| **Or Pâtissier** | `#F2C94C` | Accents ponctuels, flèches, underlines, badges "Innovation" |

### Règles d'utilisation couleurs
- Le noir et l'ivoire **structurent**
- L'or **ponctue** — jamais en aplat sur de grandes surfaces, jamais comme fond de bouton primaire
- Ne jamais mettre du texte blanc sur fond or (lisibilité insuffisante)
- Ne jamais utiliser la palette Tailwind par défaut (indigo, blue-600, etc.)
- Dériver toutes les nuances à partir de ces 5 couleurs

---

## 4. Typographie

### Display — Playfair Display
- **Usage** : H1, H2, citations, sections héros, noms de gammes
- **Graisses** : 400 Regular, 400 Italic, 500 Medium
- **Tracking** : `-0.02em` sur les grands titres
- **L'italique** : réservé aux accents poétiques et noms de produits
- **Import** : `https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,500;1,400`

### Corps — Inter
- **Usage** : corps de texte, navigation, boutons, labels, fiches produit
- **Graisses** : 300 Light (body long), 400 Regular, 500 Medium (UI)
- **Line-height** : `1.7` pour le corps, `1.2` pour les grands titres
- **Navigation** : 500 Medium, letter-spacing `0.06em`, uppercase
- **Import** : `https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500`

### Règle fondamentale
Ne jamais utiliser la même police pour les titres et le corps. Playfair Display + Inter uniquement.

---

## 5. Photographie

### Registre général
- **Ambiance** : sombre, organique, matières brutes, éclairage directionnel
- **Angle** : overhead (vue du dessus) privilégié pour les mises en scène ingrédients
- **Traitement** : légèrement désaturé, chaleur conservée, contrastes marqués
- **Fond** : bois sombre, ardoise, marbre gris — jamais de fond blanc studio pour les ambiances
- **Produits packagés** : fond neutre clair acceptable

### Règles de traitement
- Gradient overlay sombre sur les images hero : `background: linear-gradient(to top, rgba(0,0,0,0.6), transparent)`
- Ne pas surcharger la mise en scène (3 éléments max autour du produit)
- Toujours laisser de l'espace négatif pour le texte en superposition

---

## 6. Assets — Inventaire & Chemins

### Logos
```
brand_assets/
  logos/
    logo.png                    # Logo cercle noir sur fond blanc (fourni)
    logo-white.png              # À créer : version inversée
    logo.svg                    # À fournir si disponible en vectoriel
```

### Photographie — Ambiance
```
brand_assets/photography/ambiance/
  slider-groupe-mas.png         # Image hero principale (ingrédients overhead, style sombre)
```

### Photographie — Équipes
```
brand_assets/photography/team/
  CP-2002-24_Retouche.jpg       # https://compagniedespatissiers.com/app/uploads/2022/10/CP-2002-24_Retouche-scaled.jpg
  CP-2002-9_Retouche.jpg        # https://compagniedespatissiers.com/app/uploads/2022/10/CP-2002-9_Retouche-scaled.jpg
  CP-2002-41_Retouche.jpg       # https://compagniedespatissiers.com/app/uploads/2022/10/CP-2002-41_Retouche-scaled.jpg
  Charlotte_D.jpg               # https://compagniedespatissiers.com/app/uploads/2021/07/20_Charlotte_D_2MO-scaled.jpg
  Nicolas_A.jpg                 # https://compagniedespatissiers.com/app/uploads/2019/01/7_Nicolas_A-2.jpg
  Xavier_R.jpg                  # https://compagniedespatissiers.com/app/uploads/2019/01/8_Xavier_R-2.jpg
  Sebastien_M.jpg               # https://compagniedespatissiers.com/app/uploads/2019/01/9_Sebastien_M-2.jpg
  Nicolas_B.jpg                 # https://compagniedespatissiers.com/app/uploads/2019/01/11_Nicolas_B-2.jpg
  Vincent_P.jpg                 # https://compagniedespatissiers.com/app/uploads/2019/01/14_Vincent_P-2.jpg
  Steeve_B.jpg                  # https://compagniedespatissiers.com/app/uploads/2019/01/15_Steeve_B-2.jpg
```

### Photographie — Produits
```
brand_assets/photography/products/

  categories/
    bake-off-category.jpg       # https://compagniedespatissiers.com/app/uploads/2021/09/FondCru-e1646643046877.jpg
    a-partager-category.png     # https://compagniedespatissiers.com/app/uploads/2019/11/Sans-titre-3.png

  flans-crus/
    _hero.jpg                   # https://compagniedespatissiers.com/app/uploads/2022/03/CiePatissiers-FinalEdit1-Adrien_Dubuisson_Photographe-JPG-HD-122-scaled-e1646143936218.jpg
    flan-pistache.png           # https://compagniedespatissiers.com/app/uploads/2025/06/Flan-Pistache.png
    flan-a-lancienne.png        # https://compagniedespatissiers.com/app/uploads/2025/03/Flan-SDA-a-lancienne-Site.png
    flan-coco-bande.jpg         # https://compagniedespatissiers.com/app/uploads/2021/12/500050-scaled-e1639135135944.jpg
    flan-classique-bande.jpg    # https://compagniedespatissiers.com/app/uploads/2021/12/500048-2-e1639133801965.jpg
    flan-chocolat.jpg           # https://compagniedespatissiers.com/app/uploads/2019/01/CiePatissiers-FinalEdit1-Adrien_Dubuisson_Photographe-JPG-HD-127_Carre-1.jpg
    flan-coco.png               # https://compagniedespatissiers.com/app/uploads/2019/01/Sans-titre-10.png
    flan-pur-beurre-premium.jpg # https://compagniedespatissiers.com/app/uploads/2019/01/CiePatissiers-FinalEdit1-Adrien_Dubuisson_Photographe-JPG-HD-112_Carre-1.jpg
    flan-cremeux-pur-beurre.jpg # https://compagniedespatissiers.com/app/uploads/2019/01/CiePatissiers-FinalEdit1-Adrien_Dubuisson_Photographe-JPG-HD-118_Carre-1.jpg
    flan-classique.jpg          # https://compagniedespatissiers.com/app/uploads/2019/01/CiePatissiers-FinalEdit1-Adrien_Dubuisson_Photographe-JPG-HD-195_Carre-1.jpg

  fonds-de-tarte/
    _hero.jpg                   # https://compagniedespatissiers.com/app/uploads/2021/09/FondCru-e1646643046877.jpg
    couronne.png                # https://compagniedespatissiers.com/app/uploads/2025/03/Couronne-Site-Web.png
    garni-frangipane-stick.png  # https://compagniedespatissiers.com/app/uploads/2019/07/Sans-titre-13.png
    sucree-cacao-stick.png      # https://compagniedespatissiers.com/app/uploads/2019/07/Sans-titre-12.png
    garni-frangipane.png        # https://compagniedespatissiers.com/app/uploads/2019/01/Sans-titre-11.png
    garni-creme-legere.png      # https://compagniedespatissiers.com/app/uploads/2019/01/Sans-titre-3.png
    sucree-rond.jpg             # https://compagniedespatissiers.com/app/uploads/2019/01/Cie_Patissiers_2018_Fuveau-Adrien_Dubuisson_Photographe-354_Carre-1.jpg
    sucree-stick.jpg            # https://compagniedespatissiers.com/app/uploads/2019/01/Cie_Patissiers_2018_Fuveau-Adrien_Dubuisson_Photographe-215_Carre-1.jpg
    sablee-stick.jpg            # https://compagniedespatissiers.com/app/uploads/2019/01/Cie_Patissiers_2018_Fuveau-Adrien_Dubuisson_Photographe-237_Carre-1.jpg
    brisee-rond.jpg             # https://compagniedespatissiers.com/app/uploads/2019/01/CO-PAT-PDANIEL-023_Carre-1.jpg
    brisee-stick.jpg            # https://compagniedespatissiers.com/app/uploads/2019/01/Stick-Brise-mise-en-scene_Carre.jpg

  clafoutis-crus/
    _hero.png                   # https://compagniedespatissiers.com/app/uploads/2025/08/Clafoutis-Poires-Choco-1.png
    framboises-rhubarbe.png     # https://compagniedespatissiers.com/app/uploads/2025/08/Clafoutis-Framb-Rhub.png
    griottes.png                # https://compagniedespatissiers.com/app/uploads/2025/08/Clafoutis-Cerises.png
    poires-chocolat.png         # https://compagniedespatissiers.com/app/uploads/2025/08/Clafoutis-Poires-Choco-1.png
    pommes.png                  # https://compagniedespatissiers.com/app/uploads/2025/08/Clafoutis-Pommes.png
```

> **Note pour Claude** : Si les fichiers locaux ne sont pas encore téléchargés, utiliser les URLs directement depuis compagniedespatissiers.com. Toujours préférer les assets locaux en production.

---

## 7. Composants UI

### Boutons
```css
/* Primaire */
background: #1A1A18; color: #F7F4EE;
border: none; padding: 10px 24px;
font-family: Inter; font-size: 13px; font-weight: 500;
letter-spacing: 0.06em; border-radius: 2px;

/* Secondaire */
background: transparent; color: #1A1A18;
border: 1px solid #1A1A18; /* mêmes dimensions */

/* Lien texte avec accent or */
color: #1A1A18; border-bottom: 1px solid #F2C94C;
/* Flèche : → en couleur #F2C94C */
```

### Tags & badges
```css
/* Nouveauté */
background: #1A1A18; color: #F7F4EE;
font-size: 10px; letter-spacing: 0.12em; text-transform: uppercase; padding: 4px 12px;

/* Catégorie neutre */
border: 0.5px solid #6B6860; color: #6B6860; background: transparent;

/* Innovation / mise en avant */
background: #F2C94C; color: #1A1A18;
```

### Cartes produit
- Image sur fond sombre ou neutre
- Badge catégorie (tag) en haut
- Nom produit en Playfair Display 400
- Description courte en Inter 300, couleur `#6B6860`
- CTA "Fiche produit →" avec underline or

### Espacement
- Sections : padding vertical `80px–120px`
- Grille : 12 colonnes, gouttière `24px`
- Composants internes : multiples de `8px`

---

## 8. Règles visuelles

### À faire
- Espaces blancs généreux — le vide est du luxe
- Asymétrie contrôlée — texte et image jamais parfaitement symétriques
- Alignements à gauche favorisés
- Surfaces en couches : base → elevated → floating
- Animations uniquement sur `transform` et `opacity`, jamais `transition-all`
- Chaque élément cliquable : états hover, focus-visible, active obligatoires

### À ne jamais faire
- Ombres portées lourdes (box-shadow décoratif)
- Dégradés criards ou multicolores
- Icônes cartoon ou clipart
- `transition-all`
- Texte sur fond jaune/or
- Bouton avec fond jaune/or comme action primaire
- Palette Tailwind par défaut (indigo, blue-600…)
- Même police pour titres et corps

---

## 9. Structure de fichiers du projet

```
brand_assets/
  brand_guidelines_CP.md           ← CE FICHIER (lu automatiquement par Claude)
  logos/
  photography/
    ambiance/
    team/
    products/
      categories/
      flans-crus/
      fonds-de-tarte/
      clafoutis-crus/
workflows/                      # SOPs Claude (WAT framework)
tools/                          # Scripts Python
.env                            # Clés API (ne jamais versionner)
```

---

*Dernière mise à jour : avril 2025*
*Usage : Claude Code (terminal), Claude Design (frontend)*
