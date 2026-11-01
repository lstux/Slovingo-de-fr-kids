# Illustrations IA de Fuchsbau — prompts Gemini

Même méthode que pour Zajko (`Slovingo-sk-fr-kids`) : le **renard est le même**, dans la **Forêt-Noire**. On ajoute **Lea**, **Tom**, **Oma Hilde**, **Opa Karl** et **Herr Falke** ; Frau Stachel reprend la hérisson de Zajko.

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
| 🐰 | Lea, 8 ans | **lièvre** (pas une lapine), fourrure sable doré, ventre blanc, **sans bande blanche**, deux oreilles dressées à pointe brune, bonnet rouge à pompon, salopette verte. Doit rester différente d'Andrea |
| 🦡 | Tom, 9 ans | blaireau trapu, pelage gris argenté, museau rayé noir et blanc, pull orange-brun rapiécé, dé en bois autour du cou |
| 🦉 | Oma Hilde | grand-duc âgée, robe rouge sombre, tablier à fleurs, cuillère en bois |
| 🦌 | Opa Karl | cerf âgé, gilet loden vert, casquette plate, canne |
| 🦔 | Frau Stachel | hérisson, commerçante : **reprise de Zajko** (tablier bleu clair, petites lunettes) |
| 🦅 | Herr Falke | faucon pèlerin, garde du parc : chapeau de garde, gilet kaki, insigne en forme de sapin |

*Mama et Papa (lièvres) ne sont que cités : on les dessinera à la demande pour la scène de famille.*

---

## Planche des héros (renard, Lea, Tom)

**À joindre** : `fox-reference.png`, puis `planche-heros.jpg` (de Zajko).

```
Character model sheet for a friendly animated film for children, on a plain light background. Three young animal characters standing side by side at the same scale, each shown front view and three-quarter view, full body, with a few facial expressions (smiling, surprised, shy). They are friends living in the Black Forest in Germany.

The first attached image is the design reference for the fox. The second attached image is an existing model sheet that shows this fox, plus other characters, redrawn as young children: keep the fox EXACTLY as in that sheet (same species, colours, clothes, proportions, style) and use the same level of roundness and softness for the two new characters. Do NOT draw the other characters of the second image.

1. The red fox, 10 years old (exactly as in the attached sheet): royal-blue hoodie, backpack with yellow straps, navy jeans, white sneakers.
2. Lea, an 8-year-old hare girl (a real hare, not a rabbit): warm sandy-golden fur with a white belly and muzzle, NO white blaze, two very long upright ears with brown tips (both ears up), big round dark eyes, long slender hind legs, a bright, curious and slightly bossy look, wearing a red knitted hat with a red pompom, a white long-sleeve T-shirt under green dungarees, and brown boots. She must look clearly different from Andrea, the hare girl who appears in the attached sheet.
3. Tom, a 9-year-old badger boy, stocky and a little shorter than the fox, easy-going and a bit messy: the classic black-and-white striped face, a silver-grey body, muddy paws, wearing an orange-brown sweater with a patch on the elbow, brown shorts and a big wooden die hanging on a string around his neck.

Height: Lea (ears aside) is slightly smaller than the fox; Tom is the shortest and the sturdiest.

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
