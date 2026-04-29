# 🌍 Hot&Fresh — Gestion de Stock Interne

Application web interne de gestion de stock, production et chiffre d'affaires pour les établissements Hot&Fresh.

## 📋 Description

Outil de gestion tout-en-un pour les 5 établissements :
- 🏠 **Ravezies** — Restaurant principal
- 🎓 **Campus du Lac** — CCI Bordeaux Gironde
- 💻 **Ynov** — École digitale
- 🏫 **Mirail** — Université
- 🍕 **Eat Pizza** — Restaurant pizza

## 🚀 Utilisation

Ouvrir `index.html` dans un navigateur — aucune installation requise.

### Codes d'accès
| Code | Accès |
|------|-------|
| `1234` | Accès complet (Stock + Production + CA) |
| `Talgat` | Accès CA uniquement (voir + modifier) |

## 📱 Fonctionnalités

### 📦 Module Stock
- Suivi matières premières par établissement
- Seuils de commande avec alertes (OK / À commander / Critique)
- Prix d'achat Metro + valeur du stock calculée
- Produits organisés par catégories (accordéon)

### 🏭 Module Production
- **Onglet Flux** — Sorties & retours par jour (boutons +/−)
- **Onglet Semaine** — Vue Lun→Ven avec détection des produits à perte (rouge si retours ≥ 3 jours)
- **Onglet Suivi** — Top 5 vendus / Top 5 invendus / Taux d'écoulement / Graphiques par famille
- **Onglet Inventaire** — Boulangerie : stock début / reçu / utilisé / invendus / stock fin
- **Onglet Production** — Plan de production agrégé tous établissements avec calcul auto du besoin
- **Vue Totale** — Tous les stocks en une page + bouton "Commande passée" pour remettre à zéro

### 💶 Module CA (code Talgat)
- Saisie couverts + CA € par jour et par établissement
- Navigation par semaine (← →) avec historique
- Drill-down : clic sur une semaine passée → détail jour par jour
- Vue mensuelle comparative (3 / 6 / 9 mois)
- Graphiques : courbe d'évolution + histogramme par établissement

## 💾 Données

Les données sont sauvegardées dans le **localStorage** du navigateur.
- Persistantes entre les sessions sur le même navigateur
- Pas de serveur requis
- Export : bouton "Enregistrer" (FAB vert en bas à droite)

## 🚚 Livraisons Metro

**Mardi & Jeudi à 7h30** — indicateur automatique dans la topbar et le calendrier.

## 📁 Structure du projet

```
hotfresh-stock/
├── index.html       # Application complète (fichier unique)
└── README.md        # Ce fichier
```

## 🛠️ Technologies

- HTML5 / CSS3 / JavaScript vanilla
- Chart.js 4.4.0 (graphiques CA et suivi)
- Google Fonts (Syne + DM Sans)
- Aucune dépendance serveur

## 📲 Compatible

- ✅ Ordinateur (Chrome, Firefox, Safari, Edge)
- ✅ Tablette
- ✅ Mobile

---

*Hot&Fresh — Food mood depuis 2014 🌍*
