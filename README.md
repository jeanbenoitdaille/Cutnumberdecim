# Cutnumberdecim
Tronquer le nombre de décimales 
Dans cet exercice, nous continuons d'explorer cette fabuleuse fonction format qui cache de nombreuses fonctionnalités assez avancées.

En effet, il est possible d'utiliser la syntaxe suivante pour tronquer le nombre de décimales après la virgule d'un nombre :

{nombre:.3f} 

'nombre' correspond au nom du tag que l'on utilise comme nom de paramètre dans la fonction format.

Nous avons ensuite deux points, un point, un nombre qui détermine le nombre de décimales après la virgule que l'on souhaite conserver (ici 3) et pour finir la lettre f.

Je l'avoue, ce n'est pas la syntaxe la plus facile à retenir, mais c'est vraiment très efficace pour pouvoir rapidement afficher un nombre tronqué dans une chaîne de caractère.

    SOLUTION ALTERNATIVE

Vous pouvez également utiliser la fonction round afin de tronquer le nombre de décimales :

    nombre = 2938.48872
    decimales = 3
     
    solution = round(nombre, decimales)
     
    print("Nombre tronqué: {}".format(solution))

Il vous faudra cependant tout de même utiliser la méthode format afin d'insérer le nombre tronqué à l'intérieur de la chaîne de caractères.
