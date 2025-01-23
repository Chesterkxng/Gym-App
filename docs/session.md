![GymApp Logo](/images/logo_md.png "GymApp Logo")

# Gestion des séances

La gestion des séances est une fonctionnalité centrale qui assure un suivi structuré et efficace des clients de votre salle de sport. Elle vous permet d’inscrire des clients, de gérer leurs séances et de suivre leurs paiements de manière claire et intuitive.

---

## **Ajouter un séance**

Pour ajouter un séance, procédez comme suit :  
1. Accédez au formulaire d'ajout de séances :  
   ![navbar add session](/images/screenshots/session/nav_add.png "navbar add session")  

2. Renseignez les informations suivantes :  
   - **Informations du client** :  
     - _Nom_  
     - _Prénom_  
     - _Genre_  
     - _Téléphone_  
     - _Date de naissance (facultatif)_  
     - _Email (facultatif)_  
     - _Adresse (facultatif)_  
   - **Informations de la séance** :  
     - _Forfait_ (cf. [Gestion des forfaits](package.md#gestion-des-forfaits))  
     - _La date et l'heure (ajouté automatiquement)_

   ![adding Form](/images/screenshots/session/add_form.png "adding Form")  

   > **Note 1** : Utilisez cette interface uniquement pour la **première séance** d’un client. Pour les reconductions ultérieures, ce formulaire n’est plus nécessaire, car les informations du client sont déjà enregistrées.
   > **Note 2** : La date et l'heure sont celles du moment de l'enregistrement de la séance.
   > **Note 3** : La séance reste valable durant toute la journée.

---

## **Modifier une séance**

1. Accédez à la liste des séances via le menu déroulant :  
   ![navbar list session](/images/screenshots/session/nav_list.png "navbar list session")  

2. Cliquez sur le bouton correspondant à la séance pour ouvrir le formulaire de modification.  
   ![edit session btn](/images/screenshots/session/edit_btn.png "edit session btn")  

3. Modifiez les informations souhaitées et cliquez sur **MODIFIER SEANCE**.  
   ![edit subscription form](/images/screenshots/session/edit_form.png "edit subscription form")  

   > **Note** : Les informations du client ne sont pas modifiables depuis cette interface.  
   > **Note** : La modication d’une séance met à jour automatiquement les statistiques dans les tableaux de bord. 

---

## **Reconduire une séance**

1. Cliquez sur le bouton correspondant à la séance à reconduire :  
   ![reconduct subscription btn](/images/screenshots/session/reconduct_btn.png "reconduct subscription btn")  

   > **Note**: 
    > - Identifiez facilement les séances expirées grâce à la colonne **STATUT** (indiquée par des **puces grises**).
    > - Les **puces jaunes** indiquent que le client a souscrit pour une séance ce jour.
    > - Les **puces vertes** indiquent que le client dispose d'un abonnement en cours.

2. Confirmez la reconduction en cliquant sur **RECONDUIRE SEANCE**.  
   ![reconduct session form](/images/screenshots/session/reconduct_form.png "reconduct session form")  

   > **Note** : La date et l'heure sont celles du moment de l'enregistrement de la séance.

---

## **Supprimer une séance**

1. Cliquez sur le bouton **SUPPRIMER** pour accéder au formulaire de suppression :  
   ![delete session btn](/images/screenshots/session/delete_btn.png "delete session btn")  

2. Confirmez la suppression en cliquant sur **SUPPRIMER SEANCE**.  
   ![delete session form](/images/screenshots/session/delete_form.png "delete session form")  

   > **Note** : La suppression d’une séance est irréversible et met à jour automatiquement les statistiques dans les tableaux de bord.

---

## **Liens de navigation**

- [_Retour au Sommaire_](table.md)  
- [_Page précédente : Gestion des abonnements_](subscription.md)  
- [_Page suivante : Gestion de stock_](stock.md)
