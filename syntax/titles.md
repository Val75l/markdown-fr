# Titres

Quand on commence a rediger un document en Markdown, on se doit d'ajouter un titre et plusieurs sous-headers.

Le Markdown supporte deux sortes de header, Setext et atx.

Les Headers Setext sont “soulignés” en utilisant des signes égal (Pour le premier niveau de headers) et dashes (pour le second niveau de headers). Par exemple:

```
Ceci est un H1
==============

Ceci est un H2
--------------
```

aucun nombre du soulignage =’s ou -’s veut fonctionner.

Les headers Atx utilisent 1-6 caractères hash au début de la ligne, correspondants aux niveaux des header 1 à 6. par exemple:

```
# Ceci est un H1

## Ceci est un H2

###### Ceci est un H6
```


Accessoirement, vous pouvez “fermer” les headers de type atx. Ceci est purement esthétique — vous pouvez utiliser cela si vous pensez que cela est mieux. La fermeture des hashes, vous ne devez même pas savoir matcher le nombre de hashes utilisés pour ouvrir le header. (Le nombre de hashes ouverts determinent le niveau du header.) :

```
# Ceci est un H1 #

## Ceci est un H2 ##

### Ceci est un H3 ######
```


---

Ici un quiz sur les titres en Markdown.

Sélectionnez les bons headers:
- [x] `# bonjour`
- [ ] `#bonjour`

>Les Headers ont besoin d'un espace entre les caractères de hash et le texte.

Sélectionnez les bons headers headers:
- [ ]  

```
test
########
```
- [x]  

```
test
=======
```

> Seul '=' et '-' sont acceptés pour souligner un header.

---


