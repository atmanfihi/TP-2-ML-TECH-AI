# TP2 IA — Apprentissage profond avec TensorFlow / Keras

Deux notebooks déjà exécutés (sorties, courbes et matrices de confusion incluses), avec les réponses à toutes les questions et l'analyse personnelle demandée pour le rapport.

| Notebook | Contenu | Résultat test |
|---|---|---|
| `Exercice1_MNIST.ipynb` | Réseau dense sur MNIST, courbes de précision et de perte, prédictions et erreurs | 97,53 % |
| `Exercice2_FashionMNIST.ipynb` | ANN, comparaison sigmoïde / tanh / ReLU / LeakyReLU, CNN, matrice de confusion, data augmentation | ANN 87,15 % · CNN 90,50 % · CNN + augmentation 91,10 % |

## Exécution
```
pip install -r requirements.txt
jupyter notebook
```
Les datasets sont téléchargés automatiquement par `mnist.load_data()` et `fashion_mnist.load_data()` au premier lancement.
Les valeurs peuvent varier légèrement d'une machine à l'autre (initialisation, CPU/GPU) malgré la graine fixée.
