# CHAPITRE 18 - PROCESSUS DE VENTE D’ARTICLES AUX CLIENTS, COMMANDE, PREPARATION ET LIVRAISON 

* A - CREATION DE COMMANDE CLIENT
* B - STATUT DE COMMANDE CLIENT
* C - CREATION DE BON DE LIVRAISON & ENVOIE EN PREPARATION LOGISTIQUE 
* D - GESTION ET SOUMISSION DES BON DE LIVRAISON UNE FOIS LA PREPARATION LOGISTIQUE TERMINEE 
* E - CREATION DE SERVICE DE LIVRAISON – PRISE DE RDV POUR LIVRAISON/ENLEVEMENT DE COMMANDE
* F - FACTURATION – CREATION DE FACTURE DE VENTE
* G - REGLEMENT CLIENT – CREATION D’ECRITURE DE PAIEMENT
* H - ESCOMPT - ECRITURE DE JOURNAL MANUEL APRES VERIFICATION PAR SYLVIANE ET RECEPTION DU VIREMENT CLIENT

## A - CREATION DE COMMANDE CLIENT

**Créer une commande client :** 

1. Entrer dans la section commande client et cliquer sur le bouton Nouveau(elle) en haut à droite de l’écran.

    1. Compléter le champs client en choisissant parmi les clients dans le system (certains champs seront automatiquement remplis comme le numéro de Tva, la sous-section adresse et contact). Veillez à vérifier que l’adresse de livraison préenregistrer est bien l’adresse correcte. Autrement vous pouvez en sélectionnez une autre ou créer une adresse supplémentaire pour le client. Remplir la date de livraison désirée ainsi que le numéro de bon de commande du client 

    2. Listing Prix appliqué – Dans la sous-section ‘’DEVISE ET LISTING PRIX" vous trouverez les champs pré-remplis associé au client sélectionné. Vous pouvez à tout moment ouvrir la sous-section pour vérifier que le listing prix attribué est bien correct par rapport au client sélectionné 

    3. Sélectionner les articles pour la commande client dans le tableau Articles – remplir les champs ‘’code de l’article" et ‘’Quantité" et ajouter des ligne grâce au bouton en dessous du tableau ‘’ajouter une ligne’’. Les champs livraison, prix et montant total se rempliront automatiquement grâce aux informations précédemment renseignées et au listing prix sélectionné.

    4. **ETAT DU STOCK ET STATUS PAR LIGNE – Pour chaque ligne d’article insérée dans le tableau d’article, un tableau apparaitra en dessous faisant état des états de stock sur l’article concernée et identifiant automatiquement si le produit est (a) EN STOCK, (b) STOCK EN TRANSIT, (c) PAS DE STOCK, (d) STOCK EN PARTIE DISPO, LE RESTE EN ARRIVAGE.**Vous saurez donc dès la saisis de la commande, si la commande peut être immédiatement envoyer en préparation, ou s’il faut contacter le client pour le prévenir qu’un ou plusieurs articles sont en arrivage ou en rupture et l’informer de nouveau délais ou proposer un remplacement de produits en rupture.
        * (a) EN STOCK – Statut Disponible,
        * (b) STOCK EN TRANSIT – Statut En Arrivage,
        * (c) PAS DE STOCK – Statut Non Disponible. 
        * (d) STOCK EN PARTIE DISPO, LE RESTE EN ARRIVAGE – Statut HYBRIDE

    5. Les totaux, écotaxe et TVA sont automatiquement calculée en identifiant si le client est Français (soumis à l’écotaxe et la TVA) ou pas. Les termes de paiement sont également automatiquement remplis grâce à la configuration au préalable des clients et leurs termes de paiement respectif associé.

    6. Cliquez sur le bouton en haut à droite - ENREGISTRER – pour enregistrer puis soumettre la commande client. Notez, tant que la commande n’est pas soumise, les stocks ne sont pas réservés, une commande en brouillon ne réserve pas de stock, uniquement une commande soumise réserve du stock

## B - STATUT DE COMMANDE CLIENT

**STATUT DE COMMANDE CLIENT – une fois votre commande client enregistrer et soumise, retourner dans la liste des commandes clients et observer les STATUTS ID-  voici les 3 statut et conséquences et marche à suivre qui en découlent :**

1.	**STATUT ID = VALIDE** Si toutes les lignes d’articles de la commande sont en stock, alors **la commande est valide, et prête a être envoyée en préparation logistique. Les stocks sont réservés**

2.	**STATUT ID = EN ATTENTE** Si une ou plusieurs lignes d’articles de la commande sont en arrivage ou que certaines quantités demandées dépassent le stock actuellement disponible et doit être complétée par du stock en arrivage (donc avec un délais et pas immédiatement disponible), alors la commande est en attente. Les stocks sont réservés. 
Cependant la commande ne peut être envoyer en préparation tel quelle puisque tous les articles ne sont pas physiquement disponibles de suite. Il faudra donc contacter le client pour convenir avec lui d’un nouveau délai, ou de plusieurs envois de marchandise et envoyer en préparation uniquement les articles disponibles, en laissant le reste des articles en attente jusqu'au nouvel arrivage de marchandise déjà prévu. </br>
**Dans le cas d’une commande EN ATTENTE CAR contenant une ou plusieurs lignes HYBRIDE** (cad que toute la quantité commandée n’est pas actuellement dispo en stock mais uniquement une partie, l’autre partie étant en arrivage). 
    * Il vous faudra **modifier la commande** (cliquer sur annuler en haut a droite puis sur modifier) en divisant la (ou les) ligne d ‘article HYBRIDE en 2 quantités différentes ; une ligne avec la quantité dispo de suite et une ligne avec le restant de quantité demandée qui sera en attente car par encore en stock (rappelez-vous que toutes les quantités dispos et en arrivage pour chaque produit se trouve dans le tableau en dessous de votre tableau d’article)

    * La commande sera alors une commande EN ATTENTE mais maintenant sans aucune ligne hybride et se comportera donc comme une commande en attente ‘normal’ précédemment décrite. Suivre la même démarche que déjà décrit, contacter le client et établir les délais.  

3.	**STATUT ID = INVALIDE**: Si une ou plusieurs lignes d’articles de la commande ne sont plus en stock, ou que la quantité sélectionnée est supérieur a la quantité en stock et en arrivage, alors **la commande est invalide** car elle ne peut être préparer en totalité au vu des manquants. **Une commande Invalide n’est pas soumise et ne peut être soumise, elle est enregistrée en BROUILLON et le restera jusqu'à modification ou retrait des articles manquants problématiques.</br>ATTENTION, tant que la commande est invalide (donc en brouillon) aucuns stocks sur la commande ne sont réservés.**</br>
**Le client doit donc être contactée dans les plus bref délais** pour retirer ces produits manquants, les remplacer ou ajuster la quantité en fonction de nos stocks afin de rendre la commande ‘’soummetable" et assurer que le restant des articles commandée soit toujours disponibles.

## C - CREATION DE BON DE LIVRAISON & ENVOIE EN PREPARATION LOGISTIQUE

**Création de bon de Livraison – envoie en préparation en logistique, la création de bon de livraison n’est possible que pour des commande VALIDES ou EN ATTENTE (uniquement en sélectionnant les lignes d’articles actuellement disponible).** 

1.	Ouvrir la commande client en question, dans la section tableau de bords **cliquer sur le signe + a cote de Bon de Livraison**, les champs seront tous pré-remplis, et le tableau d’articles avec leur quantité commandée sera repris en totalité, il vous suffit de cliquer sur **ENREGISTRER** en haut à droite.  Si vous voulez envoyer en préparation uniquement une partie de la commande (dans le cas d’une commande EN ATTENTE) alors vous devez supprimer les lignes non désirées dans le tableau d’article (les lignes non dispos seront marques d’un point orange et non vert) puis enregistrez</br>
**Par cet enregistrement, vous venez de créer un BROUILLON de bon de livraison ce qui a également créer une PREPARATION dans le système logistique pour les préparateurs de commandes. Si vous ne créez pas de brouillon de bon de livraison, les préparateurs ne reçoivent pas la commande.** 

2.	Une fois que le bon de livraison brouillon est créer, vous aurez le bouton SOUMETTRE en haute a droite qui apparaitra mais vous ne serez pas autorisée a soumettre un Bon de Livraison dont les informations (nombre de palettes et tailles de palettes) n’ont pas été remplie, vous devez donc attendre que le system vous informe que la préparation est terminée, vous pourrez alors soumettre le bon de livraison
    * Jauge % Prepa (dans la section commande client)  – cette jauge vous indique si vous avez créer un brouillon de bon de livraison et si donc la commande est bien descendue en préparation 

## D - GESTION ET SOUMISSION DES BON DE LIVRAISON UNE FOIS LA PREPARATION LOGISTIQUE TERMINEE 

Au cours de la préparation vous devez vous référer a la section "bon de Livraison" pour voir quel préparateur est en charge de la commande, si il a commencé la prise en charge ou non et lorsqu’il a terminé également 
Dans la section Bon de Livraison vous trouvez:

1. **Le nom du préparateur en charge** – indique une fois que le préparateur commence la prise en charge
2. **Le STATUT PREPA** – ce statut vous informe sur l’état de la préparation. En attente signifie que la préparation n’a pas encore été prise en charge, En cours signifie que le préparateur est actuellement en train de préparer la commande, et Prêt signifie que la préparation est terminée et les informations ont bien été ajoutées au bon de Livraison Brouillon 
3. **Le statut du BL** – Il sera en BROUILLON si vous ne l’avez pas encore soumis et le restera jusqu'à ce que le préparateur ait terminé la préparation

**POUR TOUT BON DE LIVRAISON OU LE STATUS PREPA = PRET, LE BON DE LIVRAISON DOIT ETRE SOUMIS ET NON PAS RESTER EN BROUILLON**

* Ouvrir le bon de livraison dont le statut PREPA est prêt, cliquer en haut à droite sur le bouton SOUMETRE, votre bon de livraison n’est maintenant plus en Brouillon. La commande est prête, vous apercevrai dans la section commande client que la Jauge ‘’% prêt" s’est rempli
    * Jauge % prêt (dans la section commande client) - cette jauge vous indique lorsque le bon de livraison a bien été soumis et donc que la commande est prête pour expédition ou enlèvement 

**La prochaine étape est la prise de RDV pour livrer la commande ou prévoir son enlèvement**

## E - CREATION DE SERVICE DE LIVRAISON – PRISE DE RDV POUR LIVRAISON/ENLEVEMENT DE COMMANDE

Ouvrir le bon de livraison pour lequel vous voulez prendre un rdv livraison, dans la section tableau de bords **cliquer sur le signe + a cote de Service de Livraison**

Vous devez préalablement avoir contacter un de nos affréteur pour leur transmettre le nombre de palette et l’adresse de livraison afin qu’ils vous proposent un tarif et une date, que vous confirmerez ensuite avec les clients.

1.	Remplir le champ du type de livraison (Genial, Enlevement, Afreteur, livraison ID par notre chauffeur
2.	Sélectionner n’importe quel véhicule (pas important)
3.	Renseigner la date et l’heure d’enlever
4.	Renseigner la date et l’heure de la livraison chez le client
5.	Renseigner les prix et numéro de confirmation communiquer par nos services de transport (GENIAL/Affréteur), Vous verrez dans le tableau en dessous le bon de livraison concerné.</br>
**Si vous voulez grouper des Bon de Livraison pour effectuer leur livraison groupée**, cliquer en haute à droite sur le bouton ‘’obtenir les clients de" puis bon de livraison et vous pourrez sélectionner les bons de livraison a grouper et livrer ensemble
6. **Enregistrer puis soumettre**, votre service de livraison est maintenant PREVU et vous verrez dans la liste des bon de livraison le carre "RDV Prix" coché pour le ou les BL sélectionné dans votre service de livraison. 
7.	**Une fois la livraison réaliser**, ouvrer le service de livraison correspondant et dans le tableau regroupant les BL cliquez sur la flèche de la dernière colonne et **cocher la case ‘’BIEN LIVREE" puis cliquer sur ‘’mettre a jour" en haut a droite, le statut passera de PREVU a TERMINE**

## F - FACTURATION – CREATION DE FACTURE DE VENTE. 

**ATTENTION, les autorisations comptables sont nécessaires pour procéder à cette étape.**

1.	Ouvrir la commande client en question, dans la section tableau de bords **cliquer sur le signe + a cote de FACTURE DE VENTE**, les champs seront tous pré-remplis, et le tableau d’articles avec leur quantité commandée et les prix sera repris en totalité, ainsi que le total TVA et ECOTAX en dessous

2.	Il vous suffit de cliquer sur **ENREGISTRER** en haut à droite puis **SOUMMETTRE**. Une partie des écritures comptables sont effectuées automatiquement dans le système. L’autre partie des écritures se fera au moment du règlement (écriture de paiement)

**Si la commande a été diviser en différents bons de livraison et que nous voulons facturer uniquement les bon de livraison qui sont prêt et NON PAS TOUTE LA COMMANDE alors :**

1.	Ouvrir le bon de livraison en question, en haut a droite cliquer sur CREER > FACTURE DE VENTE.

2.	Les champs seront tous pré-remplis, et le tableau d’articles avec les prix et les quantités commandées uniquement du bon de commande sélectionnée et non pas de toute la commande, ainsi que la TVA et ECOTAX en dessous

3.	Il vous suffit de cliquer sur **ENREGISTRER** en haut à droite puis **SOUMMETTRE**

## G - REGLEMENT CLIENT – CREATION D’ECRITURE DE PAIEMENT ATTENTION, les autorisations comptables sont nécessaires pour procéder à cette étape.

1.	Ouvrir la facture de vente en question, dans la section tableau de bords **cliquer sur le signe + a cote de ECRITURE DE PAIEMENT**
2.	**Remplir alors les champs nécessaire** (mode de paiement, compte bancaire entreprise) et vérifier que le montant est correct. 
3.	**Enregistrer puis soumettre**, les écritures comptables sont alors automatiquement faite et cette commande est enregistré comme paye dans le system ERP. Faire le virement nécessaire correspondant sur le site de la banque au préalable pour pouvoir renseigner la référence de la transaction bancaire lors de l’écriture de paiement

## H - ESCOMPT - ECRITURE DE JOURNAL MANUEL APRES VERIFICATION PAR SYLVIANE ET RECEPTION DU VIREMENT CLIENT 

* pas d’opération à faire 
