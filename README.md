# ShaLauncherJson
Un outil pour faire un launcher minecraft à partir d'un fichier json (c'est cool n'est ce pas ?) :)
Je suis acutellement en train de le faire et c'est assez compliqué à cause de mon niveau assez bas en Java il peut contenir beaucoup de bugs et d'imperfections. Néanmoins j'ai fait de mon mieux pour que ça fonctionne assez bien.

### Comment s'en servir ?
Je sais que certains d'entre vous ne savent pas utiliser de fichier json, donc je vais peut être faire une interface graphique ou il faudra drag and drop les éléments etc.. Mais ce sera long a faire. En attendant, je vais vous donner un fichier json "vierge" qui contiendra le squellette de votre launcher.

Description de chaque éléments :

Partie principale :

- Title (String) : Définit le titre du launcher
- Resizable (Boolean) : Définit si le launcher peut être agrandi / rétréci (pas encore dispo)
- Undecorated (Boolean) : Retire si oui ou non les bords de Windows sur le launcher
- Width (String) : Définit la largeur du launcher
- Height (String) : Définit la longueur du launcher
- Movable (Boolean) : Définit si le launcher peut être bougé
- FaviconFileName (String) : Nom du fichier de l'icone du launcher
- BackgroundFileName (String) : Nom du fichier du background du launcher (les vidéos ne sont pas encore supportées)
- CssFile (String) : Nom du fichier css pour appliquer du css sur les éléments du launcher

LaunchSettings :

- GameVersion (String) : Définit sur quelle version le jeu va être lancé (pas tout est ajouté pour l'instant)
- GameDirectory (String) : Nom du dossier du jeu (a mettre sans le .)
- UseForge (Boolean) : Définit si vous allez utiliser forge pour lancer le jeu
- AutoConnect (String) : Ip et port du serveur pour que sa se connecte lors du lancement du jeu terminé
- JVMArgs (String List) : Définit des arguments JVM par défaut pour les utilisateurs

AuthSettings : 
 
- UsernameField (String) : Nom du TextField qui sert pour le pseudo / l'email
- SaveEmailField (Boolean) : Définit si l'email / pseudo va être sauvegardé dans un fichier
- SavePasswordField (Boolean) : Définit si le mot de passe va être sauvegardé dans un fichier (chiffré évidemment).
- SaverFileName (String) : Nom du fichier ou l'email et le mot de passe seront sauvegardés
- Type (String) : Définit si l'authentification est crack ou premium

UpdateSettings :

- UpdateType (String) : Définit le type d'update (supdate par défaut et il y a que celui la de dispo pour l'instant)
- Link (String) : Lien du serveur supdate
- DisplayPercentage (String) : Nom de la progressbar (ProgressBar1) ou nom du TextField pour afficher le pourcentage

Fonts :

- 1 : Nom de la police

Buttons :

//a faire
