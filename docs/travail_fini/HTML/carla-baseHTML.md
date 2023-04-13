<!DOCTYPE>
<html>
    <head>
        <meta charset="utf-8">
        <title>Base HTML5</title>
        <style>
        h1 {
            color: pink;
        }
        h2 {
            color: rgb(0,232,15)
        }
        p {
            color: blue;
        }
        ul {
            color: blue;
        }
        ol {
            color: blue;
        }
        body {
            background-color: rgb(255,255,204)
        }
        #test {
            color: black;
        }
        .test2 {
            background-color: purple
        }
        </style>
    </head>
    <body>
        <h1 class="test2">Les Bases</h1>
        <p>-une page web debute toujours par "DOCTYPE"<br>-ensuite, la premiere balise de la page est HTML<br>-une balise, c'est un truc qui commence par un crochet et qui finit par un crochet<br>-a la fin de la balise, il faut ajouter un slash dans les crochets<br>-la balise "title" est ce que le navigateur utilise pour connaitre le titre de l'onglet<br>-pour ajouter un titre, on met la balise h1<br>-on a 6 balises differentes, qui sont de plus imporants à moins importants<br>-pour faire un paragraphe, j'utilise la balise "p"<br>-pour passer une ligne, j'utilise la balise "br"</p>
        <h1>mise en évidence du texte</h1>
        <h2>mettre un texte en italique</h2>
        <p>j'utilise la balise <em>"em"</em></p>
        <h2>mettre un texte en gras</h2>
        <p>j'utilise la balise <strong>"stronge"</strong></p>
        <h2>souligner le texte</h2>
        <p>j'utilise la balise <u>"u"</u></p>
        <h1>les liste</h1>
        <h2>une liste</h2>
        <ul>
            <li>on utilise 2 balises</li>
            <li>la premiere c'est "ul"</li>
            <li>la deuxieme c'est "li"</li>
        </ul>
        <h2>une liste ordonée</h2>
        <ol>
            <li>on utilise encore 2 balises</li>
            <li>la premiere c'est "ol"</li>
            <li>la deuxieme c'est "li"</li>
        </ol>
        <h1>les images</h1>
        <p>pour ajouter une image, on utilise la labalise "img" suivi de "src="liens de la video"". De plus, on ajoute "alt="un texte qui decrit l'image". Et enfin, on peut changer la taille de l'image, en ajoutant "width="200"" pour la longueur et "heigt="150"".</p>
        <img src="https://cdn.kastatic.org/third_party/javascript-khansrc/live-editor/build/images/food/sushi.png" alt="sushi" width="200" heigt="150">
        <h1 class="test2">le CSS</h1>
        <h2>couleur</h2
        <p>On utilise la balise "style" en dessous de la balise "title"<br>Ensuite, on met le truc qu'on veut modifier, ici on a pris h1 et h2. Puis, on ajoute une alcolade et à l'interieur on met "color: "pink".<br> Pour pouvoir mettre des tons de couleurs differents, je peux metrre "rgb(0,232,15)" après le mot "color:"</p>
        <h2>la couleur de fond</h2>
        <p>C'est exactement pareil, on change juste "color" par "background-color"</p>
        <h2>selectioner par identifiant</h2>
        <p id="test">On va sur la balise qu'on veut prendre, moi je vais prendre celle-ci. Et on ajoute "id="mot"" dans la premiere balise.<br>Ensuite, on revient au style et on met d'abord un diese "#" et apres on met le mot qu'on a mit pour l'id.<br><strong>chaque ID est unique</strong></p>
        <h2>selection par classe</h2>
        <p>A la place de "id" j'ai juste à utiliser "class"<br>Mais, je remplace le diese avec un point "."</p>
    </body>
</html>