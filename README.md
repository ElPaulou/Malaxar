# Malaxar
Simplification of compiling and executing C and python programs

Utilisation :
A la place de taper la longue ligne de commande pour compiler le programme et l'exécuter, utilisez la commande malaxar !
Elle compile le code et l'execute. Elle fait automatiquement la différence entre le code python et le code C.

Syntaxe : malaxar [options] nom_prog.c arg_1 ... arg_n (pour le C) / malaxar nom_prog.py (pour le Python)

Options (uniquement pour le code en C): 
- -f : ajoute les option -Ofast et -DNDEBUG lors de la compilation, rend l'executable plus rapide et ignore les assert
- -o : ajoute l'option -O0 lors de la compilation, ne modifie pas le code lors de la compilation
- -v : execute le code dans Valgrind
- -h : liste des options

Installation :
1. Tapez cd pour aller dans le répertoire de base
2. ouvrez le ficher .bash_aliases ou créez-le s'il n'existe pas
3. copiez-collez le code dans ce fichier
4. relancez le terminal ou tapez source .bashrc

(Sinon, un petit git clone et l'ajout de ". ~/chemain/vers/fichier dans le bashrc marche très bien)

Et parce que je suis super sympa, une petite fonction pour ouvrir facilement les TP/DM d'info, la fonction go (me remerciez pas, ça me fait plaisir)