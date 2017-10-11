# tp-frontpage


## Menu de navigation

`
<aside id="header">
  <nav>
    <img src="img/logo.png" alt="Logo musique">
    <ul>
      <li>Accueil</li>
      <li>Recherche</li>
      <li>Mes favoris</li>
      <li>Mes playlists</li>
    </ul>
  </nav>
</aside>
` 

Pour ajouter une entrée, vous pouvez insérer un nouvel élément <li>Mon sous-menu</li> à l'intérieur du <ul></ul>

-------------------------------

## Page artiste

`
<section id="main" class="conteneur">
`

Cette section représente le contenu de la page affichée à l'écran.
L'application est actuellement en mesure de fournir des informations sur un artiste :

* Nom de l'artiste
	* ` <div class="entete-artiste">
          <h2 class="nom-artiste">RIDSA</h2>
          <h4 class="followers-artiste">86,191 followers</h4>
        </div> `
* Nombre de followers (popularité)
	* ` <div class="entete-artiste">
          <h2 class="nom-artiste">RIDSA</h2>
          <h4 class="followers-artiste">86,191 followers</h4>
        </div> `
* Une barre d'actions : "PLAY" / "FOLLOW" / "Menu contextuel (pour plus d'actions)"
	* ` <div class="actions">
          <button class="btn btn-principal">PLAY</button>
          <button class="btn btn-secondaire">FOLLOW</button>
          <button class="btn btn-transparent">&middot; &middot; &middot;</button>
        </div> `
* Une description/biographie de l'artiste
	* ` <div class="description-artiste"> ... </div> `
* La liste des différents albums (avec ses titres)
	* ` <div class="album-artiste">
          <div class="pochette-album">
            <img src="img/RIDSA_pochette-album.jpg" alt="RIDSA - Mes histoires">
          </div>
          <ul class="titres-album">
            <li>
              <span class="numero-titre">1.</span>
              <span class="titre-titre">Oh mama</span>
              <span class="duree-titre">3:21</span>
            </li> 
          </ul>
      	</div>`

Il suffit d'éditer les valeurs 