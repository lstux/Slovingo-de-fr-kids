# Illustrations IA de Fuchsbau — prompts Gemini

Même méthode que pour Zajko (`Slovingo-sk-fr-kids`) : le **renard est le même** et **Lea est Andrea** (même dessin, autre nom), dans la **Forêt-Noire**. On ajoute **Tom**, **Oma Hilde**, **Opa Karl** et **Herr Falke** ; Frau Stachel reprend la hérisson de Zajko.

Style : dessin animé 2D classique, animaux debout qui portent des vêtements, formes rondes et douces (enfants de 8 à 9 ans), décors peints reconnaissables. Le monde est « façon Bisounours » (voir `Format-animaux.md`).

## Méthode (comme pour Zajko, mais avec Gemini)

1. **Planche des héros** : nouvelle conversation Gemini, joindre les images indiquées, coller le prompt. Garder la meilleure et la déposer dans `docs/illustrations/planche-heros.jpg`. Même chose pour la planche des seconds rôles (`planche-seconds-roles.jpg`).
2. **Défauts à surveiller** : Andrea qui redevient une lapine (oreille gauche pliée, bande blanche, pas de cils), un animal du cours qui redevient « un personnage connu », des yeux réduits à de gros points noirs, des humains plus réalistes que les animaux. Si un personnage dérive : « Keep the characters exactly as in the attached model sheet. »
3. **Si Gemini refuse** : nouvelle conversation et on enlève la phrase qui coince. Ne jamais citer de film, de studio ou de personnage connu.
4. **Ensuite** : les prompts des scènes (une couverture, une image par série), écrits sur le même modèle que dans `Slovingo-sk-fr-kids/docs/Prompts-illustrations.md`, avec ces planches jointes.

**Fichiers de référence** (dans les autres repos) : `Slovingo-sk-fr-friends/esp32/zajko-quest/art/characters/fox-reference.png` et `andrea-reference.png` ; `Slovingo-sk-fr-kids/docs/illustrations/planche-heros.jpg` et `planche-seconds-roles.jpg`.

## Les personnages

| | Personnage | Description à garder |
|---|---|---|
| 🦊 | Le renard (toi) | **identique à Zajko** : sweat bleu roi, sac à dos aux bretelles jaunes, jean, baskets blanches. Le texte ne précise pas garçon ou fille |
| 🐰 | Lea, 8 ans | **même personnage qu'Andrea** (Zajko), sous un autre nom : hase tachetée, oreille gauche pliée, T-shirt vert menthe, sacoche jaune, short en jean, baskets rouges |
| 🦡 | Tom, 9 ans | blaireau trapu, pelage gris argenté, museau rayé noir et blanc, pull orange-brun rapiécé, dé en bois autour du cou |
| 🦉 | Oma Hilde | grand-duc âgée, robe rouge sombre, tablier à fleurs, cuillère en bois |
| 🦌 | Opa Karl | cerf âgé, gilet loden vert, casquette plate, canne |
| 🦔 | Frau Stachel | hérisson, commerçante : **reprise de Zajko** (tablier bleu clair, petites lunettes) |
| 🦅 | Herr Falke | faucon pèlerin, garde du parc : chapeau de garde, gilet kaki, insigne en forme de sapin |

*Mama et Papa (lièvres) ne sont que cités : on les dessinera à la demande pour la scène de famille.*

---

## Planche des héros (renard, Lea, Tom)

**À joindre** : `fox-reference.png`, `andrea-reference.png`, puis `planche-heros.jpg` (de Zajko).

```
Character model sheet for a friendly animated film for children, on a plain light background. Three young animal characters standing side by side at the same scale, each shown front view and three-quarter view, full body, with a few facial expressions (smiling, surprised, shy). They are friends living in the Black Forest in Germany.

The first attached image is the design reference for the fox, the second is the design reference for Andrea. The third attached image is an existing model sheet that shows the fox and Andrea, plus other characters, redrawn as young children: keep the fox and Andrea EXACTLY as in that sheet (same species, colours, clothes, proportions, style) and use the same level of roundness and softness for the new character. Do NOT draw the bear cub and the marmot of that sheet.

1. The red fox, 10 years old (exactly as in the attached sheet): royal-blue hoodie, backpack with yellow straps, navy jeans, white sneakers.
2. Lea: this is the SAME character as Andrea in the attached sheet, only with another name. Keep her EXACTLY as Andrea (a real hare, not a rabbit: speckled brown-grey fur, white blaze from forehead to muzzle, no eyelashes, long ears with black tips where her LEFT ear is folded down, mint-green T-shirt, yellow cross-body bag, denim shorts, red sneakers).
3. Tom, a 9-year-old badger boy, stocky and a little shorter than the fox, easy-going and a bit messy: the classic black-and-white striped face, a silver-grey body, muddy paws, wearing an orange-brown sweater with a patch on the elbow, brown shorts and a big wooden die hanging on a string around his neck.

Height: Lea (ears aside) and the fox are about the same height; Tom is the shortest and the sturdiest.

Style: Classic 2D hand-drawn animated-film style (not 3D, not pixel art): clean ink outlines, flat colours with soft cel shading, expressive faces. Warm, natural light. Anthropomorphic animals walk upright, wear clothes and live among ordinary humans, who are drawn in the same 2D style and find this normal. No text, no letters, no speech bubbles, no logos, no watermark.
```

## Planche des seconds rôles (Oma Hilde, Opa Karl, Frau Stachel, Herr Falke)

**À joindre** : `planche-seconds-roles.jpg` (de Zajko), pour le style et pour Frau Stachel (la hérisson).

```
Character model sheet for a friendly animated film for children, on a plain light background. Four adult animal characters standing side by side, each shown front view and three-quarter view, full body, kind and warm. Two of them are attached as an existing model sheet: keep the hedgehog lady EXACTLY as in that sheet and use the same drawing style for all four. Do NOT draw the ewe and the eagle from the attached sheet: the falcon below replaces the eagle.

1. Oma Hilde, an elderly Eurasian eagle-owl grandmother (big round orange eyes, feathery ear tufts, mottled brown-and-cream plumage, a white feathery bun), wearing a dark-red dress under a flowered apron and holding a wooden spoon. Warm and a bit mischievous.
2. Opa Karl, an elderly red deer stag grandfather (a gentle face with a grey muzzle, modest antlers), wearing a green loden waistcoat, a white shirt, a flat tweed cap between the antlers, and holding a walking stick. Calm and kind.
3. Frau Stachel, the hedgehog lady shopkeeper, exactly as in the attached sheet (light-blue shop apron, small glasses).
4. Herr Falke, a peregrine falcon park ranger (slate-blue-grey back, white chest with fine dark barring, a dark moustache marking on the cheeks, yellow base of the beak), wearing a ranger hat and a khaki-green vest with a small fir-tree badge. Stern but kind.

Style: Classic 2D hand-drawn animated-film style (not 3D, not pixel art): clean ink outlines, flat colours with soft cel shading, expressive faces. No text, no letters, no logos, no watermark.
```
