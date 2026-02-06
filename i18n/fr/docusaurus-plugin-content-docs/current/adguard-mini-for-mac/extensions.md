---
title: Extensions Safari
sidebar_position: 3
---

:::info

Cet article concerne AdGuard Mini pour Mac, qui protège uniquement votre navigateur Safari. Pour protéger l'ensemble de votre Mac, [téléchargez l'application AdGuard](https://agrd.io/download-kb-adblock)

:::

## Qu’est-ce qu’une extension Safari

Les extensions Safari sont de petits logiciels qui ajoutent des fonctionnalités au navigateur web Safari. Ils permettent aux utilisateurs de personnaliser et d'améliorer leur expérience de navigation en ajoutant des fonctionnalités qui ne sont pas nativement intégrées au navigateur. AdGuard Mini pour Mac utilise principalement des extensions pour appliquer des règles de filtrage sur les sites Web ouverts dans Safari.

## Comment ça marche

Pour bloquer les publicités, les traqueurs et les nuisances sur les sites web, AdGuard utilise des règles de filtrage. Les règles d’AdGuard et vos filtres personnalisés sont convertis en des filtres compréhensibles par Safari et intégrés dans 6 extensions Safari :

- AdGuard Général
- AdGuard Confidentialité
- AdGuard Social
- AdGuard Sécurité
- AdGuard Personnalisé
- AdGuard Autres

Chaque extension de blocage de contenu peut inclure jusqu'à 150 000 règles de filtrage actives. Le nombre de règles au sein de la plupart des groupes de filtres ne dépasse pas 150 000. Toutefois, si vous activez trop de filtres spécifiques à une langue ou de filtres personnalisés, vous risquez de dépasser la limite. Dans de tels cas, les règles aléatoires dépassant la limite seront automatiquement désactivées, ce qui peut entraîner un blocage incorrect. **We strongly recommend activating only the filters you need**.

Il existe également une extension supplémentaire responsable d'autres fonctionnalités : _AdGuard pour Safari_, qui ajoute l'icône AdGuard à côté de la barre de recherche dans Safari et permet d'utiliser des règles avancées pour bloquer les publicités complexes.

![Extensions Safari](https://cdn.adtidy.org/content/kb/ad_blocker/mini_mac/check-extensions.png)

Plus d’informations sur chaque extension ci-dessous.

## Extensions de blocage de contenu

_AdGuard General_ applies rules from filters that you can find in _Settings_ → _Filters_ → _Ad blocking_ and _Language-specific_. Cette extension se concentre sur le blocage complet des publicités et inclut des filtres pour les publicités dans des langues spécifiques.

_AdGuard Privacy_ applies rules from filters located in _Filters_ → _Privacy_. Il bloque les mécanismes de suivi et garantit que votre activité de navigation reste privée.

_AdGuard Social_ applies rules from filters that can be found in _Filters_ → _Social Widgets_ and _Filters_ → _Annoyances_. It blocks popups, social media buttons, online assistant windows, and other elements on webpages that you might find annoying.

_AdGuard Security_ applies rules from filters under _Filters_ → _Security_. Cette extension identifie et bloque les éléments potentiellement dangereux, en protégeant les utilisateurs de tout contenu malveillant.

_AdGuard Other_ applies rules from filters that don’t fall under the above-mentioned categories and that are located in _Filters_ → _Other_: _Filter unblocking search ads and self-promotion_, _AdGuard DNS filter_, and _AdGuard Experimental filter_.

_AdGuard Custom_ applies rules from filters that you add on your own to _Custom filters_.

User rules and allowlist rules are included in every extension.

## AdGuard pour Safari

_AdGuard for Safari_ activates the AdGuard icon next to the search bar. It’s useful if you want to quickly set up protection for a specific website or block ads manually.

_AdGuard for Safari_ extension also contains advanced rules that aren’t converted to the format supported by Safari. These include [CSS rules](/general/ad-filtering/create-own-filters#cosmetic-css-rules), [extended CSS selectors](/general/ad-filtering/create-own-filters#extended-css-selectors), and [scriptlets](/general/ad-filtering/create-own-filters#scriptlets), which allow AdGuard to block complex ads, such as those on YouTube.

## Comment gérer les extensions Safari

1. Open Safari and click _Safari_ in the upper left corner of the screen to expand the menu.

   ![Paramètres Safari \*mobile](https://cdn.adtidy.org/content/kb/ad_blocker/safari/adguard-for-safari-settings1.png)

2. Cliquez sur _Paramètres..._

3. Sélectionnez _Extensions_.

   ![Onglet extensions](https://cdn.adtidy.org/content/kb/ad_blocker/safari/adguard-for-safari-extensions1.png)

## Pourquoi AdGuard pour Safari nécessite une autorisation

Lors de l'activation de l'extension _AdGuard pour Safari_, vous pouvez remarquer qu'elle nécessite **l'accès au contenu des pages web** et **l'accès à l'historique de navigation**. Voici pourquoi elle a besoin de ces autorisations :

- L'accès au contenu des pages web est nécessaire pour que le blocage manuel des publicités et les règles de blocage avancées fonctionnent correctement
- L'accès à l'historique de navigation est nécessaire pour vérifier l'état de protection des sites web et déterminer les règles avancées à appliquer

Nous n'utilisons pas ces données à d'autres fins et ne les partageons avec personne. Pour plus d'informations, vous pouvez consulter notre [Politique de confidentialité](https://adguard.com/privacy.html).
