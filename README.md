# -Active-Directory-Les-Unit-s-D-Organisations-ou-Unit-Organisationnelle



## Création de l'Unité d'Organisation `Wilders_students`

1. Ouvrir **Utilisateurs et ordinateurs Active Directory** depuis **Gestionnaire de serveur**.
2. Faire un clic droit sur le domaine `wilders.lan`.
3. Sélectionner **Nouveau** > **Unité d'organisation**.
4. Nommer l'Unité d'organisation : `Wilders_students`.
5. Cliquer sur **OK**.

![OU wilder-students ](https://github.com/user-attachments/assets/54eb69f1-acf8-4ebe-b5cc-78025d0fb334)

## Création du Groupe d'Utilisateurs `Students`

1. Dans **Utilisateurs et ordinateurs Active Directory**, développer `wilders.lan` > `Wilders_students`.
2. Faire un clic droit sur `Wilders_students` > **Nouveau** > **Groupe**.
3. Nommer le Groupe : `Students`.
4. Sélectionner **Groupe de sécurité** et **Portée globale**.
5. Cliquer sur **OK**.

6. ![students ](https://github.com/user-attachments/assets/e168fbad-00b4-4029-9b38-00050c5acbe2)

## Création d'un Utilisateur et Ajout au Groupe `Students`

1. Faire un clic droit sur `Wilders_students` > **Nouveau** > **Utilisateur**
2. Remplir les informations : Prénom, Nom et Nom d'ouverture de session (lisa et david ).
3. Cliquer sur **Suivant**, entrer un mot de passe et configurer les options.
4. Cliquer sur **Suivant** puis **Terminer**.
![les utilisateur (students) crée ](https://github.com/user-attachments/assets/54756f1b-ffc7-48d3-a6b4-db79e618c72b)

5. Faire un clic droit sur l'utilisateur créé > **Propriétés** > **Membre de** > **Ajouter**.
6. Taper `Students` et cliquer sur **OK**.

![add users (lisa et david)](https://github.com/user-attachments/assets/34c44f5f-06a9-4035-80cf-a21d6e6d743d)
