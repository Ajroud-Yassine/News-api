# App-Android-News-API

Wireframe page principale (Tout les articles):

![Wireframe_ _Maquette_App-News-API](https://user-images.githubusercontent.com/80514203/140019206-1ae7e648-6db8-4683-89b5-5d16eec8ca0a.png)

Wireframe page d'un article:

![Wireframe1_ _Maquette_App-News-API](https://user-images.githubusercontent.com/80514203/140019399-3d45ef7c-7a80-4957-8af7-ba2255bfda0a.png)

# Tecnologigie choisie -> Android Studio avec Kotlin 
    -Rapide pour développer une application native avec une architecture MVC.
    -Code simple avec kotlin 
    -Création d'un binding pour optimiser le code (appel du R.findById() trop de fois)
    -RecyclerView est une liste dynamique pour afficher les cards
    -API => news.org

# Temps : environ 8 heures

    Création du binding -> 10 min
    Création du recycler View et de la carte -> 2h
    Ajout de l'Api News -> environt 6h (ne fonctionne pas)

# Ce que je n'ai pas réussi à faire:

    -J'ai un problème lors de l'appel de l'api , je reçois erreur 403  dans le log lors de l'appel (GET), j'ai testé avec une autre api (Api pokémon) et je recois bien les données, je n'est toujour pas trouvé le problème pour API news.

    -Pour ouvrir un article je ferais un onClickListener qui pointe sur une fonction pour charger l'activité (Page XML d'un article) et afficher l'article en fonction de sont identifiant (id).

