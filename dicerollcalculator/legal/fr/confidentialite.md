---
layout: document
title: "Politique de confidentialité — Dice Roll Calculator"
lang: fr
permalink: /dicerollcalculator/legal/fr/confidentialite
counterpart: /dicerollcalculator/legal/en/privacy-policy
counterpart_lang: en
---
_Dernière mise à jour : 2026-10-08_

> Version française, **seule faisant foi**. Une [traduction anglaise de courtoisie](/dicerollcalculator/legal/en/privacy-policy) est disponible.

## 1. Responsable du traitement

François LAMBERT — voir [mentions légales](/dicerollcalculator/legal/fr/mentions-legales). Contact : app.dicerollcalculator.polyester538@passmail.net

## 2. Données collectées

| Donnée | Finalité | Base légale |
|--------|----------|--------------|
| Identifiant publicitaire (IDFA sur iOS, identifiant publicitaire Google sur Android) — **version gratuite, iOS et Android uniquement** | Affichage de publicités personnalisées via Google AdMob | Consentement (SDK Google UMP, complété sur iOS par l'App Tracking Transparency) |
| Historique des lancers de dés | Fonctionnalité de l'app — stocké **en local uniquement** (SQLite — dossier Application Support sur iOS/macOS, stockage interne privé sur Android), jamais transmis | — (pas de transmission, pas de base légale requise) |
| Reçu d'achat (App Store ou Google Play selon la plateforme) — **version payante uniquement** | Validation de l'achat « retirer les pubs » | Exécution du contrat (achat) |
| Données techniques de diagnostic en cas de plantage — **toutes les versions, les trois plateformes** | Corriger les défauts de l'app (§4) | Intérêt légitime : assurer la fiabilité de l'app |

La version payante (ou la version gratuite après achat « retirer les pubs ») n'affiche **aucune publicité** et ne transmet **aucun identifiant publicitaire**. Les rapports d'incident décrits au §4 s'appliquent en revanche à elle comme aux autres : corriger un plantage ne dépend pas de la façon dont l'app est financée.

**Le widget d'écran d'accueil lit ces mêmes données, sur l'appareil.** Sur iOS et macOS, les jets enregistrés et le dernier lancer sont recopiés dans un conteneur partagé entre l'app et son extension (« App Group ») : c'est le seul moyen pour une extension de lire les données de son application. Sur Android, le widget ouvre directement la base locale de l'app. Dans les deux cas rien ne quitte l'appareil — étant entendu qu'un nom de jet que vous choisissez peut alors s'afficher sur votre écran d'accueil.

**La version macOS n'affiche aucune publicité**, y compris gratuite : Google AdMob ne couvre pas cette plateforme. Elle ne collecte donc aucun identifiant publicitaire. Les rapports d'incident du §4, eux, la concernent aussi.

## 3. Publicités et partenaires tiers

Sur **iOS et Android**, la version gratuite affiche des publicités via **Google AdMob** (Google Ireland Limited). AdMob peut recevoir l'identifiant publicitaire de l'appareil pour proposer des annonces personnalisées, sous réserve du consentement recueilli via le SDK Google UMP (User Messaging Platform), complété sur iOS par l'autorisation App Tracking Transparency. Les publicités ne sont chargées qu'**après** réponse au formulaire de consentement.

- Politique de confidentialité Google AdMob : https://policies.google.com/technologies/ads

## 4. Rapports d'incident

Quand l'app se ferme inopinément, un rapport technique est transmis à **Sentry** (Functional Software, Inc.) pour permettre de corriger le défaut. Cela vaut pour **toutes les versions et les trois plateformes** — c'est indépendant de la publicité et de l'achat « retirer les pubs ».

**Ce que le rapport contient** : la pile d'appels du plantage, la version de l'app, la version du système d'exploitation, le modèle d'appareil, la langue, et un identifiant d'installation tiré au hasard par l'app. Ce dernier ne sert qu'à savoir combien d'appareils distincts un même défaut touche ; il ne vous désigne pas et disparaît si l'app est désinstallée.

**Ce qu'il ne contient pas** : aucun identifiant publicitaire, aucune capture d'écran, aucun élément de votre historique de lancers (noms de jets compris), aucune adresse e-mail. L'app est configurée pour ne pas transmettre votre adresse IP — étant entendu que, comme pour toute connexion à un serveur, celui-ci voit l'adresse d'où elle provient au moment de l'envoi.

**Hébergement** : les données sont traitées dans la **région européenne** de Sentry (Allemagne). Sentry agit comme sous-traitant.

- Politique de confidentialité de Sentry : https://sentry.io/privacy/

**Base légale** : intérêt légitime — une app qui plante sans que son éditeur puisse le savoir ne se corrige pas. Vous pouvez vous opposer à ce traitement en écrivant à l'adresse de contact (§9).

## 5. Durée de conservation

- Historique des lancers : conservé localement tant que l'app n'est pas désinstallée ou que l'utilisateur ne vide pas l'historique (bouton dédié dans l'app).
- Identifiant publicitaire : géré par AdMob/Google, non stocké par l'app elle-même.
- Rapports d'incident : supprimés par Sentry au bout de **30 jours** (durée du plan utilisé).

## 6. Droits des utilisateurs (RGPD)

Conformément au RGPD, vous disposez d'un droit d'accès, de rectification, d'effacement et d'opposition sur vos données. Pour l'exercer : app.dicerollcalculator.polyester538@passmail.net. L'historique local peut aussi être effacé directement depuis l'app (bouton « vider l'historique »).

## 7. App Tracking Transparency (iOS)

Ce mécanisme est propre à iOS : Android n'a pas d'équivalent obligatoire (seul le consentement RGPD via le SDK Google UMP s'applique, §3) et macOS n'affiche aucune publicité. Dans la version gratuite sur iOS, l'app demande l'autorisation ATT après le consentement RGPD et avant tout tracking à des fins publicitaires. Refuser cette autorisation n'empêche pas l'usage de l'app ; les pubs restent affichées mais non personnalisées.

## 8. Sécurité

Aucune donnée n'est transmise à un serveur propre à l'app : il n'y a pas de backend. Les seules données quittant l'appareil le font via deux SDK tiers, chacun selon sa propre politique de confidentialité : **Google Mobile Ads** (version gratuite, iOS et Android uniquement — §3) et **Sentry** (toutes les versions, les trois plateformes — §4).

## 9. Contact

app.dicerollcalculator.polyester538@passmail.net
