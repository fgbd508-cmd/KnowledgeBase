---
title: Filtering doesn’t stop when AdGuard Mini is disabled
sidebar_position: 3
---

:::info

Cet article concerne AdGuard Mini pour Mac, qui protège uniquement votre navigateur Safari. Pour protéger l'ensemble de votre Mac, [téléchargez l'application AdGuard](https://agrd.io/download-kb-adblock)

:::

If filtering doesn’t stop when AdGuard Mini for Mac is disabled, it may be because content blockers take too long to update.

## Comment procéder

1. Ouvrez Safari.
2. Cliquez sur _Safari_ dans le menu du coin supérieur gauche.
3. Cliquez sur _Paramètres…_ → _Extensions_.
4. Décochez les cases des extensions d'AdGuard Mini : _Personnalisé_, _Mode général_, _Autre_, _Confidentialité_, _Sécurité_, _Social_ et _AdGuard pour Safari_.
   ![Extensions décochées](https://cdn.adtidy.org/content/kb/ad_blocker/mini_mac/unchecked-extensions.png)
5. Redémarrez Safari.
6. Retournez dans Safari → _Paramètres..._ → _Extensions_ et réactivez les extensions AdGuard.

Now everything should work as intended: filtering is on when AdGuard Mini is enabled, and filtering is off when it is disabled.
