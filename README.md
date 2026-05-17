# Mnemoonic

**Mnemoonic** is a educational application that helps users memorize the stars of night-sky constellations through mnemonics turning star lists like *Sirius, Adhara, Wezen, Murzim, Furud* into memorable sentences like *Smart Astronomers Watch Many Fires*.

---

## Features

- **Mnemonic display** each constellation page presents its mnemonic as a single natural sentence
- **Word tooltips** hover on desktop or long-press on mobile to reveal the star name behind each word
- **Star cards** compact two-column grid with a short description of each star mentioned in the mnemonic
- **Mythology** a brief narrative covering the constellation's mythological origin
- **Animated star background** slow-glowing stars rendered on canvas across all pages
- **Constellation of the Month** the homepage featured card updates automatically based on the current month
- **Search** filter constellations by name, common name, or mnemonic keyword
- **Category filter** browse by Zodiac, Northern, Southern, or Equatorial
- **Mnemonic Builder** a dedicated tool for creating custom mnemonics from any star list
- **Fully offline** no external requests, no CDN dependencies, no internet required after loading

---

## Project Structure

```
mnemoonic/
├── index.html               # Homepage — constellation picker
├── acronym_engine.html      # Mnemonic builder tool
├── privacy_policy.html      # Terms & privacy policy
└── src/
    ├── style.css            # Shared stylesheet for all constellation pages
    ├── orion.html
    ├── canismajor.html
    ├── canisminor.html
    ├── taurus.html
    ├── gemini.html
    ├── cancer.html
    ├── leo.html
    ├── virgo.html
    ├── libra.html
    ├── scorpius.html
    ├── capricornus.html
    ├── aquarius.html
    ├── pisces.html
    ├── aries.html
    ├── auriga.html
    ├── ursamajor.html
    ├── ursaminor.html
    ├── cassiopeia.html
    ├── cepheus.html
    ├── perseus.html
    ├── andromeda.html
    ├── pegasus.html
    ├── bootes.html
    ├── lyra.html
    ├── cygnus.html
    ├── lepus.html
    ├── hydra.html
    ├── eridanus.html
    ├── cetus.html
    ├── ophiuchus.html
    ├── monoceros.html
    ├── centaurus.html
    ├── delphinus.html
    └── pyxis.html
```

---

## Constellations Covered

| Constellation | Common Name | Mnemonic |
|---|---|---|
| Orion | The Hunter | Bright Red Beetles March Across A Star |
| Canis Major | The Greater Dog | Smart Astronomers Watch Many Fires |
| Canis Minor | The Lesser Dog | Pretty Good |
| Taurus | The Bull | All Elephants Always Try Making More Trumpets |
| Gemini | The Twins | People Can Always Trust My Perfect Advice |
| Cancer | The Crab | The Ancient Ibis Always Acts Zealous |
| Leo | The Lion | Real Diamonds Always Zazzle And Charm |
| Virgo | The Maiden | Some People Visit Historic Zoos |
| Libra | The Scales | Zebras Zigzag Before Zany Dances |
| Scorpius | The Scorpion | A Strong Scorpion Dug Lairs |
| Capricornus | The Sea Goat | Delicious Dates At North |
| Aquarius | The Water Bearer | Seven Stars Shine Strongly |
| Pisces | The Fish | All Gamers Always Order Intense Food |
| Aries | The Ram | Huge Sheep Makes Big Bleats |
| Auriga | The Charioteer | Cats Make Many Humans Absolutely Smiled |
| Ursa Major | The Great Bear | All Dogs Always Make Many Pals |
| Ursa Minor | The Little Bear | Please Keep Practicing Every Zodiac Year |
| Cassiopeia | The Seated Queen | Some Clever Girls Read Star Atlases |
| Cepheus | The King | All Excellent Astronomers Zealously Examine Item |
| Perseus | The Hero | Many Astronomers Admire Magnificent Zodiac Mysteries |
| Andromeda | The Chained Princess | Always Make All Dreams Nearly Obvious |
| Pegasus | The Winged Horse | Every Star Makes Almost Magical Heavens |
| Boötes | The Herdsman | Always Imagine Many Stars During Night |
| Lyra | The Lyre | Very Sour Steak |
| Cygnus | The Swan | Don't Stop Gazing During All Afternoons |
| Lepus | The Hare | All Night Glow Dimly |
| Hydra | The Water Serpent | A Giant Zebra Never Pauses |
| Eridanus | The River | A Curious Astronomer Zooms Rapidly |
| Cetus | The Sea Monster | Dolphins Make Every Dark Bay Magical |
| Ophiuchus | The Serpent Bearer | Red Socks Cover Your Yard |
| Monoceros | The Unicorn | Bright And Golden Dwaves Zigzag |
| Centaurus | The Centaur | Rare Horses Makes Mods |
| Delphinus | The Dolphin | Rabbit Steals A Giant Daisy |
| Pyxis | The Compass | Always Beat Games |

---

## Technology

- HTML, CSS, and vanilla JavaScript + wrap inside an app
- Canvas API for animated star backgrounds
- Local storage used solely to persist terms acceptance

---

## Adding a New Constellation

Each constellation page follows the same structure as any existing page in `src/`. The page pulls its styling from `src/style.css` automatically. To add a new constellation:

1. Create `src/yourname.html` following the structure of any existing constellation page
2. Add an entry to the `CONSTELLATIONS` array in `index.html`

---

## License

This project is open source under the **MIT License**.

Any distribution or derivative work must include a visible attribution to **PurpStellar** — the originating project — within its own terms, conditions, or about section.

The developer bears no responsibility for any third-party forks or distributions.

See `privacy_policy.html` for the full license text and terms of use.

---
