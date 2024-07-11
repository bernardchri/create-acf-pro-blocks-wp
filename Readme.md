# Script node de création de bloc pour ACF

Bootstrap de création de blocks ACF pour thème FSE wordpress


- clone le projet à la racine de votre thème FSE
- lancer la commande `npm run create monNouveauBlock` , **monNouveauBlock** etant le nom de votre block.
- creation d'un dossier dans le dossier "pattern" de votre thème FSE avec un fichier : _block.json_, _monnouveaublock.js_, _monnouveaublock.php_, _monnouveaublock.css_

```
    git clone **
    cd create-acf-pro-blocks-wp
    rm -rf .git
    npm i
    npm run create monNouveauBlocks
```

- Copier/coller la ligne du terminal `register_block_type(PATH . "/patterns/monNouveauBloc");` dans **functions.php** pour enregister le blocks




