```javascript
//REVISIONS
// Declarez une variable nommée "boucler" contenant true
var boucler = true;
// Declarez un tableau members contenant Aida67, lapie002, anneserrano, Jennysmille, nunkabuk, RCosson, kaonb-ax, FerEmilie, crazychouwi, KiluaZoldyc, patatobeur, Sam11360, elo062, hermeline, Biciclet,
var members = ["Aida67", "lapie002", "anneserrano", "Jennysmille", "nunkabuk", "RCosson", "kaonb-ax", "FerEmilie", "crazychouwi", "KiluaZoldyc", "patatobeur", "Sam11360", "elo062", "hermeline", "Biciclet"]

// SI la variable boucler vaut true ALORS

  // Bouclez sur le tableau que vous avez déclaré ci-dessus
  var check = document.getElementById("check");
 check.addEventListener("click", function(){
  if(boucler === true){
    var members_length = members.length;
    for(var i = 0; i < members_length; i++){
  switch (members[i]) {
    case "FerEmilie":
    var nd = document.createElement("div");
    var p = document.getElementById("check");
    nd.innerHTML = "Affiche " + members[i];
    p.appendChild(nd);

      console.log("Affiche " + "FerEmilie");
      break;
    default:
    var nd = document.createElement("div");
    var p = document.getElementById("check");
    nd.innerHTML = members[i];
    p.appendChild(nd);
    console.log(members[i]);
    break;
  }
}} });
  // Mettre un switch pour qu'au moment où la boucle se trouve sur votre pseudo cela ajoute "Affiche " devant votre pseudo dans la console et sur l'écran et par defaut seulement le pseudo des autres



// FIN REVISIONS

// COURS AJAX
  // AJAX Jquery .ajax() ou .get()
  // Faites une requete vers l'API REST de Github pour récupérer les informations de votre compte


// FIN COURS AJAX
```
