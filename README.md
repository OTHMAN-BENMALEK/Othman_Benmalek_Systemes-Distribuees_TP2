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


   Pour la Question 8 :
   Dans le dossier "Question 8" , il existe deux app :

   1iere application : Hospital APP :
   Nous avons utilisé Start Spring.io
   ![Start  Spring  IO](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribuees_TP2/assets/159661363/91d236ad-fd1c-47ca-b770-37347e484937)

   Architecture du projet :


   ![Project architecture ](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribuees_TP2/assets/159661363/1b51f5d7-6569-44c7-a30c-c68fa455a198)


   Ajout de 3 personnes dans la base h2 :
   ![1)Ajout de 3 personnes dans la base h2](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribuees_TP2/assets/159661363/0bff8d91-cedd-42cb-810e-395b18c49fa3)
   ![1-1) Résultat de l'ajout de 3 Personnes dans la base h2](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribuees_TP2/assets/159661363/46221285-de31-47c0-bc3b-dca90b8e3d1e)
    Ajout de 3 medecins :
    ![2)Ajout de 3 medecins dans la base h2](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribuees_TP2/assets/159661363/13466681-3fe5-4ecd-b6ff-25252d5ede86)
   ![2-1)Resultat de l'ajout de 3 Medecins dans la base h2](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribuees_TP2/assets/159661363/fd36ac5a-330e-4575-a971-05dcf0cc56a9)
   Creation d'un rendez-vous :
   ![3)Creation d'un RendezVous (patient et medecin ) ](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribuees_TP2/assets/159661363/272063e6-8514-43e1-bd8e-21320c7b8566)
   ![3-1)Resultat de creation d'un rendez vous dans h2 après ajout de type Enumerated de type String ](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribuees_TP2/assets/159661363/df87fbca-3ec1-4159-8d32-e4794149fa51)
   Consultation :
   ![4)Consultation](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribuees_TP2/assets/159661363/f7557dcd-0905-4774-9d30-30c6bbc6335a)
   ![4-1)Consultation ](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribuees_TP2/assets/159661363/4334cbaa-9b63-45f4-b9de-7031ac913f7b)
   Package service et creation d'une interface :
   ![5-1)Ajout du package service et creation d'une interface ](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribuees_TP2/assets/159661363/3bae3a72-9fef-4413-9125-8b6fc6359741)
   Implementation de l'interface :
   ![5-2)Implementation de l'interface ](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribuees_TP2/assets/159661363/4d2d9498-73cd-4171-ab95-a2ec0d478839)
   Utilisation de UUID :
   ![6-1)UUID dans l'implementation](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribuees_TP2/assets/159661363/79510e99-421b-4314-88bb-63fa30ad83d2)
   ![6-2)Resultat de UUID](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribuees_TP2/assets/159661363/681f1fbf-6362-4bda-8dd4-772b9045ebed)
   Resultat JSON :


   ![7-1)JSON resultat](https://github.com/OTHMAN-BENMALEK/Othman_Benmalek_Systemes-Distribuees_TP2/assets/159661363/2bef20ae-84b6-4909-892c-b1c493f0f319)



   



   



