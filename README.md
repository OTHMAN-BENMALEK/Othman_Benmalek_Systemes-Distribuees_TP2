# Othman_Benmalek_Systemes-Distribuees_TP2


1. Installer IntelliJ Ultimate

![Capture d’écran 2024-04-13 212059](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribuees_TP2/assets/159661363/01f8c806-543c-4ca0-a2c6-a13e4cb3fd87)

2. Créer un projet Spring Initializer avec les dépendances JPA, H2, Spring Web et Lombock
![New project dependencies](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribuees_TP2/assets/159661363/dc263b33-cb01-4592-baf2-56391158d1cd)
![New project SpringInitializer](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribuees_TP2/assets/159661363/3b4e358c-97f4-4b13-8cc0-a363177f8c85)

3. Créer l'entité JPA Patient ayant les attributs :
       - id de type Long
       - nom de type String
       - dateNaissanec de type Date
       - malade de type boolean
       - score de type int
![Product class + persistance configuration](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribuees_TP2/assets/159661363/0325f5db-9adc-4193-957b-ce5be2f981f6)

4. Configurer l'unité de persistance dans le ficher application.properties 
![Application properties](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribuees_TP2/assets/159661363/51ee18a3-8500-4d47-92db-4438e0e5e09e)
5. Créer l'interface JPA Repository basée sur Spring data
![Adding 3 while using JPA](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribuees_TP2/assets/159661363/026057f0-6002-4cea-bc2f-d4355c6ab7fe)
6. Tester quelques opérations de gestion de patients :
D'abord on a utilisé la base de données H2 :
![Database screen ](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribuees_TP2/assets/159661363/1dc9ca7a-42bd-4479-a5a7-d3636a4e16c9)

    - Ajouter des patients
      ![Adding 3 product Code](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribuees_TP2/assets/159661363/7d1c7369-4ef8-4b70-ba73-45d7730114ea)
      ![Adding 3 product to DB](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribuees_TP2/assets/159661363/2087617c-544e-4c8e-9d90-4a4089504c82)

    - Consulter tous les patients
      ![Consulter tous les produits](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribuees_TP2/assets/159661363/c0da698d-bc2a-4668-b9ae-15fee626c16d)

    - Consulter un patient
      ![Chercher Un produit](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribuees_TP2/assets/159661363/c5cec932-c4de-4871-aa94-bb1f22196e0f)

    - Chercher des patients
      ![Chercher Un produit par nom ](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribuees_TP2/assets/159661363/c357fae3-fa5b-4395-9513-73abb0df6053)

    - Mettre à jour un patient
      ![Mettreàajout un produit ](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribuees_TP2/assets/159661363/b116f985-eb63-4149-a8a4-6d1c729447fb)
      ![Résultat après MàJ](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribuees_TP2/assets/159661363/d0bca278-a026-4d1d-b19d-3c5e8dd4df29)

    - supprimer un patient
      ![Supprimer Produit 3](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribuees_TP2/assets/159661363/9fc87687-b960-4f4f-9153-528e9ed8b1e8)
      ![Résultat après Suppression du produit 3](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribuees_TP2/assets/159661363/43795797-7c8d-4a89-b9b7-21a97d5f3c03)

8. Migrer de H2 Database vers MySQL
      ![Migration vers MySQL](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribuees_TP2/assets/159661363/07cff094-a120-4916-b9e0-1a2c64185ee6)
J'ai utilisé le WampServer :
      ![Création de la table MySQL Products-db](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribuees_TP2/assets/159661363/d2b90f00-95b3-4cc5-91ca-f718737a768a)
      ![Table de produits dans MySQL](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribuees_TP2/assets/159661363/1408686d-ea6d-4acd-9bff-74a91ffe3f2d)

