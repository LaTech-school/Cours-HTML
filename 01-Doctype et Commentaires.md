# Doctype et Commentaires

Bien que HTML ne soit pas un langage de programmation, il possède deux instructions.

Les instructions sont reconnaissable par leur syntaxe.  
e.g. : `<! ... >`

## L'instruction Doctype

Le Doctype doit être la première instruction du document HTML.

Il permet de préciser la version HTML au client qui interprète le document.

Le doctype HTML5 est :

```html
<!DOCTYPE html>
```

## L'instruction de Commentaire

Le commentaire permet d'apporter une précision sur le code qui est écrit.  
Il peut être écrit n'importe ou dans le document.

Le commentaire ne sera pas interprété par le navigateur.

Un commentaire simple :

```html
<!-- Ceci est un commentaire -->
```

Un commentaire multiligne :

```html
<!-- 
    Ceci 
    est 
    un 
    commentaire 
-->
```

Lors de la phase de développement, il est courant de mettre du code en commentaire.
