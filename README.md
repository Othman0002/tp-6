# tp-6
js et html 
code html
<!DOCTYPE html>
<html lang="fr">
<head>
 <meta charset="UTF-8">
 <meta name="viewport" content="width=device-width, initial-scale=2.0">
 <title> la Manipulation du dm</title>
</head>
<body>
 <div id="Div"></div>
 <script src="Js6.js"></script>
</body>
</html>
code js
const Div = document.getElementById('Div');
const Paragraphe = document.createElement('p');
Paragraphe.textContent = "Ceci est un paragraphe";
Div.appendChild(Paragraphe);
monParagraphe.textContent = "Le texte a été modifié";
Paragraphe.style.backgroundColor = "grenn";
Paragraphe.style.textAlign = "center";
Div.addEventListener('click', function() {
 Paragraphe.textContent = "Un clic a été détecté";
}); 
