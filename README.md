# ✦ SquishCase

> 🏆 **Vibecoded for a Marketing 305 class project tradeshow (Our project won Best Product!) **

A custom phone case configurator where you design your own sensory "squishy" case from the ground up. Users can pick a texture, tint the gel, choose a frame, set the finish, fit it to your phone — then flip into **Squish Test** mode and actually pop every bubble. 

## 🎀 What it does

SquishCase is a single-page, interactive product builder. Everything updates live as you customize, so you always see exactly what you're buying before it goes in the bag.

The whole case is rendered as SVG and rebuilt on the fly with every choice you make — no pre-made images, no product photos. The "squishy" look comes from layered gradients and shine highlights generated in code.

## 🛠️ Build your case

Step through five quick choices in the configurator:

| step | options |
|------|---------|
| **squish texture** | orbs · pop dots · bubbles · waves · ice cubes |
| **gel color** | 12 shades from bubblegum to midnight, plus a confetti mix |
| **case frame** | clear · frost white · jet black · tinted pink · smoke |
| **finish** | glossy · matte · iridescent (holo, +$5) |
| **phone model** | iPhone 16/15 · Galaxy S24 · Pixel 9 |

## 🫧 Squish Test mode

The fun part. Hit **"Try it out — squish it"** and the case grows, the configurator hides, and every single texture element becomes tappable. Tap one and it:

- squishes with a springy press animation
- sends out a ripple
- makes a little pop sound (Web Audio — no audio files)
- ticks up your squish counter

There's a mute toggle if you're somewhere quiet, and a button to head back to designing.

## 🚀 Run it

No build step, no dependencies, no install. It's one self-contained HTML file.

```
# just open it in a browser
open index.html
```
## 🧰 Built with

- Vanilla **HTML / CSS / JavaScript** — zero frameworks
- **SVG** for the entire case (generated procedurally)
- **Web Audio API** for the pop sounds
- **Google Fonts** — Fredoka + Hanken Grotesk
