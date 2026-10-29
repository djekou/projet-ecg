# Classification de battements cardiaques à partir d'ECG

Projet personnel d'IA appliquée au médical (L2 SPI).

## Objectif
Comparer deux approches pour classer des battements cardiaques (normal / anormal) sur la base MIT-BIH :
1. Caractéristiques extraites du signal + forêt aléatoire
2. Réseau de neurones convolutif 1D (PyTorch)

## Données
MIT-BIH Arrhythmia Database (PhysioNet), publique et anonymisée.

## Avancement
- [ ] Prise en main de l'environnement
- [ ] Lecture et visualisation de l'ECG
- [ ] Filtrage et détection des pics R
- [ ] Extraction de caractéristiques
- [ ] Modèle classique (forêt aléatoire)
- [ ] Réseau de neurones 1D
- [ ] Comparaison et conclusion

## Limites
À compléter. Ce projet est un exercice d'apprentissage et ne constitue pas un outil de diagnostic.

## Installation
```
python -m venv venv
source venv/bin/activate   # Windows : venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook
```
