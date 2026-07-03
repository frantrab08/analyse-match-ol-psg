# ⚽ Analyse de match — OL 0-1 PSG (Ligue 1, 2022)

Analyse tactique et statistique complète du match **Olympique Lyonnais – Paris Saint-Germain**
(8ᵉ journée de Ligue 1, 18 septembre 2022), réalisée à partir des données **StatsBomb Open Data**
et traitée en **Python**.

📄 **[Lire le rapport complet (PDF)](./rapport/OL_PSG.pdf)**

## 🎯 Objectif
Raconter le match avec des preuves chiffrées : qui a contrôlé l'espace et le rythme,
où le danger est né, et à quel moment la dynamique a basculé entre les mi-temps.

## 📊 Ce que contient l'analyse
- Formations moyennes et centroïdes de possession
- Carte des tirs et course d'**xG**
- **Field tilt** (territoire) et cartes de passes
- Progression du ballon (passes / conduites progressives)
- Vitesse d'attaque et *directness*
- Intensité de pressing (**PPDA**) et *gegenpress*
- Phases arrêtées (corners, coups francs)

## 🛠️ Outils
Python · pandas · numpy · matplotlib

## 📁 Données
[StatsBomb Open Data](https://github.com/statsbomb/open-data) — match ID `3837717`
