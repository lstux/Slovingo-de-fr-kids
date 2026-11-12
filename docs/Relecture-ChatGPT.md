# Relecture éditoriale de Slovingo-de-fr-kids

**Document de travail — nouvelle passe ChatGPT**  
**Dépôt :** \`lstux/Slovingo-de-fr-kids\`  
**Cours :** Fuchsbau — allemand vers français, public enfant (à partir de 8 ans)  
**Périmètre :** les 45 fiches Markdown (introduction, Kit de Survie et séries 01 à 06), les documents de format et de progression, le README, \`lang.json\`, les crédits d'images et les fichiers d'exercices présents.  
**But :** relever les corrections et incohérences visibles dans l'état actuel du dépôt. Ce document est une proposition de relecture ; il ne modifie aucune fiche ni aucun exercice.

## 1. Bilan général

Fuchsbau a une identité agréable et bien distincte : le jeune renard arrive dans la Forêt-Noire, rencontre Lea le lièvre et ses amis, et apprend l'allemand dans un univers animalier doux. Le fil rouge du renard qui préfère les baies aux lièvres fonctionne bien, Tom le blaireau a un rôle identifiable, et Oma Hilde apporte une présence familiale chaleureuse.

La progression est globalement logique :
- le Kit de Survie donne les premières formules utiles ;
- Familie introduit les bases de \`sein\`, \`haben\` et des verbes réguliers ;
- Haus travaille les pièces, les positions et quelques verbes séparables ;
- Essen introduit les repas, les goûts et les commandes ;
- Stadt permet de se déplacer et de demander son chemin ;
- Tiere développe les noms d'animaux et les actions ;
- Spiele réutilise les verbes pour proposer des jeux et jouer ensemble.

La documentation pédagogique est particulièrement utile : elle distingue les points enseignés, les formes seulement données « à l'oreille » et les mots à ne pas introduire trop tôt. Il faut conserver cette discipline.

Les principaux chantiers restants sont :
1. quelques erreurs ou approximations de prononciation ;
2. des mots utilisés sans être introduits ou signalés ;
3. des tableaux de vocabulaire des fiches extra incomplets ;
4. une incohérence de contenu dans Spiele 06 ;
5. des informations de statut et de crédits d'images qui ne correspondent plus tout à fait au dépôt actuel ;
6. quelques affirmations culturelles trop générales.

**Limite linguistique :** je ne suis pas locuteur natif allemand. Les corrections grammaticales très sûres sont séparées des propositions de naturel, qui méritent une validation orale par un germanophone, notamment pour le vocabulaire enfantin et les tournures idiomatiques.

## 2. Points prioritaires

| Priorité | Fichier / emplacement | Observation | Proposition |
|---|---|---|---|
| Haute | Introduction 04 — prononciation | La règle « le ch gratte après a, o, u » oublie \`au\`, alors que la fiche donne \`auch\` comme exemple. | Écrire « après a, o, u et au » ; garder \`ich\` comme exemple du son doux. |
| Haute | Introduction 04 — prononciation | « Le v se dit comme un f » est trop absolu : c'est vrai dans beaucoup de mots allemands d'origine germanique (\`Vater\`), mais pas dans de nombreux emprunts (\`Vase\`, \`Vulkan\`, etc.). | Préciser « dans beaucoup de mots allemands, v se prononce f ; dans certains mots empruntés, il se prononce v ». |
| Haute | Introduction 05 — nombres | \`Wie viel? Fünf!\` signifie plutôt « Combien (en quantité / combien ça coûte) ? ». Pour compter des éléments, on attend \`Wie viele?\`. | Remplacer par \`Wie viele? Fünf!\` (« Combien ? Cinq ! »), ou ajouter un contexte de quantité non dénombrable pour conserver \`Wie viel?\`. |
| Haute | Essen 01 — nouveaux mots | \`Wasser\` et \`Käse\` sont utilisés dans les phrases, mais absents du tableau « Les nouveaux mots ». | Ajouter \`das Wasser\` et \`der Käse\`, ou remplacer ces phrases par des mots déjà introduits. |
| Haute | Spiele 06 — scène 3 | Le titre français annonce « Le puzzle perdu », mais l'introduction dit que le cerf-volant est cassé ; le dialogue parle ensuite de faire un puzzle. | Renommer la scène, par exemple « Le cerf-volant cassé », ou réécrire l'introduction pour annoncer un puzzle perdu. |
| Haute | Fiches extra — plusieurs séries | Des mots signalés comme nouveaux dans les dialogues ne figurent pas dans les tableaux récapitulatifs : \`Gefunden\`, \`Minuten\`, \`Enten\`, \`Juhu\`. | Compléter les tableaux correspondants et vérifier les exercices associés. |
| Moyenne | Tiere 01 — Lea | \`Lea ist ein Hase\` est grammaticalement compréhensible, mais \`Hase\` désigne normalement le lièvre au masculin ; pour une femelle, \`Häsin\` est plus précis. | Préférer \`Lea ist eine Häsin\` si l'on veut marquer son sexe, en expliquant le mot ; à valider avec un natif. |
| Moyenne | Haus 06 — scène 1 | \`Und hier ist das Wohnzimmer\` utilise \`hier\`, qui n'a pas été introduit dans les fiches précédentes ni signalé comme nouveau. | Ajouter \`hier\` au vocabulaire / à une carte antérieure, ou remplacer par une formulation connue. |
| Moyenne | Haus 05 — dialogue | \`Gefunden!\` est signalé comme nouveau, mais n'est pas repris dans le tableau de vocabulaire de Haus 06. \`Noch einmal\` apparaît également sans être signalé. | Ajouter \`Gefunden\` à l'extra et signaler / expliquer \`noch einmal\` si l'expression n'est pas considérée comme déjà acquise. |
| Moyenne | Stadt 05 — dialogue | \`Ich komme mit!\` introduit le verbe séparable \`mitkommen\`, qui n'est pas mentionné dans la progression ni signalé comme nouveau. | Le signaler comme expression à retenir, ou le remplacer par une formule déjà vue. |
| Moyenne | Tiere 05 — dialogue | \`die Enten\` est signalé comme nouveau dans le dialogue, mais absent du tableau Tiere 06. | Ajouter \`die Ente / die Enten\` au tableau de vocabulaire de l'extra. |
| Moyenne | Spiele 05 — dialogue | \`Juhu\` est signalé comme nouveau, mais absent du tableau Spiele 06. | Ajouter \`Juhu\` au tableau récapitulatif. |
| Moyenne | Kit de Survie 04 — extra | \`Pizza\`, \`Banane\` et surtout \`Wasser\` apparaissent dans les mini-dialogues alors que ces mots ne figurent pas dans le vocabulaire du Kit. | Ajouter ces mots au tableau ou les introduire dans une fiche précédente. |
| Basse | docs/Format-animaux.md | « remporter ses déchets » est une faute de français. | Écrire « emporter ses déchets ». |
| Basse | README, Progression, Format, Format-animaux | Plusieurs passages disent que toutes les illustrations restent à faire / sont en TODO, alors que les fiches ont déjà des photos Commons et plusieurs illustrations IA dans \`img/\`. | Harmoniser le statut : sélection initiale faite, éventuelles améliorations / remplacements restant à faire. |
| Basse | img/credits.md | « Toutes les images viennent de Wikimedia Commons » est inexact pour les illustrations générées avec Gemini et le fond de carte. | Distinguer photos Commons, illustrations générées à partir de références et fond de carte généré. |

## 3. Relecture par fiche

### 3.1. Introduction

**Introduction 02 — Où parle-t-on allemand ?**

La fiche présente les trois pays principaux : Allemagne, Autriche et Suisse. C'est un bon choix pour commencer, à condition que « les trois principaux » ne soit pas compris comme « les seuls pays où l'allemand est langue officielle ». Le Luxembourg, le Liechtenstein et certaines régions d'autres pays sont également germanophones.

Proposition facultative :
« Voici trois pays où l'allemand est une langue officielle ou très largement parlée. Il y en a d'autres, comme le Liechtenstein et le Luxembourg ! »

La formule actuelle « les trois principaux » est acceptable pour une première découverte ; je ne la classe pas comme une faute.

**Introduction 04 — Comment ça se prononce ?**

Deux ajustements sont recommandés.

1. Le son dur de \`ch\` apparaît après \`a, o, u\`, mais aussi après la diphtongue \`au\`. La fiche utilise précisément \`auch\` en exemple : la règle devrait donc inclure \`au\`.
2. La règle sur \`v\` est trop générale. Dans \`Vater\`, le \`v\` se prononce bien comme un \`f\`, mais dans des mots empruntés comme \`Vase\`, il se prononce généralement comme un \`v\`.

Proposition de formulation :
- « Après a, o, u et au, le ch est guttural, comme dans \`auch\`. »
- « Le w se prononce comme un v. Dans beaucoup de mots allemands, le v se prononce comme un f, par exemple \`Vater\`. Dans certains mots empruntés, il se prononce comme un v. »

Pour un enfant débutant, il n'est pas nécessaire de dresser une liste d'exceptions ; il faut simplement éviter une règle présentée comme absolue.

**Introduction 05 — Compter jusqu'à 10**

La carte \`Wie viel? Fünf!\` est à revoir. \`Wie viel?\` correspond à « combien ? » au sens de quantité ou de prix. Pour demander combien d'objets il y a, on utilise \`Wie viele?\`.

Proposition :
\`Wie viele? Fünf!\`
> Combien ? Cinq !

Cela reste une phrase elliptique, mais elle convient à un exercice de comptage. Pour une phrase complète : \`Wie viele Finger? Fünf!\` (« Combien de doigts ? Cinq ! »).

### 3.2. Kit de Survie

**Kit de Survie 04 — Alles zusammen**

La fiche annonce « Pas de mot nouveau ici », mais la scène du goûter utilise :
- \`Pizza\`
- \`Banane\`
- \`Wasser\)

Les deux premiers mots sont transparents pour un francophone, mais ils ne figurent pas dans le tableau récapitulatif du Kit. \`Wasser\` est moins transparent et mérite vraiment d'être enseigné avant d'être utilisé dans un dialogue.

Deux solutions :
- ajouter \`die Pizza\`, \`die Banane\` et \`das Wasser\` au vocabulaire du Kit ;
- ou remplacer la scène par des mots déjà présents dans les fiches.

La première solution est la plus naturelle : ce sont des mots utiles et faciles à retenir.

### 3.3. Série Familie

**Familie 02 — Wie alt bist du?**

La phrase :
\`Die Kinder sind klein.\`
est correcte. L'explication « après est ou sont, klein ne change jamais » est vraie pour l'adjectif attribut (après \`sein\`). Pour éviter une généralisation trop large, je préciserais :

« Après \`sein\` (être), l'adjectif ne change pas : \`klein\` reste \`klein\`, que l'on parle d'un garçon, d'une fille ou de plusieurs enfants. »

Cela évite que l'enfant applique cette règle à un adjectif placé devant un nom (\`das kleine Kind\`), forme qui sera étudiée plus tard.

Le Coin allemand affirme qu'un adulte pose souvent « Wie alt bist du? » comme toute première question à un enfant. C'est une généralisation culturelle trop large. Proposition plus prudente :
« Quand on rencontre un enfant, on peut lui demander son âge : \`Wie alt bist du?\` »

**Familie 03 — Bei Oma und Opa**

L'explication de \`einen Hund\` et \`meinen Hund\` est une bonne manière de faire entendre l'accusatif masculin sans imposer le terme grammatical. Elle est juste dans les exemples choisis.

Je garderais toutefois l'expression « dans ces phrases » plutôt que « après ce verbe » si la règle est reprise ailleurs : le changement ne concerne pas uniquement \`haben\`, mais la fonction du complément masculin. Pour le niveau actuel, l'approche par morceaux est adaptée.

**Familie 05 — Bei Lea zu Hause**

Le dialogue est naturel et réutilise bien les notions des fiches précédentes. \`Der Kuchen ist toll!\` et \`Bis bald!\` sont correctement signalés comme nouveaux.

Rien de prioritaire à corriger ici.

### 3.4. Série Haus

**Haus 05 — Verstecken spielen**

Le dialogue contient plusieurs expressions données en bloc, ce qui est prévu dans la progression : \`ich verstecke mich\`, \`wo seid ihr\`, etc. C'est acceptable si ces structures restent clairement identifiées comme des expressions à reconnaître, et non comme des règles à produire immédiatement.

En revanche :
- \`Gefunden!\` est signalé comme nouveau, mais ne figure pas dans le tableau récapitulatif de Haus 06 ;
- \`Noch einmal?\` apparaît sans explication ni signalement.

Proposition :
- ajouter \`Gefunden\` = « trouvé ! » au tableau de Haus 06 ;
- ajouter \`noch einmal\` = « encore une fois » au tableau ou le signaler dans le dialogue.

**Haus 06 — scène 1**

Original :
\`Und hier ist das Wohnzimmer. Es gibt ein Sofa!\`

\`hier\` n'a pas été introduit avant cette scène. Il ne s'agit pas d'une faute d'allemand, mais d'un mot nouveau dans une fiche qui annonce qu'il n'y en a pas.

Proposition : ajouter \`hier\` = « ici » dans une fiche antérieure ou dans le tableau de l'extra. On peut aussi remplacer la phrase par une formulation utilisant \`dort\`, déjà appris, si le sens de la scène le permet.

### 3.5. Série Essen

**Essen 01 — Was wir essen**

Les phrases utilisent \`Wasser\` et \`Käse\`, qui ne sont pas dans le tableau « Les nouveaux mots » :
- \`Ich trinke Wasser.\`
- \`Isst du Käse?\`

Ces deux mots sont ensuite réutilisés dans Essen 06. Je recommande de les ajouter au tableau :
- \`das Wasser\` — l'eau
- \`der Käse\` — le fromage

Cela porte la fiche au-delà de son objectif de six mots. Si l'on veut absolument conserver le plafond, remplacer \`Käse\` par un mot déjà connu et faire apparaître \`Wasser\` comme complément signalé.

**Essen 03 — Wie schmeckt das?**

\`Probier mal!\` est une formule utile et naturelle. Elle est mentionnée dans la progression comme forme donnée telle quelle. Je la garderais, mais il faut veiller à ce qu'elle ne soit pas considérée comme un verbe déjà maîtrisé dans les exercices.

**Essen 05 — Mittagessen bei Oma Hilde**

Le dialogue est cohérent avec le personnage de Lea qui n'aime pas les légumes et avec le renard qui préfère les baies. \`Oma, du kochst sehr gut!\` est correct.

La phrase \`Ich bin satt\` est bien expliquée comme « je suis rassasié » au sens littéral, puis traduite naturellement par « je n'ai plus faim ». À conserver.

### 3.6. Série Stadt

**Stadt 05 — Verlaufen in der Stadt**

\`Ich habe mich verlaufen\` est une bonne expression et la documentation a raison de la préférer à \`Ich bin verloren\`, qui n'a pas le sens voulu.

Deux éléments méritent cependant d'être explicités :
- \`Ich komme mit!\` introduit le verbe séparable \`mitkommen\` (« venir avec »). Le mot \`mit\` a déjà été vu comme préposition, mais le verbe composé est une nouvelle structure.
- \`Minuten\` est signalé comme nouveau dans le dialogue, mais il manque au tableau de Stadt 06.

Proposition :
- signaler \`mitkommen\` ou la formule \`Ich komme mit!\` comme expression à retenir ;
- ajouter \`die Minute / die Minuten\` au tableau de Stadt 06.

Le tableau de Stadt 06 ne reprend pas non plus l'expression \`Ich habe mich verlaufen\`, que la progression indique pourtant comme une expression nouvelle de la série. Je recommande de l'ajouter au récapitulatif sous forme de bloc.

### 3.7. Série Tiere

**Tiere 01 — Waldtiere**

Le cours présente Lea comme un lièvre, puis écrit :
\`Lea ist ein Hase.\`

C'est compréhensible, mais si l'on veut désigner précisément une femelle, le mot allemand est \`die Häsin\`. On pourrait écrire :
\`Lea ist eine Häsin.\`
> Lea est une hase.

Cela ajoute un mot au vocabulaire. Autre possibilité : garder \`der Hase\` comme nom générique de l'espèce, mais alors mieux vaut expliquer que le nom appris est le nom général de l'animal, même si Lea est une femelle. À confirmer avec un locuteur natif.

**Tiere 05 — Im Wald mit Oma Hilde**

Le dialogue est agréable et le rappel de sécurité \`Bleibt bitte auf dem Weg!\` est bien placé.

Le mot \`die Enten\` est signalé comme nouveau dans la réplique :
\`Schau mal, die Enten schwimmen!\`
Mais il n'est pas repris dans le tableau de vocabulaire de Tiere 06. Ajouter :
- \`die Ente / die Enten\` — le canard / les canards.

Le fait que \`möchtet ihr\`, \`bleibt\` et \`kommt\` soient donnés en bloc est cohérent avec la progression, mais il faut veiller à ne pas les demander en production libre dans les exercices avant qu'ils soient travaillés.

### 3.8. Série Spiele

**Spiele 05 — Spieleabend bei Lea**

Le dialogue fonctionne bien et les nouveaux éléments \`es regnet\`, \`klar\` et \`Juhu\` sont signalés.

Cependant, \`Juhu\` ne figure pas dans le tableau de vocabulaire de Spiele 06. L'ajouter :
- \`Juhu\` — youpi !

**Spiele 06 — scène 3**

Le titre français est :
« Le puzzle perdu »

Mais l'introduction indique :
« Oh non ! Le cerf-volant de Tom est cassé. Que faire à la place ? »

Puis le dialogue confirme que le cerf-volant est cassé et que les personnages décident de faire un puzzle. Il n'y a donc pas de puzzle perdu.

Proposition :
- titre : « Le cerf-volant cassé » ;
- ou, si l'on veut conserver le titre « Le puzzle perdu », modifier l'introduction pour annoncer la disparition du puzzle.

Je recommande « Le cerf-volant cassé », qui correspond exactement au contenu du dialogue.

## 4. Cohérence des fiches extra et du vocabulaire

La documentation indique que les fiches 06 doivent reprendre le vocabulaire de la série et ne pas introduire de nouveaux mots. Plusieurs écarts apparaissent dans l'état actuel des fiches :

| Série | Élément introduit dans le dialogue | Problème | Action |
|---|---|---|---|
| Kit de Survie | Pizza, Banane, Wasser | Absents du tableau récapitulatif ; Wasser n'est pas transparent. | Ajouter au vocabulaire du Kit. |
| Haus | Gefunden | Signalé dans Haus 05, absent de Haus 06. | Ajouter à l'extra. |
| Haus | noch einmal | Utilisé sans signalement et absent du tableau. | Ajouter ou signaler. |
| Stadt | Minuten | Signalé dans Stadt 05, absent de Stadt 06. | Ajouter à l'extra. |
| Stadt | Ich habe mich verlaufen | Expression signalée dans le dialogue, absente du tableau. | Ajouter comme bloc lexical. |
| Tiere | die Enten | Signalé dans Tiere 05, absent de Tiere 06. | Ajouter \`die Ente / die Enten\`. |
| Spiele | Juhu | Signalé dans Spiele 05, absent de Spiele 06. | Ajouter à l'extra. |

Les tableaux extra ne sont pas seulement des résumés : ils servent aussi de référence pour les exercices et la révision. Il faut donc qu'ils reprennent tous les mots et expressions que l'enfant est censé avoir appris.

## 5. Français, culture et cohérence éditoriale

### 5.1. Petites corrections de français

Dans \`docs/Format-animaux.md\`, remplacer :
- « remporter ses déchets »
par :
- « emporter ses déchets ».

Cette expression apparaît également dans plusieurs Coins allemands ; vérifier que la bonne forme est utilisée partout.

### 5.2. Généralités culturelles

Quelques Coins allemands utilisent des formulations trop absolues ou généralisantes :

- « Chaque enfant allemand reçoit un immense cornet en carton » à propos de la \`Schultüte\` : la tradition est très répandue, mais la formulation « chaque enfant » est trop catégorique.
- « Les Allemands adorent un mot… » à propos de \`gemütlich\` : c'est une généralisation inutile.
- « En Allemagne, on dit merci très souvent » : cela peut être reformulé comme une observation de politesse sans en faire un trait national.
- « Il y a des pistes cyclables partout » : « dans beaucoup de villes » est plus juste.
- « Quand un adulte rencontre un enfant, c'est souvent la toute première question qu'il pose » : trop général ; préférer « on peut demander son âge ».

Le document \`Format-de-fr.md\` demande explicitement d'éviter les clichés sur les Allemands. Je recommande donc de privilégier des faits précis et localisés (la Schultüte, le parc national, le gâteau de la Forêt-Noire, les jeux de société) plutôt que des phrases qui attribuent un comportement à toute une population.

### 5.3. Suisse et pays germanophones

La fiche d'introduction présente Allemagne, Autriche et Suisse comme les trois principaux pays. C'est une simplification pédagogique acceptable. On pourrait ajouter une petite mention du Liechtenstein et du Luxembourg pour éviter l'idée que l'allemand se limite à ces trois pays.

### 5.4. Genre et personnage 🦊

Le français est bien rédigé sans accord masculin ou féminin imposé à l'enfant. C'est une contrainte importante du projet et elle est globalement respectée.

Il faut aussi distinguer :
- le genre grammatical des noms allemands (\`der Fuchs\`, \`der Hase\`, \`das Eichhörnchen\`) ;
- le sexe du personnage représenté.

Le cas de Lea (\`der Hase\` / \`die Häsin\`) est le seul endroit où cette distinction mérite une décision éditoriale claire.

## 6. Documentation, statut du projet et images

### 6.1. Statut des illustrations

Le README, \`docs/Progression.md\`, \`docs/Format-de-fr.md\` et \`docs/Format-animaux.md\` indiquent encore que toutes les illustrations sont à faire ou que toutes les fiches sont en TODO.

Or, dans l'état actuel du dépôt :
- les fiches Markdown ont déjà des photos Wikimedia Commons sélectionnées ;
- plusieurs fiches utilisent des illustrations générées présentes dans \`img/\` (\`illus_00_couverture.jpg\`, \`illus_00_kit.jpg\`, \`illus_01_familie.jpg\`, etc.) ;
- les crédits de la première passe sont déjà renseignés dans \`img/credits.md\).

Le statut devrait donc être harmonisé. Proposition :
« Première sélection d'images effectuée : photos Wikimedia Commons dans les fiches et illustrations générées pour les dialogues principaux. Des remplacements et améliorations restent possibles. »

### 6.2. Crédits des images

La phrase d'ouverture de \`img/credits.md\` (« Toutes les images viennent de Wikimedia Commons ») n'est plus exacte : le fichier contient aussi des images générées avec Google Gemini et un fond de carte généré.

Proposition :
« Les photographies utilisées dans les fiches proviennent de Wikimedia Commons. Certaines illustrations et le fond de carte ont été générés spécifiquement pour le projet ; leur référence éventuelle à une photographie source est indiquée dans le tableau. »

Pour les images générées à partir de photos Commons, il faut distinguer :
- l'attribution de la photographie de référence ;
- l'illustration générée ;
- la licence annoncée pour le fichier final.

Je ne peux pas déterminer à moi seul si chaque illustration générée constitue juridiquement une œuvre dérivée de la photo de référence, ni si la licence de la photo s'applique automatiquement au résultat. Il vaut mieux éviter de déclarer systématiquement « œuvre dérivée, même licence » sans validation adaptée.

## 7. Exercices

Le dépôt contient bien des fichiers d'exercices faits à la main pour les fiches, conformément à la documentation. Cette relecture n'a pas consisté en un audit exhaustif de chacun des distracteurs et de chaque question des 45 fichiers JSON.

Après correction des fiches, il faudra en particulier :
1. ajouter ou remplacer les mots manquants du Kit de Survie et d'Essen 01 ;
2. compléter les tableaux extra de Haus, Stadt, Tiere et Spiele ;
3. vérifier que les exercices reprennent exactement les formes corrigées ;
4. vérifier qu'aucun distracteur allemand ne contient un mot qui n'a pas encore été vu ;
5. relancer la synchronisation et le build pour repérer les exercices périmés.

Attention : si l'on modifie une carte ou une traduction dans une fiche, il faut mettre à jour le fichier \`.exercises.json\` correspondant. La documentation du projet décrit déjà le workflow à suivre.

## 8. Méthode de finalisation recommandée

1. Corriger la fiche de prononciation (\`ch\` après \`au\`, nuance sur \`v\`).
2. Remplacer \`Wie viel?\` par \`Wie viele?\` dans la fiche de comptage si l'objectif est de compter des objets.
3. Compléter le vocabulaire du Kit et d'Essen 01.
4. Compléter les tableaux extra avec \`Gefunden\`, \`noch einmal\`, \`Minuten\`, \`Ich habe mich verlaufen\`, \`die Enten\` et \`Juhu\`.
5. Corriger le titre de la scène 3 de Spiele 06.
6. Décider si Lea est présentée comme \`ein Hase\` au sens générique ou \`eine Häsin\`.
7. Harmoniser les documents de statut et les crédits d'images.
8. Revoir les exercices concernés et lancer le build.
9. Faire écouter les fiches de prononciation et les dialogues à un germanophone, puis les tester avec un enfant.

## 9. Conclusion

Fuchsbau est déjà un cours cohérent et sympathique. Son univers animalier fonctionne, les personnages ont chacun leur place, et la progression grammaticale est pensée avec soin. Il n'y a pas besoin de tout réécrire.

Le meilleur gain viendra d'une passe de cohérence pédagogique : s'assurer que chaque mot utilisé a bien été présenté, que les fiches extra récapitulent vraiment ce qui a été appris, et que les exercices restent alignés sur les fiches.

Pour la langue, les points les plus importants à faire écouter par un natif sont la prononciation de \`ch\` et \`v\`, la désignation de Lea comme hase, et le naturel des dialogues à voix haute. Une fois ces points validés, le cours aura une base très propre pour être testé avec un enfant.
