# 📊 Analyse de la dette propre de la Ville de Paris  
### *Projet Data – Finances publiques & Risque de concentration*

##  Description du projet
Ce projet consiste en une analyse complète de la **dette propre de la Ville de Paris**, à partir du dataset officiel disponible sur l’Open Data Paris.  
L’objectif principal est d’étudier la **structure d’endettement** et d’évaluer le **risque de concentration des prêteurs**.

---

##  Objectif analytique
**Hypothèse :** La Ville de Paris dépend-elle excessivement de certains prêteurs ?

L’étude analyse :
- la diversité des prêteurs  
- la part de marché de chacun  
- l’évolution de la concentration  
- l’indice HHI  
- la répartition obligations vs emprunts bancaires  
- les prêteurs dominants  

---

##  Principaux résultats

- **Montant total de dette initiale :** 40,2 Md€  
- **Dette restante :** 38 Md€  
- **Nombre d’emprunts :** 610  
- **Nombre de prêteurs :** 61  
- **HHI moyen :** 456,46  
- **66 %** d’obligations vs **33 %** d’emprunts bancaires  

---

##  Méthodologie
1. **Collecte via API Open Data Paris**  
2. **Nettoyage & traitement des données**  
3. **Chargement MySQL** pour validation SQL  
4. **Création de dashboards Power BI**  
5. **Calculs HHI, parts de marché, indicateurs clés**  
6. **Synthèse & recommandations stratégiques**

---

##  Validation SQL
Les mesures Power BI ont été vérifiées dans MySQL :  
- HHI  
- parts de marché  
- totaux dette  
- distribution par prêteur  

Document : *Validation_avec_SQL.pdf*

---

##  Livrables inclus
- CSV bruts & nettoyés  
- 3 notebooks Jupyter  
- Fichier Power BI  
- Rapport PDF  
- Validation SQL  
- README  

---

##  Recommandations
1. Diversifier davantage les prêteurs  
2. Surveiller régulièrement l’indice HHI  
3. Analyser les conditions des prêteurs les plus sollicités  
4. Optimiser la stratégie obligations vs banques  
5. Simuler des scénarios de stress financier  
6. Ajouter des alertes et analyses automatisées dans Power BI  
