# Script de la Vidéo Explicative (60 à 90 Secondes)

**Format :** Capture d'écran commentée en français (720p minimum).

---

### ⏱️ 0–20 s : Introduction & Problématique
> "Bonjour, je présente le projet F29 sur la prévisibilité du facteur momentum. La question clé est de savoir si l'apprentissage automatique permet d'anticiper la hausse du mois suivant à partir des signaux historiques, tout en résistant aux coûts de transaction de marché."

### ⏱️ 20–45 s : Jeu de données & Modèle
> "Nous utilisons 1 185 mois de données Ken French de 1927 à 2026. Pour éviter toute fuite d'information, nous appliquons un découpage chronologique 80/20. Notre modèle principal est une Régression Logistique régularisée avec pondération équilibrée des classes."

### ⏱️ 45–75 s : Résultats & Simulation Financière
> "Sur le test set 2007–2026, la Régression Logistique atteint 57,8% d'exactitude contre 47,7% pour la référence naïve. En intégrant des frais de 0,10% par arbitrage, le modèle génère +9,78% de rendement net contre -17,34% pour la référence, grâce à une réduction des arbitrages inutiles (55 vs 124)."

### ⏱️ 75–90 s : Conclusion & Limite Principale
> "En conclusion, le modèle capte la tendance mais subit un risque de crash élevé avec un Drawdown Max de -56,52%. L'ajout d'un filtre de volatilité dynamique est la principale perspective d'amélioration. Merci."
