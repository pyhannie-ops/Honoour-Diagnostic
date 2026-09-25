# Our Philosophy page: restructure (Wix Editor)

This guide updates the **Our Philosophy** page on **Hannie Consultants cc** to
match `Philosophy_Restructure_Mockup_1.html`. It reuses the blocks and colour
palette already on the page. The compass diagram stays as it is.

## Status (checked 2026-09-25)

| Item | State |
|---|---|
| Site | Hannie Consultants cc (Wix Editor, Velo enabled) |
| Page text and layout | **Edit these in the Wix Editor.** Wix has no public API for changing Editor page elements, so the changes can't be pushed remotely. |
| Compass section | Leave it as it is |

Open the page: **My Sites > Hannie Consultants cc > Edit Site**, then pick
**Our Philosophy** from the Pages menu.

## Palette (already on the site)

| Token | Hex | Used for |
|---|---|---|
| Ink | `#1A1A1A` | Headline text |
| Gold | `#C08A2E` | Card left border |
| Gold pale | `#F5F1E8` | Hook section background, card hover |
| Teal | `#095656` | Eyebrow, "Read the full philosophy" link, bridge line |
| Mist | `#F7F6F3` | Card background |
| Slate | `#2C3E50` | Body and card text |

Font: Poppins, as on the rest of the site.

## Page order (top to bottom)

1. Hook section (existing top strip)
2. "What's yours?" grid (existing strip holding the nine lines)
3. Bridge line
4. Compass diagram (unchanged)

## 1. Hook section

Use the existing top strip. Set its background to Gold pale `#F5F1E8` if it
isn't already. Centre the text.

| Element | Text | Style |
|---|---|---|
| Eyebrow | OUR PHILOSOPHY | Poppins bold, 11px, all caps, letter spacing ~0.2em, Teal |
| Headline | You didn't arrive here by accident. | Poppins semibold, ~36px desktop, Ink |
| Sub-line | Something in your system (your team, your vision, or your way of working) is ready for a change. | Poppins regular, 16px, Slate |

### "Read the full philosophy" drop-down

Replace the existing long philosophy text box with a **collapsible text**
element, so the four paragraphs stay hidden until the visitor opens them.

1. Click **Add Elements (+) > Text > Collapsible Text** and drop it under the
   sub-line, inside the hook strip.
2. Paste the four paragraphs below into it.
3. In **Settings**, set it to expand with a button, and set the button text to
   **Read the full philosophy**.
4. **Design:** body text Poppins 15px Slate, left-aligned, max width ~640px.
   Button text Poppins semibold, Teal, no fill, with a Teal underline. Hover
   colour Gold.
5. Delete the old text box once the new one is in place.

Hidden text:

> At Hannie Consultants, we provide an environment in which clarity,
> collaboration and transformation can exist. We provide creative coaching,
> Agile facilitation, and purposeful reframing for individuals and teams and
> design systems that respect both structure and soul.
>
> We see a world in which clarity comes first, collaboration happens
> naturally, and transformation seems solid. Where rhythm meets resonance,
> every interaction becomes a step toward deeper connection.
>
> HannieVerse Enterprise™ Compass is the philosophy that guides our work. It
> is the place where structure meets soul, where operational intelligence
> comes together with human depth, and where clarity becomes something you
> actively practice each day rather than merely having it as an idea.
>
> HannieVerse Enterprise™ compass is neither a trend nor a tool. It's a way of
> working that is clear, grounded, and wise. This approach helps the work grow
> and succeed.

## 2. "What's yours?" grid

Turn the nine stacked, centred lines into a 3 × 3 grid of cards in the
existing strip (white background). Use a **repeater** or a **3-column
layout** with nine boxes.

- Heading above the grid: **What's yours?** (Poppins semibold, ~24px, Ink,
  centred)
- Each card: Mist `#F7F6F3` fill, 3px Gold `#C08A2E` left border only, text
  Poppins 14–15px Slate, left-aligned, ~20px padding, ~14px gap between cards
- Hover (optional): fill Gold pale, left border Teal
- Mobile: stack the cards in one column

Card text, in order:

1. We act with purpose, calm and precision.
2. We lead with care.
3. We design with rhythm, not haste.
4. We honour depth, not noise.
5. We guide by instinct, not pressure.
6. We pace by breath, not urgency.
7. We create systems in which structure and humanity exist together.
8. We listen deeply.
9. We respond with intention. We shape what's true, not what's convenient.

## 3. Bridge line

Put a single centred line directly above the compass diagram:

> *Here's what ours looks like when it meets the work.*

Style: Poppins italic, ~18px, Teal.

## 4. Compass diagram

No changes.

## Checks before publishing

- [ ] Preview in mobile view: hook text centred, cards in one column
- [ ] "Read the full philosophy" opens and closes the four paragraphs
- [ ] The old nine-line text and old philosophy text box are removed
- [ ] The compass section is unchanged
- [ ] Publish
