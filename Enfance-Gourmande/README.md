# Enfance gourmande

> 155
> 
> medium
> 
> RaptorJésus
> 
> Quand vous étiez jeune, vous accompagniez régulièrement votre père chercheur durant ses déplacements. Mais un repas dans un hôtel en particulier brûle en vos souvenirs : un peu avant le réveillon, en plein confinement, vous y aviez mangé "l'entrecôte de boeuf cuite au barbecue, accompagnée des légumes du potager du Roi". Mais vous avez beau vous creuser la cervelle, impossible de retrouver le nom du lieu ! Seules quelques images vous reviennent par flash quand vous essayez de vous souvenir. Parviendrez vous à retrouver le nom de l'hôtel de ce restaurant, et le prix du plat ? 
> 
> Format : 404CTF{plaza_athenee-12}
> Fichier fourni : souvenir.mp4



La vidéo est une succession de trois courtes vidéos
- Une photo avec marqué "Relais et Châteaux" dessus
- Un lac ou étang
- Une vue aérienne proche de Paris avec la Tour Eiffel au fond.

Relais et Châteaux est une association qui regroupe plusieurs hotels et restaurants de luxe. Ils ont affiliés "Relais et Châteaux".

En cherchant des "Relais et Châteaux" proches de Paris et d'un étang, on tombe sur les Etangs de Corot.

https://www.etangs-corot.com

Aux alentours, il y a plusieurs restaurants et bistrots, mais aucune mention de "l'entrecôte de boeuf cuite au barbecue, accompagnée des légumes du potager du Roi" sur le site.

Mais l'énoncé mentionne ceci :

> un peu avant le réveillon, en plein confinement, vous y aviez mangé

Il faut donc regarder des menus datant de décembre 2020 ou 2021 environ.

Sur Wayback Machine, il y a bien un page des étangs de corot qui date du 6 décembre 2020.

https://web.archive.org/web/20201206014940/https://www.etangs-corot.com/

Les Etangs de Corot propose une vente à emporter.

https://web.archive.org/web/20201130232859/https://etangs-de-corot.myshopify.com/

Dans ce menu, on retrouve bien la mention de l'entrecôte de boeuf cuite au barbecue.

``Entrecôte de bœuf cuite au barbecue, légumes du potager du Roi (pour 2 personnes) — Prix régulier €60 ```

Flag : ``404CTF{etangs_de_corot-60}``