1) Dans le HTMl
// Ins�rer la classe divAnim dans les conteneurs qui doivent effectuer la transition sur son contenu
// Ins�rer la classe avecContainer pour que le contenu apparaisse une fois tout le contenant visible � l'�cran
// Si avecContainer n'est pas pr�sent, le contenu appara�t d�s que le contenant commence � appara�tre � l'�cran
// .elemTrans est la classe � mettre dans les �l�ments pr�sents dans divAnim afin qu'elle apparaissent en fondu

2) Dans le CSS main
// Ins�rer le code ci-dessous
.elemTrans{
    opacity: 0;
    transform: opacity 300ms;
}

3) Dans le dossier CSS
//Ajouter anim.less (� compiler en CSS si besoin)

4) Dans le dossier js
//Ajouter main.js (� renomer si besoin)

PS : Ne pas oublier les  <link> et les <script> dans le HTML !

