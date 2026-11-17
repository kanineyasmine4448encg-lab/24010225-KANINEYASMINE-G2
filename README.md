# Projet ML Finance — Sujet F29 : Prévisibilité du Momentum

**Auteur :** Projet Individuel · S7 FIN & CI · Année 2026–2027  
**Dépôt GitHub :** `CodeApogee-Nom-Groupe`  
**Sujet F29 :** Prévisibilité du momentum (Classification binaire)

## Description du Projet
Ce projet évalue la prévisibilité du facteur Momentum de Ken French (1927–2026) à l'aide d'algorithmes de Machine Learning (Régression Logistique & Random Forest). L'évaluation respecte un protocole temporel anti-fuite (80/20) et intègre une simulation de coûts de transaction (0.10% par arbitrage).

## Arborescence du Dépôt
```text
CodeApogee-Nom-Groupe/
├── README.md
├── requirements.txt
├── DECLARATION_IA.md
├── data/raw/
│   └── momentum_ken_french.csv
├── notebooks/
│   └── projet_F29.ipynb
├── figures/
│   ├── figure1_distribution_rendements.png
│   ├── figure2_correlation_momentum.png
│   └── figure3_performance_modeles.png
├── rapport/
│   └── rapport.pdf
├── presentation/
│   ├── presentation.pptx
│   └── presentation.pdf
└── video/
    └── script_video.md
```

## Mode d'Exécution
1. Installer les dépendances : `pip install -r requirements.txt`
2. Lancer le notebook : `jupyter notebook notebooks/projet_F29.ipynb`
