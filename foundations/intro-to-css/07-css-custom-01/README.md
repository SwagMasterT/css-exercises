# Class and ID Selectors (Challenge)

This is a harder follow-up to `02-class-id-selectors`. You will **create the HTML first** (including classes/IDs), then write the CSS selectors.

For colors, use a non-keyword value (RGB, HEX, or HSL).

> ### Note:
> Browser fonts may differ from the desired outcome image. Confirm the correct fonts are applied to the right elements; small visual differences are okay.

## Part 1 — Create the HTML

Start from the empty skeleton. Build these elements in order (use the suggested text so you can match the outcome):

1. **Item 1** — a `p` with the text `Item 1 - shared odd styles`. Give it a class you’ll reuse on the other odd items (1, 3, and 5).
2. **Item 2** — an `a` with an **absolute** `href` of `https://www.theodinproject.com` and the text `Item 2 - unique ID link`. Give it a unique `id` (no shared odd class).
3. **Item 3** — a `p` with the text `Item 3 - shared odd styles, but cooler!`. Use the same odd class as item 1, **plus** a second class for a larger font. Wrap the word `cooler` in `strong`.
4. **Item 4** — an `img` with a **relative** `src` of `./images/icon.svg`, a useful `alt`, and its own unique `id`.
5. **Item 5** — a `p` with the text `Item 5 - shared odd styles`. Same odd class as items 1 and 3 (nothing else).
6. **Item 6** — an `a` with a **relative** `href` of `./gallery.html` and the text `Item 6 - unique ID relative link`. Give it a unique `id`, reuse item 3’s larger-font class, and wrap the word `relative` in `strong`.

Hint: elements that look alike should share a **class**; one-off looks should use an **id**; slight variations often mean **multiple classes**.

## Part 2 — Create the CSS

In `style.css`, add rules so that:

* **All odd-numbered text items (1, 3, 5)**: a light red/pink background, and fonts `Verdana`, `DejaVu Sans`, with `sans-serif` fallback
* **Item 2 (absolute link, ID)**: blue text and a font size of 32px
* **Item 3**: in addition to the odd styles, a font size of 24px
* **Item 4 (image, ID)**: a width of 80px and a solid 4px dark teal border
* **Item 5**: only the shared odd styles (no extras)
* **Item 6 (relative link, ID)**: a light green background, a font size of 24px, and bold

## Desired Outcome

![desired outcome](./desired-outcome.png)

### Self Check

**HTML**
- Did you build the markup (with classes/IDs, `img`, absolute + relative links, and `strong`) before finishing the CSS?
- Do the odd items share a class?
- Do the even items use unique IDs?
- Does item 3 use multiple classes?

**CSS**
- Did you use class and ID selector syntax correctly?
- Are non-keyword color values used somewhere?