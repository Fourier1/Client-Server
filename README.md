/ ** DESCRIPTION DU CONTENU DU FICHIER README ** /

* A quoi sert la lib. 
* Comment l’installer.
* Un exempe concret d’utilisation.
* La licence d’utilisation.
* Un lien vers la doc si elle existe.

Script client server (chat entre plusieurs clients connecter a un meme server)
============================================================================================

ce script est ecrit en python2.7
c'est un systeme de chat client serveur. il suport autant de client que vosu voulez 

----------------------------------------------------------------------------------------------------
    Information a renseigner avant l'utilisation du script
    ============================================================
    
* requirements.txt installer les pacquets

    Instalation du packeges
    =======================
    pip install -r requirements.txt
    python setup.py install
    
    
Exemple d'utilisation : 
    
    # Démarrer le server en premier 
    >>> python chatserver.py
    
    # et en suite les clients (au moin  deux client pour pouvoir communiquer )
    python chatclient.py ip port
    >>>  python chatclient.py 127.0.0.1 8000

    
Ce code est sous la licence WTFPL

GNU GPL: 
   * La liberté d'exécuter le logiciel, pour n'importe quel usage ;
   * La liberté d'étudier le fonctionnement d'un programme et de l'adapter à ses besoins, ce qui passe par l'accès aux codes sources ;
   * La liberté de redistribuer des copies ;
   * L'obligation de faire bénéficier à la communauté des versions modifiées.
    