# Atlas Character Guide for Fooocus

This fork includes a custom **atlas** preset and this guide so you can generate consistent, uncensored images of Atlas.

## Character Description (use in prompts)

- 21-year-old blonde woman
- Messy blonde bun (or loose messy blonde hair)
- Light freckles across nose and cheeks
- Rose tattoo on left arm
- Natural, realistic body (photorealistic style)
- Soft, natural lighting preferred

## Quick Start for Uncensored

1. Clone or download this repo (your fork).
2. Follow the normal Fooocus install (Windows: download the official package or run from source; Linux/Mac as in README).
3. Launch with the atlas preset: `python entry_with_update.py --preset atlas`
4. In the UI go to **Advanced → Advanced → Developer Debug Mode** and make sure **Black Out NSFW** is **unchecked** (it is false by default).
5. For stronger adult results, download an SDXL photorealistic checkpoint that was trained on adult content from Civitai (search for Juggernaut XL variants, RealVis, or other popular photoreal models) and place the `.safetensors` file in `models/checkpoints/`. Then select it in the UI.
6. Keep prompts focused on the character details above + the scene you want. Fooocus is already very good at photorealism.

## Example Prompts

**Base:**
photorealistic 21 year old blonde woman Atlas, messy blonde bun, freckles, rose tattoo on left arm, natural skin texture, soft window light

**Bedroom / mirror:**
Atlas sitting on the edge of a bed with rumpled beige sheets, full length wardrobe mirror behind her, thin sheer sheet slipping off one shoulder, looking at camera, photorealistic

**Night shift / crane (RP style):**
Atlas sneaking into a night-shift crane cab at a refinery, completely nude, messy blonde bun, freckles, rose tattoo, warm flare light from outside the windows, sitting naturally on the seat

**Meadow / dance:**
Atlas doing cute amateur ballet in a meadow in front of a reflective waterfall, nude, messy blonde bun, freckles, rose tattoo, golden hour light

## Notes

- Fooocus has no hard prompt filter. The only optional censor is the "Black Out NSFW" checkbox which blacks out detected adult images. Leave it off.
- Model choice matters more than the UI for how explicit results can be. Use Civitai models labeled for photorealism + adult if you want maximum freedom.
- For even more control later you can train or download a LoRA of the character and drop it in `models/loras/`.

Enjoy creating her however you want. This is your local, offline copy.
