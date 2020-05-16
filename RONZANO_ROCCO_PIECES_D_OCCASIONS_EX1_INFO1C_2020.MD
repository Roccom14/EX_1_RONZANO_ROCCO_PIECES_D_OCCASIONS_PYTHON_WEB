Bonjour Monsieur Maccaud,

Pour l'exercice 1, comme demandé j'ai importé votre DUMP d'ex 1 sur Pycharm et j'ai modifié les 4 actions **CRUD** de la table _genre_ pour l'adapter à ma table genre et j'ai d'abord testé le ```delete_fixe_genres.py``` et je me suis rendu compte que cela ne marchera pas car il faut d'abord que j'ouvre ```insert_genres_one_value.py``` et à ma grande surprise, cela à fonctionné ! _je vous aime_ appaut dans les _genres_ :)

Je lança ensuite ```delete_fixe_genres.py``` et il ne supprima rien :/ je me pencha sur le code et à la ligne _15_, ```numero_ligne_table_delete = 7``` et me je me rendis compte que je n'avais pas de valeur à l'id _7_ du coup je l'ai modifié en _5_ et cela marcha.

Ensuite je lança ```select_all_genres.py``` pour voir et je peux voir les entrées dans ma table ``t_gender``.

Et pour finir je lança ```update_fixe_genre.py``` et tout roula comme sur des roulettes.


_RR de 1148_


P.S : le DUMP de ma BD est dans le dossier __DATABASE__ sous le nom ``ronzano_rocco_pieces_d_occasions_info1c_2020.sql``
