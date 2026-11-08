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

**À joindre** : `fox-reference.png`, `andrea-reference.png` (repo friends, `esp32/zajko-quest/art/characters/`), puis `planche-heros.jpg` de Zajko (repo sk-fr-kids, `docs/illustrations/`).

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

---

## Scènes des séries (fiche 05 de chaque série, plus le kit 03)

Une illustration par série, dans la fiche 05 (le dialogue), comme pour Zajko. Chaque prompt est complet. **Joindre la planche des héros** (et la planche des seconds rôles quand elle est indiquée), **puis la photo de référence** : soit une image déjà dans `img/`, soit le lien Commons de la fiche.

### Kit 03 · Salut, Lea !

Fiche `10_Series_00_KitSurvie_03_dialogue.md` → `img/illus_00_kit.jpg`

**À joindre** : planche des héros + photo de référence : Red_Fox_drinking_from_a_lake (Commons, lien dans la fiche)

```
Use the attached model sheet for the characters (keep them exactly as designed). Use the attached photo as the reference for the place.

Scene: A sunny forest path in the Black Forest in summer, with tall spruce trees and ferns on both sides. The young fox, with his backpack, meets Lea the hare for the first time: they stand face to face on the path, a little shy, the fox waving, Lea smiling with her long ears upright.

Style: Classic 2D hand-drawn animated-film style (not 3D, not pixel art): clean ink outlines, flat colours with soft cel shading, rounded friendly shapes. Soft, painterly background with few small details, so the characters stand out, but the place stays recognisable. Landscape format 16:9. No text, no letters, no logos, no watermark. Lea wears her mint T-shirt, yellow satchel and red sneakers.
```

### Familie 05 · Bei Lea zu Hause

Fiche `10_Series_01_Familie_05_bei-lea-zu-hause.md` → `img/illus_01_familie.jpg`

**À joindre** : planche des héros + planche des seconds rôles + photo de référence : European_badger (Commons, lien dans la fiche)

```
Use the attached model sheets for the characters (keep them exactly as designed). Use the attached photo as the reference for the place.

Scene: In a clearing at the edge of a dark forest, a cosy wooden house with a round door, flowers and a big spruce beside it. Lea the hare proudly shows her home; Tom the badger, in his orange sweater, waves from the doorway, and Oma Hilde the owl stands on the porch in her flowered apron. The young fox, with his backpack, looks around with a smile.

Style: Classic 2D hand-drawn animated-film style (not 3D, not pixel art): clean ink outlines, flat colours with soft cel shading, rounded friendly shapes. Soft, painterly background with few small details, so the characters stand out, but the place stays recognisable. Landscape format 16:9. No text, no letters, no logos, no watermark. Lea wears her mint T-shirt, yellow satchel and red sneakers.
```

### Haus 05 · Verstecken spielen

Fiche `10_Series_02_Haus_05_verstecken-spielen.md` → `img/illus_02_haus.jpg`

**À joindre** : planche des héros + photo de référence : Feldhase_kauernd (Commons, lien dans la fiche)

```
Use the attached model sheet for the characters (keep them exactly as designed). Use the attached photo as the reference for the place.

Scene: Inside a cosy burrow-house with wooden beams, a game of hide-and-seek. Oma Hilde the owl is the seeker: she stands in the doorway with one wing over her eyes, counting, with a big smile. The three friends are hiding: Tom the badger squeezes into a wooden wardrobe, peeking out with one eye; Lea the hare lies flat under a low bed, with only her long ears and her red sneakers showing; the young fox crouches behind an old sofa, with just his ears, eyes and fluffy tail sticking out, trying not to laugh. Nobody except Oma Hilde covers their eyes. Warm light, toys on the floor.

Style: Classic 2D hand-drawn animated-film style (not 3D, not pixel art): clean ink outlines, flat colours with soft cel shading, rounded friendly shapes. Soft, painterly background with few small details, so the characters stand out, but the place stays recognisable. Landscape format 16:9. No text, no letters, no logos, no watermark. Lea wears her mint T-shirt, yellow satchel and red sneakers.
```

### Essen 05 · Mittagessen bei Oma Hilde

Fiche `10_Series_03_Essen_05_mittagessen-bei-oma-hilde.md` → `img/illus_03_essen.jpg`

**À joindre** : planche des héros + planche des seconds rôles + photo de référence : Eurasian_eagle-owl (Commons, lien dans la fiche)

```
Use the attached model sheets for the characters (keep them exactly as designed). Use the attached photo as the reference for the place.

Scene: A warm kitchen with a big wooden table in Oma Hilde's nest-house, with a steaming bowl of vegetables and potatoes in the middle. Oma Hilde the owl carries the bowl; Lea the hare and Tom the badger sit at the table, and the young fox sits at the end with a napkin, happy and hungry.

Style: Classic 2D hand-drawn animated-film style (not 3D, not pixel art): clean ink outlines, flat colours with soft cel shading, rounded friendly shapes. Soft, painterly background with few small details, so the characters stand out, but the place stays recognisable. Landscape format 16:9. No text, no letters, no logos, no watermark. Lea wears her mint T-shirt, yellow satchel and red sneakers.
```

### Stadt 05 · Verlaufen in der Stadt

Fiche `10_Series_04_Stadt_05_verloren-in-der-stadt.md` → `img/illus_04_stadt.jpg`

**À joindre** : planche des héros + photo de référence : SWV_Wegweiser (Commons, lien dans la fiche)

```
Use the attached model sheet for the characters (keep them exactly as designed). Use the attached photo as the reference for the place.

Scene: A forest path at a crossroads, with a wooden signpost with arrows pointing in several directions. The young fox stands in front of it holding an open map, looking lost; Tom the badger, who knows every trail, points confidently down the path with a big smile. A small sunlit village can be seen behind the trees. Only the fox and Tom are in the scene. The signpost arrows are blank.

Style: Classic 2D hand-drawn animated-film style (not 3D, not pixel art): clean ink outlines, flat colours with soft cel shading, rounded friendly shapes. Soft, painterly background with few small details, so the characters stand out, but the place stays recognisable. Landscape format 16:9. No text, no letters, no logos, no watermark.
```

### Tiere 05 · Im Wald mit Oma Hilde

Fiche `10_Series_05_Tiere_05_im-wald-mit-oma-hilde.md` → `img/illus_05_tiere.jpg`

**À joindre** : planche des héros + planche des seconds rôles + photo de référence : Calluna_vulgaris panoramic trail (Commons, lien dans la fiche)

```
Use the attached model sheets for the characters (keep them exactly as designed). Use the attached photo as the reference for the place.

Scene: A forest path in the Black Forest with blooming heather and tall trees. Oma Hilde the owl leads the walk. Herr Falke the peregrine falcon park ranger, in his ranger hat, khaki vest and fir-tree badge, stands on the path and raises one wing in a friendly "stay on the path" gesture. The young fox, Lea and Tom stand on the path and look up at a deer on the hillside in the background. Friendly, curious mood.

Style: Classic 2D hand-drawn animated-film style (not 3D, not pixel art): clean ink outlines, flat colours with soft cel shading, rounded friendly shapes. Soft, painterly background with few small details, so the characters stand out, but the place stays recognisable. Landscape format 16:9. No text, no letters, no logos, no watermark. Lea wears her mint T-shirt, yellow satchel and red sneakers.
```

### Spiele 05 · Spieleabend bei Lea

Fiche `10_Series_06_Spiele_05_spieleabend-bei-lea.md` → `img/illus_06_spiele.jpg`

**À joindre** : planche des héros + planche des seconds rôles + photo de référence : Brettspiel Mensch ärgere dich nicht (Commons, lien dans la fiche)

```
Use the attached model sheets for the characters (keep them exactly as designed). Use the attached photo as the reference for the place.

Scene: A cosy wooden living room in a forest house on a rainy evening. Through the window we see only dark spruce trees in the rain: no street, no street lamps, no buildings. A board game is set on a low table: Lea the hare, Tom the badger, Oma Hilde the owl and the young fox sit around it, laughing. Tom has just rolled a small wooden die, the size of a walnut, which lies on the board. Warm lamp light.

Style: Classic 2D hand-drawn animated-film style (not 3D, not pixel art): clean ink outlines, flat colours with soft cel shading, rounded friendly shapes. Soft, painterly background with few small details, so the characters stand out, but the place stays recognisable. Landscape format 16:9. No text, no letters, no logos, no watermark. Lea wears her mint T-shirt, yellow satchel and red sneakers.
```
