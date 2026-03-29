# SGD, Adam et Cie : qui est le meilleur entraîneur de neurones ?

**TIPE – Classes Préparatoires (2024-2025)**

*Gabriel Roux-Dessarps*

---

## Sujet

Ce travail compare les performances de différents optimiseurs utilisés pour l'entraînement de réseaux de neurones convolutifs (CNN) :

- **SGD** (Stochastic Gradient Descent)
- **SGD + Momentum**
- **Adam** (Adaptive Moment Estimation)

L'étude porte sur la vitesse de convergence, la stabilité et la précision finale de chaque optimiseur, testés notamment sur les jeux de données **CIFAR-10** et **MNIST**.

## Contenu

- Présentation de l'architecture des CNN
- Mise en œuvre en Python avec Keras
- Formalisation mathématique des optimiseurs
- Optimisation bayésienne des hyperparamètres (taux d'apprentissage)
- Comparaison expérimentale sur plusieurs jeux de données

## Résultats clés

- **SGD + Momentum** offre une meilleure accuracy en temps long et une plus grande stabilité grâce à son pas constant.
- **Adam** converge plus rapidement dans les premières époques, mais se montre moins stable sur le long terme.
- Les résultats varient selon la complexité du jeu de données utilisé.

## Consulter la présentation

📄 [**Slides (PDF)**](./slides.pdf)

## Outils utilisés

Python · Keras · NumPy · Matplotlib · LaTeX (Beamer)
