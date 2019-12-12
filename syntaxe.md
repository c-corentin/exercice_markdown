# Inventaire syntaxe Markdown

* [Définition MarkDown](/memo.md)
* [READ ME](/README.md)

# Sommaire

* [Titres](#Titres)
* [Emphase](#Emphase)
* [Listes](#Listes)
* [Images](#Images)
* [Citations](#Citations)
* [Inline](#Inline)
* [Mettre de la syntaxe en évidence](#Mettre-de-la-syntaxe-en-évidence)
* [Listes de tâches](#Listes-de-tâches)
* [Tableaux](#Tableaux)
* [Liens](#Liens)

## Titres

```
# Ceci est une balise <h1>
## Ceci est une balise <h2>
###### Ceci est une balise <h6>
```

Ce qui donne 

# Ceci est une balise <h1>
## Ceci est une balise <h2>
###### Ceci est une balise <h6>

## Emphase

```
*Ce texte sera en italique*

_Ce sera également en italique_

**Ce texte sera en gras**

__Ce sera également en gras__

_Vous **pouvez** les combiner_
```

Ce qui donne 

*Ce texte sera en italique*

_Ce sera également en italique_

**Ce texte sera en gras**

__Ce sera également en gras__

_Vous **pouvez** les combiner_

## Listes

### À puces
```
* Item 1
* Item 2
  * Item 2a
  * Item 2b
```

Ce qui donne 

* Item 1
* Item 2
  * Item 2a
  * Item 2b

### Ordonnées

```
1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b
```

Ce qui donne 

1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b

## Images

```
![GitHub Logo](/images/logo.png)
Format: ![Alt Text](url)
``` 


## Citations

```
Comme l'a dit Kanye West:

> Nous vivons l'avenir donc
> le présent est notre passé.
```

Ce qui donne 

Comme l'a dit Kanye West:

> Nous vivons l'avenir donc
> le présent est notre passé.

## Inline

```
I think you should use an
`<addr>` element here instead.
```

Ce qui donne 

Je pense que vous devriez utiliser un
l'élément `<addr>` ici à la place.

## Mettre de la syntaxe en évidence

```
    ```javascript
    function fancyAlert(arg) {
     if(arg) {
     $.facebox({div:'#foo'})
     }
    }
    ```
```

Ce qui donne 

```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
```

## Listes de tâches

```
- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item
```

Ce qui donne 

- [x] @mentions, #refs, [links] (), **formatage** et <del> tags </del> pris en charge
- [x] Syntaxe de liste [x] requise (toute liste non ordonnée ou ordonnée prise en charge)
- [x] c'est un élément complet
- [ ] ceci est un élément incomplet

## Tableaux

```
Premier en-tête | Deuxième en-tête
------------ | -------------
Contenu de la cellule 1 | Contenu de la cellule 2
Contenu dans la première colonne | Contenu dans la deuxième colonne
```

Ce qui donne 

Premier en-tête | Deuxième en-tête
------------ | -------------
Contenu de la cellule 1 | Contenu de la cellule 2
Contenu dans la première colonne | Contenu dans la deuxième colonne


## Liens

```
https://github.com/c-corentin/exercice_markdown
```

Ce qui donne 

https://github.com/c-corentin/exercice_markdown
