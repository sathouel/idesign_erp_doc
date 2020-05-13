# CHAPITRE 15 - PROCESSUS D’ACHAT DE MARCHANDISE AUX USINES

* A - Créer un nouveau bon de Commande 
* B - Paiement de l’acompte s’il y en a un – créer une écriture de paiement
* C - Paiement du solde de notre commande quelques jours avant l’arrivage au port (afin de recevoir le XXP DOCUMENT) -  créer une deuxième écriture de paiement.
* D - Créer la facture d’achat
* E - Créer un Reçut d’achat lorsque la marchandise nous parvient </br>
**Si c’est un nouveau produit vous devez tout d’abord créer l’article dans le system pour pouvoir ensuite placer une commande**

## A - Créer un nouveau bon de Commande 

1. **Créer un nouveau bon de Commande : Créer un bon de commande pour l’achat de marchandise aux usines en remplissant les champs nécessaires : fournisseur, date de réception, articles quantités et prix commandées, et les échéances de paiement au fournisseur**
    1. IMPACT SUR STOCK – La création d’un achat créer automatiquement une écriture de stock en arrivage pour les quantités sélectionnées. Le stock passera en disponible lorsque la marchandise sera arrivée c’est à dire lorsqu’un reçut d’achat sera créer (point 5)
2. **Vous devez également joindre le fichier Excel ou pdf reçu par l’usine** en ajoutant une ou plusieurs pièce jointe sur la partie gauche de l’écran dans le bon de commande en question section "PIECES JOINTES". De cette façon nous aurons toujours la dernière PI et informations techniques à jour envoyée par l’usine afin de comparer l’exactitude des données a tout moments.

## B - Paiement de l’acompte s’il y en a un – créer une écriture de paiement

**Paiement de l’acompte s’il y en a un – créer une écriture de paiement. ATTENTION, les autorisations comptables sont nécessaires pour procéder à cette étape.**

1.	Ouvrir le bon de commande en question, dans la section tableau de bords cliquer sur le signe + a cote d’écriture de paiement. 
2.	Remplir alors les champs nécessaire (compte société et compte fournisseur) et surtout saisir le montant qui correspond à l’acompte que vous désirez verser (le montant total apparaitra automatiquement c’est à vous de l’ajuster en fonction du % d’acompte). 
3.	Enregistrer puis soumettre, les écritures comptables sont alors automatiquement faite et l’acompte est enregistré comme paye dans le system ERP. Faire le virement nécessaire correspondant sur le site de la banque au préalable pour pouvoir renseigner la référence de la transaction bancaire lors de l’écriture de paiement

## C - Paiement du solde de notre commande quelques jours avant l’arrivage au port

**Paiement du solde de notre commande quelques jours avant l’arrivage au port (afin de recevoir le DOCUMENT TELEX RELEASE nécessaire pour la réception conteneurs au port) -  créer une deuxième écriture de paiement.**

**ATTENTION, les autorisations comptables sont nécessaires pour procéder à cette étape.**

1.	 Ouvrir le bon de commande en question, dans la section tableau de bords cliquer sur le signe + a cote d’écriture de paiement. 
2.	Remplir alors les champs nécessaire (compte société et compte fournisseur). Le montant du solde s’affiche automatiquement en déduisant le premier paiement d’acompte déjà fait. 
3.	Enregistrer puis soumettre, les écritures comptables sont alors automatiquement faites et le paiement du solde est enregistré comme paye dans le system ERP. Faire le virement nécessaire correspondant sur le site de la banque au préalable pour pouvoir renseigner la référence de la transaction bancaire lors de l’écriture de paiement

## D - Créer la facture d’achat

**Créer la facture d’achat - ATTENTION, les autorisations comptables sont nécessaires pour procéder à cette étape.**

1.	Ouvrir le bon de commande en question, dans la section tableau de bords cliquer sur le signe + a cote Facture d’Achat. 
2.	Les champs seront déjà remplis, défiler jusqu'à la section **PAIEMENT ANTICIPES et cliquer sur Obtenir Acomptes payes**, les 2 paiement précédents vont alors apparaître. 
3.	Enregistrer puis soumettre, les écritures comptables sont alors automatiquement faites et la facture est enregistrée comme payée grâce aux 2 paiement précédents. 

## E - Créer un Reçut d’achat lorsque la marchandise nous parvient

**Créer un Reçut d’achat lorsque la marchandise nous parvient :**

1.	Ouvrir notre bon de commande d’achat de marchandise, 
2.	Dans le tableau de bord cliquer sur le signe + a cote de "reçut d’achat", 
3.	Vérifier que les quantités sont correct puis appuyer en haut à droite sur le bouton enregistrer puis soumettre. **Le stock sera alors automatiquement mis à jour avec les quantités reçues** maintenant disponible dans le stock et non plus en commandées
