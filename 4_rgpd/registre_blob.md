# Registre des Traitements des Données RGPD pour un Blob Azure contenant des photos

| **Source de données**   | **Nature des données**             | **Finalité du traitement**                      | **Cycle de vie des données**                          | **Risques identifiés**                                            | **Mesures de sécurité mises en œuvre**                                                                                     |
|--------------------------|------------------------------------|------------------------------------------------|-------------------------------------------------------|------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------|
| **Blob Azure (Photos)**  | Données personnelles sensibles    | Stockage d’images pour identification ou usage lié à un service | Conservation : 1 an après la dernière interaction ou conformément à la finalité spécifiée | Accès non autorisé, fuite de données sensibles, mauvaise gestion de l’accès | Chiffrement des blobs, accès limité via RBAC, ACL (Listes de contrôle d’accès) |

---

On pourrait également ajouter aux mesures de sécurité : Journalisation des accès, Sauvegardes régulières, Monitoring via Azure Security Center.
