# TP_CNN_Malaria — Classification d’hématies (Paludisme)

## Objectif
Classer des images d’hématies en **infectée (parasitized)** vs **saine (uninfected)** avec 3 modèles CNN :
1) CNN **from scratch** (Sequential + Dropout)  
2) **VGG16** pré-entraîné ImageNet (fine-tuning)  
3) **ResNet50** pré-entraîné ImageNet (fine-tuning) :contentReference[oaicite:0]{index=0}

## Livrables
- Un notebook Jupyter **clair et commenté** : `TP_CNN_Malaria.ipynb`
- Entraînement des **3 modèles** avec callbacks (**EarlyStopping** + **LR Decay**) + sauvegarde des poids
- Évaluation : **confusion matrix**, accuracy/precision/recall/f1 + **sensibilité/spécificité**, **ROC + AUC**
- Tableau comparatif + interprétation (limites/pistes) :contentReference[oaicite:1]{index=1}

## Dataset
Dataset NIH (Malaria datasets) : images d’hématies en 2 classes  
- `parasitized/` : infectée  
- `uninfected/` : saine :contentReference[oaicite:2]{index=2}


