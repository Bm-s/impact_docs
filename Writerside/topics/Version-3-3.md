# Version 3.3.0

## Chantier - Statut archivé
Afin de renforcer la sécurité, nous avons ajouté un verrou sur les chantiers avec un statut "archivé" (Voir paramètres du logiciel / État des chantiers)
![state_old.png](state_old.png)

Il ne sera dès lors plus possible de modifier un chantier verrouillé et seul un compte de type administrateur du logiciel pourra ouvrir à nouveau un chantier.


## Arrondi en indiquant un prix TTC
Afin de faciliter la définition du prix final, il est désormais possible d'inscrire le montant final TTC
auquel vous voulez arriver et le système se chargera de calculer le rabais nécessaire.
Si le montant auquel vous désirez arriver n'est mathématiquement pas atteignable, une différence d'arrondi sera
ajoutée dans le but d'atteindre le montant désiré.
Pour ce faire, cliquez sur le bouton entouré en rouge :
![set_ttc.png](set_ttc.png)


## Rabais fixe par client
Il est désormais possible d'inscrire un rabais par défaut pour un client. Celui-ci sera repris automatiquement
lors de la création d'un chantier et des devis/factures liées. Attention à toujours bien vérifier l'onglet
"synthèse du prix" afin d'éviter les erreurs.
![fix_rabais.png](fix_rabais.png)


## Listing des factures
Lors du chargement du listing des factures, seul les factures ayant moins de 45 jours sont affichées à l'exception des factures impayées
qui elles seront toujours affichées


## Suppression du catalogue web
Le catalogue "web" qui contenant jusqu'ici uniquement des références pour les sanitaires a été provisoirement
désactivé.


## Filtres sur les chantiers
Le filtre sur les chantiers est désormais stocké durant la navigation afin que la dernière vue que
vous aviez chargée soit correctement reprise lors du retour sur le listing. Nous avons également modifié le visuel
pour une meilleure compréhension.
![filter_chantier.png](filter_chantier.png)


## Améliorations du calendrier
- Réduction des temps de chargement du calendrier
- Reprise de la vue semaine par défaut sur les smartphones

## Améliorations des exports
Désormais, il est possible d'exporter les listings au format excel pour les modules suivants :
- Contacts
- Frais
- Articles
- Chantiers

## Corrections de bugs
- Facturation des heures depuis un chantier fonctionne à nouveau correctement
- Les chantiers supprimés ne sont plus présents dans certains exports
- Reprise de la mise en forme des conditions générales sur les conditions générales par défaut à la création d'un D/M/F
- Rajout du solde débiteur sur l'onglet synthèse des prix (Ipad + Ordi)
- Les utilisateurs supprimés ne sont plus présents dans certains menus de sélection
- Les utilisateurs supprimés ne sont plus présents dans le calendrier
- Amélioration de la duplication d'offre, facture ou métré.