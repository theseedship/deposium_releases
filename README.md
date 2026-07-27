# Deposium — binaires desktop

Ce dépôt héberge les binaires publiés de l'application **Deposium** pour poste
de travail. Il ne contient aucun code source : celui-ci vit dans des dépôts
privés.

## Télécharger

Les versions publiées sont dans [Releases](../../releases).

Windows x64 pour l'instant ; les autres plateformes viendront.

## Mises à jour

L'application embarque son propre mécanisme de mise à jour : elle consulte ce
dépôt et propose d'installer les nouvelles versions depuis son icône de zone
de notification.

## Signature

Les binaires ne sont pas encore signés. Windows SmartScreen affichera donc un
avertissement à la première exécution — « Informations complémentaires », puis
« Exécuter quand même ». La signature Authenticode est prévue.

## Provenance

Les artefacts sont construits par intégration continue depuis les sources
privées. Rien n'est téléversé à la main.
