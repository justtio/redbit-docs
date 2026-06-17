# GPT-image-2 Brief: Card Series Workflow

## Purpose

Generate a documentation image that explains when to use Series mode on image Cards and how planned slots move from one base prompt into reviewed outputs. This is a future image brief only; no generated bitmap is committed in this repo.

## Target Page

`docs/en/product/cards.mdx`, `docs/zh/product/cards.mdx`, and optionally the Series section in `docs/en/product/modules.mdx` / `docs/zh/product/modules.mdx`

## Aspect Ratio

`4:3` landscape, readable inside a documentation content column.

## Style

Structured product explainer, card grid layout, neutral background, restrained rose/blue/green accents, no decorative blobs, labels large enough for docs, vector-like UI rather than photorealistic output.

## Prompt

Create a technical explainer illustration for Redbit image Card Series mode. Show a base prompt entering a planner, then branching into eight possible slot cards labeled hero, detail, usage, comparison, social, poster, brand, storyboard. Each slot should show editable prompt, status, selected output, and review marker in simplified form. Include a small side note that Series supports 3, 4, 6, or 8 slots and templates such as auto, ecommerce, social, explainer, character, poster, brand, and storyboard. The image should communicate that Series plans a reusable set but each output still needs review. Use generic placeholder thumbnails, not real generated images.

## Negative Prompt

No real product photos, no illegible tiny text, no celebrity faces, no brand logos, no API tokens, no exaggerated success claims, no chaotic mood board, no single-color purple theme.

## Alt Text

Diagram-style illustration showing one image prompt planned into multiple Series slots with editable prompts, status, selected outputs, and review markers.

## Placement Guidance

Place directly under the Series Mode section in Cards or Feature Modules. Keep the existing text/table as the source of truth; the image should explain the workflow visually without adding new capabilities.
