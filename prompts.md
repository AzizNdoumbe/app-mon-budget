Prompt 1 :
Procède à ces modifications purement fonctionnelles :
- Il doit être possible de modifier le montant des charges du jour avant de les valider, au cas où le prélèvement soit différent du mois précédent.
- Faire apparaître les charges validées dès leur validation dans l'historique des dépenses.
- Tous les postes de dépense doivent être réinitialisés au 01 de chaque mois automatiquement.
- Enlève le bouton qui permet de masquer les chiffres, c'est inutile.
- L'évolution des dépenses doit se remettre à jour à chaque mois et bien suivre chaque mois. Ici, la courbe est à 0 sur mai alors qu'il y a déjà eu beaucuop de dépenses. Corrige.
- Placer le reset des charges non plus au 24 de chaque mois, mais à l'ajout du revenu de type Salaire. Toutes les charges doivent donc être décochées, et les prochaines charges à apparaître doivent être celles des jours suivant le jour où le salaire a été ajouté. Cette mise à jour des charges doit donc mettre à jour l'encadré "avant-salaire" qui calcule le reste à vivre hors charges.
- Bien sauvegarder la suppression de postes de dépenses (catégories). La suppression d'une catégorie de dépense doit également disparaître du tableau de bord.
Procède à la modification du design :
Fetch this design file, read its readme, and implement the relevant aspects of the design. https://api.anthropic.com/v1/design/h/ezGSgMa3s1uPX5QHY-05tw?open_file=Tableau+de+bord.html
Implement: Tableau de bord.html