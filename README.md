# Interior-Designing
This project explores interior design using Shakkar AI


The Design Idea:
I want to create AI‑generated Scandinavian style living room interiors with bright natural light, light wood furniture, and soft neutral colours. The spaces should feel calm, minimal, and cosy, with clean lines, plants, and warm lighting that make the room look inviting and realistic.

Answer 1 (What was your idea?):
To create a series of AI‑generated Scandinavian living room interiors that feel bright, calm, and cozy, using Shakkar AI’s ComfyUI workflow.
The focus was on light wood flooring, neutral walls, simple furniture, and plants so the images look like realistic catalog photos of modern Nordic homes.

Answer 2 (What worked well in Shakkar AI?):
The online ComfyUI in Shakkar let me use Stable Diffusion models in the browser with a ready‑made text‑to‑image workflow, so I did not need to install anything or build a graph from scratch.
It was easy to edit the prompt node and sampler settings and instantly see new versions, which helped me iterate through v1–v5 and gradually move closer to my design vision.

Answer 3 (What challenges did you face?):
At first it was confusing to understand what each node (checkpoint, sampler, latent image, text prompts) actually did, and how changing them would affect the final picture.
The early outputs looked slightly “illustrated” or not realistic enough, and it took a few tries to realise that using a painting‑style model and vague prompts was pulling the images away from the clean Scandinavian look I wanted.

Answer 4 (How did you refine the prompts/settings?):
I gradually added more specific interior details to the positive prompt (type of sofa, rug, art, plants, lighting, colour palette) and used a clear negative prompt to remove people, text and distortions, which made each new version more realistic and on‑style.
I switched from a painting checkpoint to a photorealistic SD/SDXL model, increased steps to 30, adjusted guidance (CFG) around 6.5–7, and kept a consistent wide horizontal resolution (896×640) so the images looked like professional interior photos.

Answer 5 (How would you improve in the next attempt)?:
Next time I would explore multiple camera angles and room types (for example, a bedroom or dining area in the same Scandinavian apartment) to build a more complete interior design series.
I would also experiment with saving and loading different ComfyUI workflows, trying advanced nodes like ControlNet or lighting/colour adjustments, to control composition and mood more precisely while still keeping the workflow simple enough for classmates to follow.
