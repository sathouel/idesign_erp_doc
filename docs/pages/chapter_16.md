# CHAPITRE 16 - COMMANDE TRANSITAIRE POUR LIVRAISON DE MARCHANDISE ACHETEE

**Enregistrer une demande de transite associée à un bon de commande d’achat de marchandise**

* A - Créer un nouveau bon de Commande 
* B - Créer un Reçut d’achat lorsque la marchandise nous parvient 
* C - Paiement de la facture reçu du transitaire – créer une écriture de paiement. 
* D - Enregistrement des écritures comptables restantes (éclatement de la facture transitaire) – créer une écriture de journal
* E - Clore le bon de commande en passant le statut a "FERME"

## A - Créer un nouveau bon de Commande 

**Créer un nouveau bon de Commande : Créer un bon de commande pour une livraison conteneur ne nécessite pas de remplir les mêmes champs que pour de l’achat de marchandise.**

1.	**Remplir le champs Fournisseur avec le nom du transitaire** (le system reconnaitra que ce fournisseur est un transporteur avec un  qui apparaitra en bas du nom de transitaire choisis)
2.	**Remplir le champ "commande associe"** : sélectionner dans le rouleau la commande d’achat de marchandise que ce transitaire va prendre en charge 
3.	**Remplir les champs de la section " conteneur Info"** : Numéro de PI fournisseur, date de chargement, date d’arrivée au port, date d’arrive au dépôt, description conteneur (40HQ ou 1 20hq + 1 40HQ etc..). Ces champs pourront être mis à jour même après soumission du document dans le cas où la date e livraison/d’arrivée changent
4.	**Remplir le tableau d’article** pour finaliser l’enregistrement du service transitaire : Sélectionner l’article "transite conteneur", quantité =1, et mettre le prix du transport TTC annoncée.
5.	En haut à droite cliquer sur le **bouton Enregistrer, puis Soumettre**

**Une fois que le service de transport est effectué, nous recevons la facture du transitaire pour ses services.** 

## B - Créer un Reçut d’achat lorsque la marchandise nous parvient 

**Créer un Reçut d’achat lorsque la marchandise nous parvient :** 

1.	Ouvrir notre bon de commande transitaire, 
2.	Dans le tableau de bord cliquer sur le signe + a cote de "reçut d’achat", puis appuyer en haut à droite sur le bouton enregistrer puis soumettre. 
3.	Vous n’avez rien à remplir, cette action indique uniquement que la livraison a été faite et qu’elle n’est donc plus attendu, il ne reste plus qu’à payer les frais au transitaire.

## C - Paiement de la facture reçu du transitaire – créer une écriture de paiement. 

**Paiement de la facture reçu du transitaire – créer une écriture de paiement.** </br>
**ATTENTION, les autorisations comptables sont nécessaires pour procéder à cette étape.** </br>
**<span style="color: red">ATTENTION NE JAMAIS CREER DE FACTURE D’ACHAT POUR LES BON DE COMMANDES TRANSITAIRE</span>**

1.	Ouvrir le bon de commande en question, dans la section tableau de bords **cliquer sur le signe + a cote d’écriture de paiement.** 
2.	Remplir alors les champs nécessaire **(compte société et compte fournisseur)**, le montant à payer se remplira automatiquement comme 100% de la sommes précédemment indiquer, **veillez à vérifier que le montant correspond à la facture**. Et **remplir les identifiants de transactions** fournis par la banque. (Faire le virement nécessaire correspondant sur le site de la banque au préalable pour pouvoir renseigner la référence de la transaction bancaire lors de l’écriture de paiement)
3.	**En haut à droite, Enregistrer puis soumettre**. Une partie uniquement des écritures comptables sont alors automatiquement faite (celle du compte fournisseur et celle de la banque) les autres écritures nécessitant un éclatement de la facture plus spécifique qui se fera manuellement dans l’étape suivante ; l’écriture de journal.

## D - Enregistrement des écritures comptables restantes (éclatement de la facture transitaire) – créer une écriture de journal

**Enregistrement des écritures comptables restantes (éclatement de la facture transitaire) – créer une écriture de journal.**</br> **ATTENTION, les autorisations comptables sont nécessaires pour procéder à cette étape.**

1.	Ouvrir le bon de commande en question, dans la section tableau de bords **cliquer sur le signe + a cote d’écriture de journal.** Puis ajouter les écritures comptables nécessaire dans le tableau grâce au bouton "Ajouter une ligne", sélectionner les comptes comptables, les tiers et type de tiers ainsi que les montant en débit et crédit, 
2.	Dans la section Reference vous pouvez renseigner le numéro de facture correspondant du transitaire, ainsi que la date et date d’échéance
3.	**En haut à droite, Enregistrer puis soumettre. Les écritures comptables sont maintenant toutes enregistrées**

## E - Clore le bon de commande en passant le statut a "FERME"

**Clore le bon de commande en passant le statut a "FERME"** 

1. Ouvrir le bon de commande en question, en haut à droite cliquer sur le bouton "STATUS" et cliquer sur Fermer.
