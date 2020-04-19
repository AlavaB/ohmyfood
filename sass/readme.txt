--Ordre des imports de base--


Utils :
    - Variables
    - Fonctions
    - Mixins
    - Placeholders
Vendors
    - feuilles de style externe (ex: bootstrap...)
Base :
    - Police de caractères
    - Normes (taille des boxs)
Components
    - blocs BEM indépendants (ex: boutons)
Layout
    - blocs BEM (ex: header, article...)
Pages
Thèmes
    - code thématique (ex: code pour noël)

--Exemples--
@import "./utils/variables";
@import "./utils/functions";
@import "./utils/mixins";
@import "./utils/extensions";
@import "./base/base";
@import "./base/typography";
@import "./components/buttons";
@import "./layouts/header";
@import "./layouts/nav";
@import "./layouts/container";
@import "./layouts/form";
@import "./pages/work";
@import "./pages/about";
@import "./pages/project";

--commandes installation sass--
npm init
npm install sass -g (si pas deja fait)

--configuration package.json--
    "scripts": {
      "sass": "sass --watch ./sass/main.scss:./css/style.css"
    },
    
--commande lancement de compilation--
npm run sass