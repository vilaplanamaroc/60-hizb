# Éditeur de prompt pour animation d’images

Ce guide t’aide à transformer une **description de scène cinématographique** en un **prompt professionnel, complet et exploitable** pour animer une image (image-to-video).

## 1) Structure de prompt professionnelle (copier-coller)

Utilise ce squelette, puis remplace les crochets `[...]` :

```text
[SUJET PRINCIPAL + ACTION]
In [LIEU / DÉCOR], [PERSONNAGE(S) / OBJET(S)] [ACTION PRINCIPALE], with [DÉTAILS VISUELS CLÉS].

[CINÉMA / CAMÉRA]
Cinematic style: [genre/référence visuelle], shot on [type de caméra/lens],
camera movement: [dolly in / crane up / handheld / pan left / orbital],
framing: [wide shot / medium / close-up], angle: [low angle / eye level / top shot].

[LUMIÈRE / COULEUR]
Lighting: [golden hour / moonlight / neon / volumetric light],
color palette: [teintes dominantes], contrast: [soft / high contrast],
atmosphere: [fog / dust / rain / smoke / particles].

[MOUVEMENT / ANIMATION]
Motion: [vitesse lente / naturelle / dynamique],
secondary motion: [cheveux, vêtements, feuilles, particules],
physics realism: [réaliste / stylisé],
parallax depth: [faible / moyen / fort].

[QUALITÉ / RENDU]
Ultra-detailed, cinematic, coherent motion, temporal consistency,
sharp subject focus, natural depth of field, 4k, high fidelity.

[CONTRAINTES / NEGATIVE PROMPT]
Negative prompt: flicker, jitter, warped anatomy, deformed hands,
face distortion, duplicated limbs, noisy artifacts, oversaturation,
frame inconsistency, unnatural motion, text, watermark, logo.
```

---

## 2) Méthode rapide en 7 blocs

1. **Sujet + action** : qui fait quoi exactement.
2. **Décor** : lieu, époque, météo, ambiance.
3. **Caméra** : type de plan + mouvement.
4. **Lumière** : source, intensité, heure, contraste.
5. **Style** : réaliste, stylisé, film noir, sci-fi, etc.
6. **Mouvement** : vitesse + micro-mouvements crédibles.
7. **Negative prompt** : tout ce que tu veux éviter.

---

## 3) Exemple prêt à l’emploi (cinématique)

### Description (entrée)
> Un guerrier solitaire avance lentement dans une rue étroite sous la pluie, éclairée par des néons rouges et bleus, pendant qu’une caméra recule devant lui.

### Prompt final (sortie)
```text
A lone warrior walks slowly through a narrow rain-soaked alley at night,
wearing a dark wet coat, subtle breath vapor visible in cold air,
reflections shimmering on the pavement, neon signs glowing red and cyan.

Cinematic neo-noir style, anamorphic lens look, medium-wide shot,
low-angle perspective, smooth backward tracking shot keeping subject centered,
slight handheld micro-movement for realism.

Lighting: high-contrast neon practicals with volumetric rain haze,
color palette dominated by deep blues, crimson highlights, and black shadows.
Atmosphere: dense rain, drifting steam from vents, fine particle mist.

Motion is slow and deliberate, natural body mechanics,
secondary motion in coat fabric and rain droplets,
strong foreground-background parallax for depth.

Ultra-detailed, cinematic, temporal consistency, coherent frame-to-frame motion,
sharp face and silhouette readability, realistic wet-surface reflections, 4k.

Negative prompt: flicker, ghosting, jittery camera, distorted face,
extra limbs, warped anatomy, plastic skin, overexposed neon,
random text, logo, watermark, frame instability.
```

---

## 4) Version “éditeur de prompt” (à remplir rapidement)

```text
Sujet: [...]
Action principale: [...]
Décor: [...]
Ambiance: [...]
Type de plan: [...]
Mouvement caméra: [...]
Lumière: [...]
Palette couleur: [...]
Style visuel: [...]
Mouvements secondaires: [...]
Niveau de réalisme: [...]
Negative prompt: [...]
Durée visée (2-4s, 4-8s, etc.): [...]
Format (16:9, 9:16, 1:1): [...]
```

Ensuite fusionne les champs en un seul prompt en suivant la structure de la section 1.

---

## 5) Astuces pro pour de meilleurs résultats

- Utilise des verbes concrets : *walks, turns, reaches, looks up, wind blows*.
- Limite les actions simultanées (1 action principale + 2 secondaires max).
- Préfère une caméra simple (un seul mouvement) pour éviter les artefacts.
- Décris la cohérence temporelle ("coherent motion", "frame consistency").
- Si le visage est important, précise "sharp facial details, stable identity".
- Commence par une version courte, puis ajoute des couches progressivement.

---

## 6) Si tu veux, je peux te générer ton prompt final

Envoie-moi simplement :
- ta scène (en 2–6 lignes),
- le style visuel souhaité,
- le format vidéo (16:9 / 9:16 / 1:1),
- la durée visée.

Je te renverrai une version **optimisée**, prête à coller dans ton outil d’animation.
