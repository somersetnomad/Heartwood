# Heartwood

An immersive website you walk through like a tree: climb into the canopy, stand inside the trunk, descend into the roots.

Heartwood is a single-page educational experience about trees. The whole page is one living tree, drawn live behind the content. It moves from the open sky, through the crown and branches, into the wood of the trunk, and down into roots, soil and glowing fungal networks. It aims to leave visitors with a sense of connection to trees and responsibility toward them.

## What's inside

- **A living world tree.** One continuous tree is drawn on a canvas across the whole page, with these parts from top to bottom:
  - Dawn sky and swaying foliage.
  - Light shafts through the leaves.
  - Bark-textured limbs.
  - The inside of the trunk, with water rising and sugar sinking.
  - Labelled soil layers.
  - Roots joined by glowing mycelium.
- **Leaf microscope (×400).**
  - Chloroplasts streaming inside palisade cells.
  - A stoma opening and closing, with gases moving through it.
  - A day/night toggle.
- **Root tip microscope (×600).** Sugar, nutrients and water trading between root cells and fungi. You can switch between the two kinds of partnership: ectomycorrhizal and arbuscular.
- **Mycelium network explorer.** Choose a tree and watch carbon, nitrogen, water and defence signals move through the network. Every claim is tagged with how strong the evidence is.
- **Growth rings timeline.** A 360-year English oak whose rings record real events, from the Great Frost of 1709 to the Great Storm of 1987.
- **Engraved species plates.** Eight trees, each drawn branch by branch as it scrolls into view.
- **Tree Journal.**
  - Record encounters with trees, including photos.
  - Write answers to reflection prompts.
  - Follow a "tree friend" through the seasons.
- **Honour moment.** A guided breathing minute, a personal promise of care, and an invitation to step outside.

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
