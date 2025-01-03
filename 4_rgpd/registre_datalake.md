# Registre des Traitements des Données RGPD pour un Data Lake Azure contenant des CSV

| **Source de données**       | **Nature des données**             | **Finalité du traitement**                      | **Cycle de vie des données**                          | **Risques identifiés**                                            | **Mesures de sécurité mises en œuvre**                                                                                     |
|------------------------------|------------------------------------|------------------------------------------------|-------------------------------------------------------|------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------|
| **Data Lake Azure (CSV Étudiants)** | Données personnelles (noms, prénoms, emails, téléphones, région) | Gestion administrative et reporting des étudiants | Conservation : 5 ans après la fin de la relation contractuelle | Accès non autorisé, fuite de données sensibles, mauvaise gestion des droits d'accès | Chiffrement des fichiers CSV, Contrôle des accès basés sur les rôles (RBAC) |
| **Data Lake Azure (CSV Formateurs)** | Données personnelles et professionnelles (noms, emails, téléphones, spécialisations, salaires) | Gestion des ressources humaines et suivi des formateurs | Conservation : 5 ans après la fin de la relation contractuelle | Fuite de données professionnelles, non-conformité aux réglementations | Chiffrement des fichiers CSV, Contrôle des accès basés sur les rôles (RBAC) |

---

On pourrait également ajouter aux mesures de sécurité : Journalisation des accès, Sauvegardes régulières, Monitoring via Azure Security Center.