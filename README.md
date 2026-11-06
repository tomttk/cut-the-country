# Coupe le Pays
Un jeu quotidien dans le navigateur : chaque jour, un pays à couper en deux parts de même surface, d'un seul trait droit.
 
## Principe
 
Le pays du jour apparaît, découpé dans du papier, sur un tapis de découpe. Tu poses un premier point, puis un second de l'autre côté : la ligne est prolongée d'un bord à l'autre et coupe le pays en deux. Le but est de s'approcher le plus possible du 50 / 50.
 
Une seule coupe compte par jour. Le même pays est proposé à tous les joueurs, et un nouveau pays arrive chaque jour à minuit.
 
| Note | Écart avec le 50 / 50 |
|------|----------------------|
| 🎯 Parfait | moins de 0,25 point |
| 🟩 Excellent | moins de 1 point |
| 🟨 Bien joué | moins de 2,5 points |
| 🟧 Pas mal | moins de 5 points |
| 🟥 Raté | 5 points ou plus |
 
## Fonctionnalités
 
- **Pays du jour** : une coupe par jour, résultat à partager sans dévoiler le pays.
- **Entraînement** : des pays au hasard, sans limite.
- **Statistiques** : jours joués, écart moyen, meilleur écart, série en cours.
- **Souris et toucher** : deux clics, ou deux touchers avec ajustement du second point avant de lever le doigt, ou un glissé d'un côté à l'autre. Échap, clic droit ou le bouton « Effacer la ligne » annule.
- **Sons** : son de lame à la coupe et petit air différent selon la note, générés dans le navigateur. Le bouton haut-parleur ou la touche M coupe le son.
- **Accessibilité** : jouable au clavier pour les menus, animations réduites si le système le demande.
## Comment les surfaces sont mesurées
 
Chaque pays est affiché avec une projection azimutale équivalente de Lambert, centrée sur le pays. Cette projection conserve les aires : les proportions affichées correspondent aux vraies surfaces, même pour les grands pays comme la Russie ou le Canada.
 
Les territoires éloignés et de petite taille (îles d'outre-mer, archipels lointains) sont retirés pour garder une forme jouable.
