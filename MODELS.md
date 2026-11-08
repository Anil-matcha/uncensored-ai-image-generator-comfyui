# Which image model should I pick?

A short guide to the models in [Muapi's spicy AI image generator catalog](https://muapi.ai/ai-spicy-image-generator). It makes no benchmark claims: try your own prompts, and check the live Muapi page for current pricing.

| You want | Try |
|---|---|
| The highest resolution | Seedream 5.0 Pro, Qwen Image 3.0 or Wan 2.7 Image (up to 2K) |
| Quick, cheap drafts | Z-Image Turbo, or Grok Imagine (flat price per call) |
| To edit one or more existing pictures | Seedream edit (up to 10 images), Qwen Image 3.0 (up to 3), Wan 2.7 Image edit (up to 9) |
| A specific aspect ratio | Qwen Image 2.0 and 3.0 and Wan 2.7 Image offer the widest list, including 21:9 |
| A negative prompt or output format | Qwen Image 3.0 (`negative_prompt`, `output_format`) |

Notes:

- Grok Imagine Image 2 edit works on a previous generation through its `request_id` instead of an uploaded picture.
- Z-Image Turbo is sized with `width` and `height`.
- If a model is missing from the node's dropdown, use the Generic node with the endpoint name.
