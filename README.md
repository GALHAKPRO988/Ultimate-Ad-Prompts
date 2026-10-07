# ad-poster-master-prompt

A **master prompt** plus **style templates** to turn a photo of your product into a professional advertising poster using any image-capable AI (Claude, ChatGPT, Gemini, etc.).

You attach a photo, paste the master prompt, drop in one style template, fill in the brief, and get a ready-to-use poster.

## How it works (3 steps)

1. **Pick a style template** from [`templates/`](templates/) that matches your ad.
2. **Copy [`PROMPT_MASTER.md`](PROMPT_MASTER.md)**, fill in the `{{PLACEHOLDERS}}` and paste the template's *Style block* where indicated.
3. **Send it to the AI together with your product photo.** Ask for tweaks or variants if needed.

## Repo structure

```
.
├── PROMPT_MASTER.md        # The master prompt (never changes)
├── templates/              # Swappable style blocks
│   ├── minimalist-product.md
│   ├── sale-discount.md
│   ├── event.md
│   ├── food-restaurant.md
│   ├── fashion-lifestyle.md
│   ├── tech-gadget.md
│   ├── real-estate.md
│   └── local-business.md
├── guides/
│   ├── prepare-your-photo.md
│   └── common-mistakes.md
└── LICENSE
```

## Why a master prompt + templates?

The master prompt holds everything that stays constant: how to treat your photo, the brief fields, layout rules, text rules and output format. The templates only define the **visual style**. This way you can reuse the same prompt for any product and just swap the style.

## Quick example

> *Attach: photo of a coffee bag.*
> Master prompt with `{{PRODUCT}} = Single-origin coffee, 250 g`, `{{HEADLINE}} = Wake up properly`, `{{CTA}} = Order today`, and the **Minimalist product** style block pasted in.

## Tips

- Most image models still struggle with long text. Keep the headline under 6 words and check spelling in the result.
- If the AI alters your product, re-send the photo and add: *"Do not modify the product. Only change the background and lighting."*
- Read [`guides/common-mistakes.md`](guides/common-mistakes.md) before your first run.

## Contributing

New templates are welcome. Copy any file in `templates/`, keep the same sections (When to use / Style block / Example brief) and open a pull request.

## License

MIT. See [LICENSE](LICENSE).
