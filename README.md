# Malaxar
Simplification of compiling and executing C and python programs

Utilisation :
A la place de taper la longue ligne de commande pour compiler le programme et l'exécuter, utilisez la commande malaxar !
Elle compile le code, l'execute, puis suprimme l'executable à la fin de l'execution. Elle fait automatiquement la différence entre le code python et le code C.

Syntaxe : malaxar [options] nom_prog.c arg_1 ... arg_n (pour le C) / malaxar nom_prog.py (pour le Python)

Options (uniquement pour le code en C): 
- -f : ajoute les option -Ofast et -DNDEBUG lors de la compilation, rend l'executable plus rapide et ignore les assert
- -v : execute le code dans Valgrind

Installation :
1. Tapez cd pour aller dans le répertoire de base
2. ouvrez le ficher .bash_aliases ou créez-le s'il n'existe pas
3. copiez-collez le code dans ce fichier
4. relancez le terminal ou taper source .bashrc
