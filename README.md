# Réinitialiser le mot de passe de Mac OS X avec le single user mode

![AppleIcon](http://www.creads.fr/blog/wp-content/uploads/2011/10/500px-apple_computer_logo_rainbow_svg-187x208.png)

Ce truc tordu vous permet de créer un nouvel utilisateur avec lequel vous pourrez modifier le mot de passe des autres utilisateurs, sans le CD d'installation qui peut aussi servir à réinitialiser votre mot de passe.

## Explication

Ce truc effectue une chose, il fait croire à Mac OS X qu'il n'est pas complètement installé, ce qui l'amène à vous demander de créer un nouveau compte utilisateur au démarrage. Vous aurez ensuite accès à ce compte et par la même occasion, à la modification de tous les autres utilisateurs.

   Démarrer votre PC et maintenir les touches Apple et C enfoncées immédiatement après le premier son de démarrage. Lorsque vous arrivez dans la console, vous devrez taper des commandes avec votre clavier
    **en respectant parfaitement les majuscules!**
    
    Taper mount -uw /  et appuyer sur Entrée.
    Taper rm /var/db/.AppleSetupDone et appuyer sur Entrée.
    Taper shutdown -h now et appuyer sur Entrée.
    L'ordinateur s'arrête, vous pouvez ensuite le redémarrer, répondre aux questions, créer votre nouvel utilisateur et accéder aux autres Comptes d'utilisateurs dans les Préférences système pour modifier leur mot de passe.
    
    **Fin**
