# TikamoonCSS

## CSS
 - Fichier normal : [export.css](https://github.com/pierredelattre/tikamooncss/blob/main/export.css)
 - Minifié : | 

## Installation
 - Installer NodeJS : [Lien externe](https://nodejs.org/en/download/current)
 - Cloner le repo Github
  
## Utilisation
Pour lancer l'exportation du SASS :
 - Ouvrir un terminal (Vscode : Terminal -> New)
 - Entrer la commande ```npm run sass```
  
## Structure
```
├── sass
│   ├── abstracts /
│   ├── components /
│   ├── layout /
│   ├── pages /
│   ├── utilities /
│   ├── _base.scss
├── export.css
```

**Abstracts** : Fichiers variables, fonctions etc.  
**Components** : Composants  
**Layout** : Groupes d'éléments (bannière, card...)  
**Pages** : Propre à des pages / types (boutique, matière...)  
**Utilities** : Fichiers pour la mise en page (grids, spacings, borders...)  
**_base.scss** : Fichier primaire global où sont importés tous les fichiers secondaires (ci-dessus)  
**export.css** : Fichier d'export

## Responsive
```
@media screen and (max-width: 767px) {
  /* Classe : .sm:order-0 */
}

@media screen and (min-width: 768px) and (max-width: 1023px) {
  /* Classe : .md:order-0 */
}

@media screen and (min-width: 1024px) {
  /* Classe : .lg:order-0 */
}

@media screen and (min-width: 1440px) {
  /* Classe : .xl:order-0 */
}
```