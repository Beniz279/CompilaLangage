Langage utilisé : Java.
. Pour l'interface , j'ai utilisé Java Swing .
. Analyse Lexicale : Lors la lecture du fichier choisi (fichier.compila) , 
j'ai divisé la ligne en mots en utilisant la methode split() , après j'ai comparé les mots obtenus
avec les mots réservés du langage compila (mot.equals(motreservé)).
. Analyse Syntaxique : j ai verifie toute la ligne (instruction) si elle respectre les règles de notre language compila.

Methodes :
-boolean identif ( String c) : Verifier si une chaine de caractères est un identificateur en verifiant juste la premiere lettre (toCharArray()) (vérifié par Code ASCII).
-boolean contain ( String [] c , String k ) : si un operateur de condition est dans la liste des operateurs declarée {<,>,= ...}
-NumberType (String C): Elle prend en entrée une chaine de caractères (j ai utilisé les resultats du split) et retourne 0 si c etait un entier si nn 2 si c etait un float si nn c mal déclaré.
-Val(String c) : Elle Prend en une chaine de caractères et verifie si c est une valeur numerique (vérifié par le code ASCII ).

 Par : Bendoukha Zineb G2. 
