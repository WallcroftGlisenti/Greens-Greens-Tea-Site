# Green’s Greens — Tea Site

A single-page tea house site in the *Floraison en Filigrane* manner: Art Nouveau
botanical linework, gilded Art Deco frames, and a restrained ivory, olive and
plum palette.

## Viewing

Open `index.html` in a browser. There is no build step, no package manager and
no JavaScript dependency beyond the file itself. Google Fonts (Cinzel
Decorative, Cinzel, Cormorant Garamond) load from the network; everything else
— including every illustration — is inline SVG.

## Notes

- Twelve teas are catalogued, in order, all presently **Empty**. No prices,
  origins, harvests or tasting notes are invented; unavailable fields show “—”.
- The basket is deliberately inert: every “Add to Basket” control is disabled
  and marked `aria-disabled="true"`.
- The desktop navigation is a gold filigree vine that draws on load and grows
  as the page is read. Below 64rem it becomes a top bar and a leaf-node drawer.
- Filtering, the Tea Ritual dialog, scroll-spy navigation and reveal animations
  are progressive enhancements; the page reads without JavaScript.
- Motion respects `prefers-reduced-motion`.

## Structure

```
index.html   the whole site — markup, CSS, SVG sprite and JavaScript
LICENSE      Unlicense
```
