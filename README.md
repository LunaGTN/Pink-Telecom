Lien vers les données (fichier csv): https://raw.githubusercontent.com/murpi/wilddata/master/quests/churn_telecom.csv

### Contexte


Le client est "Pinky" une entreprise de télécommunication, qui vend des forfaits téléphonique et internet. Ses clients sont donc abonnés, et paient mensuellement. Mais chaque mois, des clients résilient leur abonnement, c'est ce qu'on appelle le taux d'attrition (churn rate en anglais). C'est un indicateur très employé dans tous les secteurs avec des abonnements (télécom, énergie, banque, assurance, etc...).


Pinky dispose d'une plateforme d'appel, avec des conseillers. Les conseillers peuvent appeler les clients pour leur faire des propositions commerciales. Pinky a remarqué qu'il est presqu'impossible de faire revenir un client qui a résilié. Il préfère donc faire des propositions commerciales aux clients "à risque", avant qu'ils ne résilient.

C'est pourquoi Pinky fait appel à moi ! Pinky tm fournit une extraction d'un échantillon représentatif de sa base client, dont des clients qui ont résilié ce mois-ci. Mon but est de décrire les caractéristiques des clients ayant résilié et ce qui les distingue des autres clients. Puis je dois proposer un scoring pour chaque client, afin de prioriser les appels vers les clients les plus à risque.

### Organisation
- **Fichier "machine_learning"** : Traitement des données avec une Pipeline, entraînement du model de régression logiqtique, critères d'évaluation du modèle avec F1 score et matrice de confusion. Enfin, analyse de l'importance de chaque feature sur le résultat final avec SHAP. 
**NB**: Avant de lancer le fichier analysis, télécharger le nouveau csv à la fin du fichier "machine_learning".
- **Fichier "analysis"** : Analyse graphique des features qui sont ressorties auprès du SHAP.

### Capture d'écran rapport PowerBI

![alt text](image.png)

