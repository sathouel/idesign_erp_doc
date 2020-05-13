# CHAPITRE 19 - CREER DES CONDITIONS DE PAIEMENT – Achats et Vente

**Dans ce processus il faudra créer plusieurs termes de paiement pour ensuite les combiner afin de créer un modèle de paiement. C’est le model de paiement qui sera à appliquer aux client/fournisseur/bon de commande etc.**

1. Taper dans la bar de recherche **Terme de paiement Liste**

2. Cliquer sur le bouton **Nouveau** en haut à droite

3. Remplir **"Nom du terme de paiement"** – c’est à dire donner un nom au terme de paiement que vous êtes en train de créer. Exemple, si vous souhaiter créer une condition de paiement qui soit 20% d’acompte a la commande alors vous pouvez nommer le terme de paiement comme"20% d’acompte" par exemple)

4. Remplir **"Pourcentage de facturation"** – Ici il faudra indiquer le pourcentage de la facture que vous souhaitez conditionner. A savoir toujours dans notre exemple de 20% d’acompte a la commande, vous souhaitez que 20% de la commande ai une date de paiement différente du reste donc vous écrirez 20 (sans besoin de mettre le signe %)

5. Sélectionner **"Date d'échéance basée sur"** – ici vous avez 3 choix pour décider à partir de quel moment voulez-vous que les termes de paiement soient comptabilisés. Les 3 choix sont 1. Nombres de jours après la date de facturation, 2. Nombre de jours après la fin du mois de facture ou 3. Nombre de jours après la fin du mois de la facture. Reprenons notre exemple de créer une condition de paiement qui soit 20% d’acompte a la commande – ici vous sélectionnerez 1. Nombres de jours après la date de facturation.

6. Remplir **"Jours de Crédit"** – ici vous indiquerez le nombre de jour après la date de facturation après lesquelles le paiement est due. Ici si les 20% d’acompte sont due immédiatement, il faudra alors remplir par le chiffre zéro. En admettant que nous ayons une fenêtre de 5 jours pour effectuer ce paiement à partir de la date de commande alors nous remplirons ces champs par le chiffre 5 

7. Remplir **"Mode de Paiement"** – champs facultatif pour indiquer que ce terme de paiement sera fait par virement/cheque/carte/espèces

8. Remplir **"Description"** – Rédiger la description de votre terme de paiement vous prêtera de clarifier la règle appliquer- ici une bonne description de notre exemple serait" Paiement de 20% de la somme a réaliser immédiatement (ou sous 5 jours) à partir de la date de facturation de la commande

**ATTENTION – Vous venez de créer UNIQUEMENT les 20% d’acompte à travers cette condition de paiement, vous devez maintenant créer un autre terme de paiement pour définir les 80% restant (qui pourraient être due à réception de la marchandise / à 60 jours de la commande / à la réception de marchandise ou il faudra alors estimer le nombre de jours entre la commande et l’arrivée de la marchandise. Pour créer les 80% restant nous faisons une nouvelle création de condition de paiement exactement de la même façon qu’expliquer au-dessus mais maintenant avec 80%**

**Une fois que vos termes de paiement (partiels) sont créer, Vous devrez les unir afin de créer une condition de paiement COMPLETE cad qui regroupera les 20% et les 80%. Pour cela :**

1.	Taper dans la bar de recherché **Modèle de termes de paiement Liste**

2.	Cliquer sur le bouton **Nouveau** en haut à droite

3.	Remplir **"Nom du model"** – Vous allez nommer le model de paiement que vous créez qui va combiner 2 terme de paiement (ou plus que 2 si les conditions de paiement que vous souhaitez créer sont un échelonnement sur 3 temps, 4 temps ou plus, il faudra juste créer autant de terme de paiement que nécessaire). Pour reprendre notre exemple, nous combiner 2 terme de paiement :a).les 20% d’acompte a date de la commande et b)les 80% a 60 jours de la comm**ande. Nous pouvons donc **nommer ce model comme 20% comptant, 80% à 60 jours par exemple

4.	Remplir le tableau **"Termes de paiement"** – ici vous allez sélectionner dans la première ligne, première colonne le terme de paiement créer au préalable pour les 20% d’acompte (un rouleau va apparaitre avec tous les termes de paiement créer plus haut. En sélectionnant un de ces termes de paiement, les colonnes suivantes vont se remplir automatiquement avec les informations entrées lors de la création de vos termes de paiement plus haut) puis dans la deuxième ligne vous vous allez sélectionner le terme de paiement créer au préalable pour les 80% d’acompte de la même façon. 

**Ainsi vous créer un MODEL de termes de paiement qui regroupe plusieurs termes de paiement partiel pour créer un model complet dont la somme cumulée est de 100% du paiement**
