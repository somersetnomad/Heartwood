# Heartwood

An immersive website you walk through like a tree: climb into the canopy, stand inside the trunk, descend into the roots.

Heartwood is a single-page educational experience about trees. The whole page is one living tree, drawn live behind the content. It moves from the open sky, through the crown and branches, into the wood of the trunk, and down into roots, soil and glowing fungal networks. It aims to leave visitors with a sense of connection to trees and responsibility toward them.

## What's inside

**The living world tree.** One continuous tree is drawn behind the whole page: dawn sky, swaying crown with light shafts, bark-textured limbs, the inside of the trunk with water rising and sugar sinking, labelled soil layers, and roots joined by glowing mycelium.

**Canopy**
- **Leaf microscope (×400).** Chloroplasts streaming, a stoma breathing, gases in and out, with a day/night toggle.
- **Life in the crown.** An animated woodland in storeys: tits timing their broods to oak caterpillars, a jay planting acorns, a woodpecker drumming, a nuthatch walking down a trunk, a treecreeper spiralling up, an owl in a hollow. Plus seed-caching nutcrackers, fig-eating hornbills and harpy eagles.
- **Messages on the wind.** Seven ways trees signal: airborne alarms, calling parasitic wasps and birds, bitter leaves, flowers and fruit, ultrasonic clicks of thirst, electrical alarms, and fungal links. Each one is animated and rated for evidence.
- **Rivers in the sky.** How forests recycle rain inland and seed clouds.
- **Seasons** and the private **Tree Journal**.

**Branches**
- Engraved species plates, drawn branch by branch.
- Forest biomes.
- **A world on one tree.** An explorable oak supporting 2,300 species.
- Trees and climate, with a carbon calculator.
- **Trees and us.** Hospital views, street trees, the ash borer study and forest bathing, sorted by strength of evidence.
- Culture and myth.

**Trunk**
- Anatomy and a 360-year growth-ring timeline.
- **Reading a tree.** Ten signs on a veteran oak and what they mean.
- **The long death.** From veteran to nurse log, and who lives at each stage.

**Roots**
- **Root tip microscope (×600).** The trade between root and fungus, in both kinds of partnership.
- **Mycelium network explorer.**
- **The fungal kingdom.**
- **Forest, river and sea.** Salmon forests and Japan's oyster-farmer tree planters.
- An honest evidence summary and full sources.

**Honour moment.** A breathing minute, a personal promise, and an invitation to step outside.

## Science and honesty

The content draws on published research, including:

- Simard et al. (1997)
- Beiler et al. (2010)
- Song et al. (2015)
- Babikova et al. (2013)
- Karst et al. (2023)
- Crowther et al. (2015)
- Harris et al. (2021)

Where a claim is debated, the page says so, for example how much trees "communicate" through fungal networks. Full references are at the bottom of the page.

## Running it

There are no build steps and no dependencies.

1. Open `index.html` in a browser.
2. To publish with **GitHub Pages**:
   1. Push this repository to GitHub.
   2. Go to **Settings → Pages**.
   3. Choose **Deploy from a branch**, then pick `main` and `/ (root)`.

Google Fonts load from the web. If they can't load, the page falls back to system fonts.

## Journal storage

Journal entries are saved in the visitor's browser (`localStorage`):

- They stay between visits on the same browser.
- They don't sync across devices.
- They are lost if site data is cleared.

When the page runs as a Claude artifact, entries are saved privately to the visitor's Claude account instead.

## Accessibility

- A **Still motion** button freezes all animation. The page also follows the system's reduced-motion setting.
- Animated canvases have text descriptions.
- Journal photos get alt text.
- Tabs and controls work with the keyboard.
- The layout works down to phone width.
