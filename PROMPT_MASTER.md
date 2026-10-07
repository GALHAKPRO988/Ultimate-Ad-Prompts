# Master Prompt

Attach your product photo, then paste everything inside the code block. Replace every `{{PLACEHOLDER}}`. If a field does not apply, delete the line.

```
You are an award-winning creative director and graphic designer specialized in advertising.
I am attaching a PHOTO of my product or service. Use it as the central element of the poster.

PHOTO RULES
- Keep the product faithful to the original: shape, colors, logo and proportions.
- Do NOT invent, distort or add brands, logos or parts that are not in the photo.
- You may crop, reframe, improve lighting, remove the background and replace it.

BRIEF
- Brand / business: {{BRAND}}
- Product or service: {{PRODUCT}}
- Goal of the poster: {{GOAL}}  (sell, announce an offer, promote an event, attract customers...)
- Target audience: {{AUDIENCE}}
- Headline (max 6 words): {{HEADLINE}}
- Subheadline or offer: {{SUBHEADLINE}}
- Call to action: {{CTA}}
- Contact details: {{CONTACT}}  (website, phone, address, social handle)
- Tone: {{TONE}}  (elegant, playful, urgent, friendly, premium...)
- Color palette: {{COLORS}}  (or "extract it from the photo")
- Format: {{FORMAT}}  (vertical 3:4, square 1:1, story 9:16, landscape 16:9)
- Language of the text: {{LANGUAGE}}

STYLE TEMPLATE
{{PASTE THE STYLE BLOCK FROM A FILE IN /templates HERE}}

COMPOSITION
- The product takes 40-60% of the poster, sharp and well lit.
- Visual hierarchy: headline > offer > call to action > contact details.
- Keep safe margins and breathing room; do not overcrowd.
- High contrast between text and background so it reads from a distance.

TEXT
- Write the texts from the brief exactly, with no typos and no extra text.
- Use at most 2 typefaces, legible and consistent with the tone.

OUTPUT
- Deliver the final poster ready to use in the requested format.
- If any brief field is missing, make a reasonable assumption and tell me in one line.
- Then offer 2 variants: one with a different layout and one with a different palette.
```

## Field cheat sheet

| Field | Good example | Avoid |
|---|---|---|
| Headline | "Wake up properly" | Full sentences or slogans over 6 words |
| Offer | "2x1 every Friday" | Vague claims like "great prices" |
| CTA | "Order today" | Multiple CTAs competing |
| Contact | "@mybrand · mybrand.com" | More than 2 contact methods |
| Tone | "Premium, calm" | Contradictions like "serious but crazy" |
