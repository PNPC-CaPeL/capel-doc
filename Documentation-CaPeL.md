# Gestion du site public
Les contenus du site publics https://capel.portcros-parcnational.fr/ sont gérés dans un CMS du nom de Ghost.  
Certains contenus spécifiques sont extraits de l’application (LoCoKit) plutôt que du CMS.  
Les contenus sont ensuite transformés en site statique pour disposer de pages légères, rapides et d’un très haut niveau de sécurité.

Le CMS Ghost est accessible sur https://capel.portcros-parcnational.fr/ghost/.

----

![CaPeL_haut](uploads/4780a16bbe612345ca09af30ecca7a43/CaPeL_haut.png)

Les liens vers les pages proviennent du réglage [`Settings > Navigation > Primary
navigation`](https://capel.portcros-parcnational.fr/ghost/#/settings/navigation)

![navigation](uploads/navigation.gif)

----

![capel_links_to_lck](uploads/f9317e0f766dadb8df056e0566034edd/capel_links_to_lck.png)

Ces deux boutons donnent accès à l’application.

----

![capel_texte_header](uploads/7f613b3b7daada040470fcef9edfa49d/capel_texte_header.png)

Ce texte est celui du premier paragraphe de [{Pages}](https://capel.portcros-parcnational.fr/ghost/#/pages) > [Page d'accueil](https://capel.portcros-parcnational.fr/ghost/#/editor/page/60c236698582a800018424e2)

----

![capel_compteurs](uploads/fe3b3008b365b85a5826475f240036a3/capel_compteurs.png)

Ce bloc remonte automatiquement les informations de l’application dans le site à l’aide du bloc Statistiques (tag `custom-stats`) de [{Pages}](https://capel.portcros-parcnational.fr/ghost/#/pages) > (Page d'accueil).

----

![capel_map](uploads/c6984131282c44d779b5fc2631882a01/capel_map.png)

La carte et la légende sont paramétrées dans l’application :
[Interface d’administration de l’application](https://backoffice.capel.portcros-parcnational.fr/workspace/8dbf6e3c-3dc0-464e-9887-d2010fa8d689/database/10ce931c-4e48-40a2-b8f9-c1caba7d07c3) > Paramètres du site public : variables `MAP_CENTER`, `MAP_ZOOM`, `MAP_BASEMAP`, `MAP_STYLES` et `MAP_LEGENDS`.

----

![capel_pages](uploads/408bba35a207c0fc48c38c89b3a38a18/capel_pages.png)

Ce bloc remonte automatiquement les informations des pages l’aide du bloc Vignettes de pages (tag `custom-blocks`) de [{Pages}](https://capel.portcros-parcnational.fr/ghost/#/pages) > (Page d'accueil).
Apparaissent ici :
- l’image fournie dans « Settings » de [{Pages}](https://capel.portcros-parcnational.fr/ghost/#/pages)
- le champ « Excerpt » (dans « Settings ») de [{Pages}](https://capel.portcros-parcnational.fr/ghost/#/pages)


----

![capel_sn](uploads/dfeeb4989d1977363777655d745742c8/capel_sn.png)
Les réseaux sociaux sont réglés dans l’application :
[Interface d’administration de l’application](https://backoffice.capel.portcros-parcnational.fr/workspace/8dbf6e3c-3dc0-464e-9887-d2010fa8d689/database/10ce931c-4e48-40a2-b8f9-c1caba7d07c3) > Paramètres du site public : variables `LINK_FACEBOOK`, `LINK_TWITTER`, `LINK_INSTAGRAM`, `LINK_YOUTUBE`, `LINK_PINTEREST`.


----

![capel_footer](uploads/f9769169f92a35612b9364a4c937776f/capel_footer.png)

Cette partie est gérée dans [{Pages}](https://capel.portcros-parcnational.fr/ghost/#/pages) > [Pied de page](https://capel.portcros-parcnational.fr/ghost/#/editor/page/60b77ea1f6c8f8000199d4a8)

----

# Application

Se connecter en tant que structure de plongée.

### Page « Signer les règlements »

Après connexion, l’utilisateur est amené sur la page « Signer les règlements ».
> [Note JPO : J’aimerais donner une URL, mais je ne vois pas de permalien que l’on puisse mettre dans la documentation]

![home_SP](uploads/07f927e708705ac1dd437936efb4839e/home_SP.png)

Il ne peut pas signer de règlement tant qu’il n’a pas complété sa fiche d’information et au moins un bateau.  
> [Note JPO : rien ne l’indique à l’écran]

Pour compléter la fiche d’information et déclarer un bateau, cliquer sur « Mes informations » :

![bouton-Mes_informations](uploads/1fd6e4ef79cc9713a08f0c9be884659b/bouton-Mes_informations.png)

L'utilisation est amené à la page « Mes informations »
> [Note JPO : J’aimerais donner une URL, mais je ne vois pas de permalien que l’on puisse mettre dans la documentation]

### Page « Mes informations »
> [Note JPO : J’aimerais donner une URL, mais je ne vois pas de permalien que l’on puisse mettre dans la documentation]

La page présente un formulaire à compléter :

![Mes_information_à_compléter](uploads/2fe2fc37daf9ccec1fdeeb1a8a31d87d/Mes_information_à_compléter.png)

Remplir les informations :

![Mes_information_haut_rempli](uploads/26df3a2394fcdc3973b2eb46efba8b17/Mes_information_haut_rempli.png)

Pour positionner sur la carte l’emplacement de la structure, cliquer sur le bouton « Marker Tool » ![marker_tool_button](uploads/804216f4eae2d24b8a22f3002fa004fb/marker_tool_button.png)

> [Note JPO : Cela aurait intéressant de traduire « Marker Tool » en français]

![marker_tool_button_in_context](uploads/e387485ce288538a94eb40d0d303a4a4/marker_tool_button_in_context.png)

Une fois le marqueur positionné, sauvegarder en cliquant sur le bouton ![bouton-sauvegarder](uploads/f9b8c927766bcdaf2d710545c48b41f3/bouton-sauvegarder.png).

![sauvegarder_l_emplacement](uploads/88c60c1ca96bdc8d09df55702e4bad42/sauvegarder_l_emplacement.png)

Cocher « Je donne mon accord pour apparaître sur la carte CaPeL des structures » pour que l’emplacement de la structure apparaisse sur la carte publique : https://capel.portcros-parcnational.fr/

![accord-publication](uploads/899a099a3feb5cee8e1fea1483ace17c/accord-publication.png)

> [Note JPO : À quoi sert la case « Test compte OK » ?]

#### Ajouter un bateau

Cliquer sur le bouton Ajouter ![bouton_ajouter_bateau](uploads/919896a1e5c48748103c748f75b3adc9/bouton_ajouter_bateau.png)

![ajouter_bateau](uploads/577f0d103d3d9e0ab8e23db6d92d2737/ajouter_bateau.png)

Une fiche apparaît :

![info_bateau_modale](uploads/0c8d922b42294102e596fe457a1f82e3/info_bateau_modale.png)

Compléter les informations du bateau :

![info_bateau_modale_filled](uploads/9c27a463a245dfea9ea046c051da4c80/info_bateau_modale_filled.png)

Valider la fiche en cliquant sur le bouton « Valider » :

![info_bateau_modale__valider](uploads/fb61368327cc6413229c6c28433b2a73/info_bateau_modale__valider.png)

Le bateau créé apparaît dans le tableau « Mes bateaux » :

![bateau_dans_tableau_bateau](uploads/4bfd28b097564772ab8bbe6efc5908e0/bateau_dans_tableau_bateau.png)

Pour créer un nouveau bateau, il existe deux choix :

- cliquer sur le bouton « Ajouter » comme ci-dessus
- dupliquer la fiche d’un bateau et la modifier

#### Dupliquer la fiche d’un bateau et la modifier

Cliquer sur l’icône Dupliquer :

![dupliquer_1](uploads/ae403e4773bb4b3c80b8ec47c6b8a2c7/dupliquer_1.png)

Cliquer à nouveau sur l’icône Dupliquer pour confirmer la duplication :

![dupliquer_2](uploads/000985e9cd3d8e5fd4954f67c781b7ae/dupliquer_2.png)

Modifier les données en cliquant dans les cases (la sauvegarde est automatique.) :

![dupliquer_3](uploads/cea768c08f0eeb2f9f7f6e86e8883ed0/dupliquer_3.png)

Cliquer sur finaliser mon inscription pour enregistrer les données et finaliser l’inscription :

![sauvegarder_informations](uploads/51e61a215177dabbf970f3b27265b03e/sauvegarder_informations.png)

L’application revient sur l’onglet « Signer les règlements ».