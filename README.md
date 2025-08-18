# docsify-gabarit-cours

Docsify modele de publication via actions

## Activer le déploiement de page

via Github Actions

![page-action](https://i.ibb.co/2gkwH9L/page-action.png)


## submodule

```sh
git submodule sync --recursive && git submodule update --init --remote --recursive
```

## Personalisation

### index.html

#### meta

Est utilisée pour inclure des métadonnées, comme des descriptions ou des informations relatives au contenu de la page, sans les afficher directement aux utilisateurs.

```html

<meta name="description" content="Modèle docsify pour publication avec actions">

```

#### title
Définit le titre de la page qui s'affiche dans l'onglet du navigateur et est utilisé par les moteurs de recherche comme le titre principal dans les résultats de recherche.

```html
<title>Modèle docsify pour publication classique</title>
```




#### window.$docsify 

##### name

Titre de la page affiché dans la barre de coté

```html
name: 'Modèle Docsify Classique',
```

##### repo

Lien vers le repository git du projet à documenter, cliquable depuis l'icone dans la barre de coté

```html
repo: 'https://github.com/gllmAR/docsify-modele-classique',
```


#### CSS (optionnelle)

Source et lien vers style CSS lié  [gllmAR/docsify-simple-style](https://github.com/gllmAR/docsify-simple-style/)



#### Section substitution de navigation 

```
les élément start-replace-subnav et end-replace-subnav  lorsqu'ils sont dans des commentaire HTML sont substitués dans par un des scripts via intégration continue 
```

<!-- start-replace-subnav -->
* [Déroulement](/01-deroulement/)
    * [S1 :](/01-deroulement/01/)
    * [S2 :](/01-deroulement/02/)
    * [S3 : ](/01-deroulement/03/)
    * [S4 : ](/01-deroulement/04/)
    * [S5 :](/01-deroulement/05/)
    * [S6 :](/01-deroulement/06/)
    * [S7 : ](/01-deroulement/07/)
    * [S8 : ](/01-deroulement/08/)
    * [S9 : ](/01-deroulement/09/)
    * [S10 : ](/01-deroulement/10/)
    * [S11 : ](/01-deroulement/11/)
    * [S12 : ](/01-deroulement/12/)
    * [S13 : ](/01-deroulement/13/)
    * [S14 :](/01-deroulement/14/)
    * [S15 :](/01-deroulement/15/)
* [Activités ](/02-activites/)
    * [TP1 ](/02-activites/01/)
    * [TP2](/02-activites/02/)
    * [TP3 ](/02-activites/03/)
    * [Projet intégrateur](/02-activites/04/)
* [Savoirs](/03-savoirs/)
    * [Savoirs 1](/03-savoirs/01/)
    * [Savoirs 2](/03-savoirs/02/)
    * [Savoirs 3](/03-savoirs/03/)
    * [Intégrations des savoirs](/03-savoirs/04/)
* [Évaluations](/04-evaluations/)
    * [Évaluations formatives](/04-evaluations/formatives/)
        * [EVF TP 1 ](/04-evaluations/formatives/01/)
        * [EVF TP 2 ](/04-evaluations/formatives/02/)
        * [EVF TP 3 ](/04-evaluations/formatives/03/)
        * [EVF - Intégration des apprentissages](/04-evaluations/formatives/04/)
    * [Évaluations sommatives](/04-evaluations/sommatives/)
        * [EVS TP1 : Scène réactive](/04-evaluations/sommatives/01/)
            * [Grille d'évaluation TP1](/04-evaluations/sommatives/01/grille-evaluation/)
        * [EVS TP2 : Personnage et environnement](/04-evaluations/sommatives/02/)
        * [EVS TP3: Niveaux, progression, menu ](/04-evaluations/sommatives/03/)
        * [EVS-4 projet: Intégration des apprentissages](/04-evaluations/sommatives/04/)
* [Médiagraphie](/05-mediagraphie/)
* [PIEA](/06-piea/)
<!-- end-replace-subnav -->
<!-- end-replace-subnav -->