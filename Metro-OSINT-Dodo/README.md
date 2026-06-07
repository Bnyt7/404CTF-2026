# Metro OSINT Dodo
> 100
> medium
> 
> Écrit par Clarisse
> 
> Il y a quelques mois, en fin de matinée, j’ai mis plus d’une demie heure à faire un trajet direct qui normalement prend 11 à 12 minutes. Tout ça à cause d’un malaise voyageur à Châtelet. Mon trajet était entre deux stations comportant des noms de scientifiques.
> 
> Quelles étaient ces deux stations ?
> 
> Format du flag : 404CTF{les-halles_republique}

Trajet direct implque que les deux stations sont sur une même ligne.
J'ai essayé de regarder https://ratpstatus.fr/ pour voir les malaises voyageurs, mais il n'y a pas assez de précision sur la date.

On peut supposer que si le trajet de métro a pris autant de temps, alors Châtelet dans la même ligne que les deux stations.

On regarde alors le plan du métro de la RATP à Paris https://www.ratp.fr/plan-metro. Châtelet est desservi par les lignes de métro 1, 4, 7, 11 et 14.

On liste également toutes les stations qui contiennent des noms de scientifiques.

- Metro 1 : x
- Metro 4 : 
    - Réaumur Sébastopol : René-Antoine Ferchault de Réaumur, physicien et naturaliste
    - Raspail : François-Vincent Raspail, chimiste
    - Montparnasse - Bienvenüe : Fulgence Bienvenüe, ingénieur
- Metro 7 : 
    - Pont Marie : Christophe Marie, ingénieur et entrepreneur
    - Jussieu : Antoine-Laurent de Jussieu, botaniste
    - Place Monge : Gaspard Monge, mathématicien
    - Censier-Dauberton : Louis Jean-Marie Daubenton, naturaliste
    - Pierre et Marie Curie
    - Cadet (?) : Jacques et Jean Cadet, qui étaient maîtres jardiniers 
    - Riquet : Pierre Paul Riquet, ingénieur
- Metro 14 : x

Si on suppose que les deux stations sont séparées par Châtelet, alors il n'y a que deux stations qui prennent 10 à 12 minutes(estimation sur Google maps) : Réaumur Sébastopol et Montparnasse - Bienvenüe.

Flag: `404CTF{reaumur-sebastopol_montparnasse-bienvenue}`

