# html-p3
<!DOCTYPE html>
<html>

<head>
    <meta charset="utf-8" />

    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css" integrity="sha512-1ycn6IcaQQ40/MKBW2W4Rhis/DbILU74C1vSrLJxCq57o941Ym01SwNsOMqvEBFlcgUa6xLiPY/NS5R+E6ztJQ==" crossorigin="anonymous" referrerpolicy="no-referrer"
    />
    <link href="http://fonts.cdnfonts.com/css/days" rel="stylesheet">

    <title>Freedom Family</title>

</head>


<body>
    <header>
        <div class="btnMenuLeft">
            <h1 class="itemMenu textMenu">Freedom Family</h1>
            <div class="btnAnnonce itemMenu">
                <p class="annonceBtnMenu"><i class="far fa-plus-square"></i> Ajouter une annonce</p>
            </div>
            <div class="btnRecherche itemMenu">
                <p class="rechercheBtnMenu">Recherche</p>
            </div>
        </div>
        <div class="btnMenuCenter"></div>
        <div class="btnMenuRight">
            <div class="btnFavoris">
                <i class="fas fa-heart"></i>
            </div>
            <div class="btnCategories itemMenu">
                <i class="fas fa-clipboard-list"></i>
            </div>
            <div class="btnProfil itemMenu">
                <i class="fas fa-address-book"></i>
            </div>
        </div>
    </header>

    <div class="cadretour">
        <br>
        <h1 class="annonce">Déposer une annonce</h1>
        <br>
        <br>
        <div class="titre">Titre de l'annonce :</div>
        <div class="prix">Prix :</div>
        <br>
        <input type="annonce" class="titreann" style="position:relative; bottom:30px;" placeholder="Nom de votre annonce">
        <input type="annonce" class="prixann" placeholder="Prix">
        <div class="adresse">Adresse</div>
        <input type="annonce" class="adresseann" placeholder="Ville - Rue">
        <input type="annonce" class="adresseann" placeholder="Code postal">

        <h3 class="description">Description</h3>
        <form>
            <textarea name="textarea" rows=4 cols=50 class="text_area"></textarea>
        </form>
        <br>
        <button class="bouton">Envoyer</button>
    </div>




</body>


</html>
