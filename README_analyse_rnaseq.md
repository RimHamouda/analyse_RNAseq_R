
# 🧬 Analyse RNA-seq avec DESeq2

Ce projet explore l'expression différentielle de gènes entre deux conditions expérimentales (A vs B) à partir de données RNA-seq simulées. L'analyse est effectuée en R avec le package **DESeq2**, et comprend la détection des gènes différentiellement exprimés et la visualisation des résultats.

---

## 📁 Fichiers du projet

- analyse_rnaseq_R.Rmd : script complet de l'analyse en R Markdown
- comptage_rnaseq.csv : tableau de comptage simulé
- genes_significatifs.csv: fichier des gènes significatifs
- volcano_plot.png : graphique de type volcano plot généré

---

## 🧪 Étapes de l'analyse

1. **Chargement des données de comptage** ('read.csv')
2. **Préparation du design expérimental** ('coldata')
3. **Création de l'objet DESeq2** ('DESeqDataSetFromMatrix')
4. **Analyse différentielle** ('DESeq')
5. **Filtrage des gènes significatifs** ('padj < 0.05')
6. **Visualisation des résultats** :
   - Volcano plot ('ggplot2')
   - Export des résultats ('write.csv')

---

## 📊 Interprétation

L'analyse révèle plusieurs gènes significativement régulés entre les conditions A et B :

- log2 Fold Change : variation d'expression entre les conditions
- p-value ajustée ('padj') : significativité statistique après correction
- Les gènes les plus extrêmes apparaissent dans le volcano plot

---

## 🧰 Outils utilisés

- R, RStudio
- Packages : 'DESeq2', 'ggplot2', 'tidyverse'

---

## 👩‍💻 Auteure

Rim Hamouda  

🔗 [LinkedIn](https://www.linkedin.com/in/ton-profil)  
📁 [GitHub](https://github.com/RimHamouda)
