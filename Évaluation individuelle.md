# Évaluation individuelle

## Programmation - Coaching

```
Nom : Eddiba
Prénom : Naïma
URL de votre compte Github : https://github.com/NaimaK2
```

## Déroulé et fonctionnement. 

L'évaluation est à faire sur [Typora](https://typora.io/). Les réponses sont à écrire dans les blocks de code. 
Pour la partie Ruby, testez votre code sur [repl.it](https://repl.it/) et copiez le dans les blocks de code prévu à cet effet. 
Une fois fini, pushez votre feuille sur Github, dans un nouveau repository que vous appelerez "evaluation-inseec".
L'évaluation est individuelle et durera 1h30. Elle intègre des notions d'HTML, CSS, Ruby et computer science. 

![alt](https://media.giphy.com/media/26xBBfd0ii1khakpy/giphy.gif)

## Quelques mises en garde.

Je connais très bien ce merveilleux site qu'est Wikipédia. Je vous saurais gré de ne pas me remplir certaines questions avec les définitions de Wikipédia. Accessoirement, je sais aussi faire une recherche Google. Si j'ai un doute, je n'hésiterais pas rechercher "Qu'est-ce qu'une API" et comparer les définitions en tête de recherche avec les votre. Si je trouve une similarité trop grande et que je doute de votre bonne foi, je n'hésiterais pas à mettre 0 à la question. 
Pareil pour la copie sur les voisins. Si c'est trop gros et que j'ai un doute trop prononcé... 🔫

![alt](https://media.giphy.com/media/BtedgmzGNCiuk/giphy.gif)



------

### 1. Avec vos mots, expliquez l'interaction client-serveur

```t
Le client et le serveur sont liés par un échange de données, le client va recevoir ces informations de la part du serveur par une requête. Le client est par exemple un PC et le serveur est une réponse à la requête.
```



 ### 2. HTML est un langage côté... 

```
Balisage, il représente la base de la création d'une page web.
```



### 3. Donnez-moi la structure de base d'une feuille HTML

```html
<!DOCTYPE html>
<!-- Completez après cette ligne -->
<html>
  <head>
    <title> Titre </title>
  </head>

  <body>
   Contenu de la page
  </body>
</html>
```



### 4. Changez la couleur du texte "J'adore la programmation" en rose en utilisant du CSS.

```html
<div>
   <p>J'adore la programmation</p>
</div>
```

```css
/* Ecrire le code CSS sous cette ligne */
<head>
  <style>
    h1 { color: pink; }
  </style>
</head>
<body>
  <h1>Titre</h1>
  <p>J'adore la programmation'</p>
</body>

```



### 5. Qu'est-ce que Bootstrap ?

```
C'est une infrastructure de développement, gratuite et open source servant à la création de design pour les sites et applications Web.
```



### 6. Reprenez votre code de la question 3 et ajoutez Bootstrap à votre feuille HTML, au bon endroit.

```html
<!DOCTYPE html>
<html>
  <head>
    <title> Bootstrap </title>
  </head>

  <body>
   Contenu de la page
  </body>
</html>
```



### 7. Mettez ces trois divs sur le même plan horizontal avec trois colonnes de même taille.

```html
<div>
    Google
<div style="float:left;width:10px;">left </div>

<div>
    Microsoft
<div style="float:left;width:10px;">left </div>

<div>
    Apple
<div style="float:left;width:10px;">left </div>
```



### 8. Avec le même code, changez le texte par le logo de la marque en question

```html
<div>
    Google
    h3 { content: url(https://cdn.vox-cdn.com/thumbor/8tLchaDMIEDNzUD3mYQ7v1ZQL84=/0x0:2012x1341/920x613/filters:focal(0x0:2012x1341):format(webp)/cdn.vox-cdn.com/uploads/chorus_image/image/47070706/google2.0.0.jpg); }
<div style="float:left;width:10px;">left </div>

<div>
    Microsoft
    h3 { content: url(https://cdn.vox-cdn.com/thumbor/drG69iSTSbsYDNcckVzB3x97pDA=/7x0:633x417/920x613/filters:focal(7x0:633x417):format(webp)/cdn.vox-cdn.com/assets/1311169/mslogo.jpg); }
<div style="float:left;width:10px;">left </div>

<div>
    Apple
    h3 { content: url(https://image.freepik.com/free-icon/apple-logo_318-40184.jpg); }
<div style="float:left;width:10px;">left </div>
```

 

### 9. Toujours sur le même bout de code, rendez les logos cliquables. Quand on clique sur le logo, on doit arriver sur le site officiel de la marque.

```html
<div>
    Google
</div>

<div>
    Microsoft
</div>

<div>
    Apple
</div>
```

![Mon gars sûr !](https://media.giphy.com/media/l0K4mbH4lKBhAPFU4/giphy.gif)

### 10. Parlons Ruby. Ruby est un langage côté...

```
Orienté objet, c'est un langage de programmation libre et multi-paradigmes.
```



### 11. Listez-moi tous les types de données que vous connaissez.

```
Array, Bouléen, Interpolation, Condition, Chaine de caractères, Integer, Nil, Exposant, Flottant, Algorithme
```



### 12. Assignez à des variables votre prénom, nom et le lien de votre compte Github puis affichez chacune des variables. En 6 lignes.

```ruby
a = first_name
puts a = Naïma
b = last_name
puts b = Eddiba
c = https://github.com/NaimaK2
end
```



### 13. Assignez 674 et 311 à des variables `a` et `b` et stockez le résultat `a` modulo `b` dans une variable `c` et affichez la. 

```ruby

# Le résultat attendu est 52. 
```



### 14. Qu'est-ce qu'une gem ? 

```texte
Une gem définit une variable telle que le nom, la version, la desciption, etc.
```



### 15. Qu'est-ce qu'une API et qu'est-ce qui nous permet de nous y connecter ?

```
C'est une interface de programmation applicative : c'est un ensemble normalisé de classes, de méthodes ou de fonctions qui sert de façade par laquelle un logiciel offre des services à d'autres logiciels.
```



### 14. On va créer un script pour dire bonjour ou bonsoir, en fonction de l'heure de la journée. Votre script doit demander à l'utilisateur de rentrer son prénom. Si `hour` est inférieur à 12, lui dire `Bonjour Anthony` sinon `Bonsoir Anthony` (évidemment, le prénom doit être celui renseigné par l'utilisateur).

```Ruby
# <- Demander le prénom de l'utilisateur
if "hour < 12"
    then "Bonjour Anthony"
if "hour > 12"
    then "Bonsoir Anthony"

hour = 15

# Si hour est inférieur à 12
	# j'écris mon code permettant de dire Bonjour prénom

# sinon
	# j'écris mon code permettant de dire Bonsoir prénom

```



### 15. Itérer sur l'array contenant des noms de twitos un peu famous et follow chacun d'eux grâce à une méthode trouvée dans la [doc de la gem twitter](https://github.com/sferik/twitter). Pas besoin de lancer le code et de faire la partie authentification. Juste le bloc d'itération suffira. 

```ruby
handles = ["@richardbranson", "@jeffweiner", "@LinkedInQueen", "@ericschmidt", "@elonmusk", "@petecashmore", "@SteveForbesCEO", "@mtbarra"]


```



### 16. Félicitations, vous êtes arrivé·e à la fin, pushez cette feuille sur votre Github dans un repo appelé `evaluation-inseec`. N'oubliez pas de remplir le premier block avec votre identité tout en haut ! 

![alt](https://media.giphy.com/media/l0MYJnJQ4EiYLxvQ4/giphy.gif)

