I : EEG Signal Processing & Contrôle de Véhicule

## Objectif général

Développer un système BCI (Brain–Computer Interface) capable de reconnaître dans le signal EEG les intentions motrices : « gauche », « droite », « avancer », « reculer », puis piloter un véhicule (voiture, simulateur) en temps réel.

## Plan d’étude et développement (8 semaines)

1. **Bases du signal EEG** :  
   - Chargement et visualisation de signaux EEG (OpenBCI)  
   - Comprendre la nature et les artefacts du signal  
   - Notebook : `01_Bases_EEG.ipynb`

2. **Analyse temporelle et fréquentielle** :  
   - FFT, STFT, spectrogrammes  
   - Extraction de bandes de fréquences (alpha, beta…)  
   - Notebook : `02_Analyse_Temp_Freq.ipynb`

3. **Prétraitement et nettoyage** :  
   - Filtrage, suppression d’artefacts (ICA…)  
   - Alignement et normalisation  
   - Notebook : `03_Pretaitement.ipynb`

4. **Extraction de features** :  
   - Moyenne, écart-type, puissance spectrale, CSP, etc.  
   - Adaptation multi-classe (droite, gauche, avancer, reculer)  
   - Notebook : `04_Extraction_Features.ipynb`

5. **Classification multi-classique** :  
   - SVM, RandomForest, LDA, etc. avec `scikit-learn`  
   - Validation croisée, métriques (accuracy, confusion matrix)  
   - Notebook : `05_Classification_Classic.ipynb`

6. **Réseaux de neurones pour EEG** :  
   - MLP, CNN sur features ou signaux bruts  
   - Passage à `TensorFlow` / `PyTorch`  
   - Notebook : `06_Deep_Learning.ipynb`

7. **Approches avancées & fusion multimodale** :  
   - LSTM, tenseurs, fusion EEG+autres capteurs  
   - Modèles séquentiels pour séquences temporelles longues  
   - Notebook : `07_Approches_Avancees.ipynb`

8. **Projet final : BCI pour pilotage de véhicule** :  
   - Pipeline complet : extraction, classification multi-classe en temps réel  
   - Test en simulateur ou prototypage hardware  
   - Notebook : `08_Projet_Final.ipynb`

## Structure du dépôt



