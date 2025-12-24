Structure
=========

Screenplay & Branching
----------------------

To satisfy the exam structure, you must produce a screenplay for Act I featuring:

*   **Four "weak branches"**: Subtle information that matters later.
*   **Four "strong branches"**: Decisions that immediately alter the story path.

Arcweave Project
----------------

.. note::
   Link to the Arcweave structure will be added here.

   *   [Placeholder for Arcweave Link]

Gen-AI Prompts
--------------

The aspect ratio for all generated content is set to 16:9, and here they are listed in the order they appear in the film.

- Cinematic_Forest_Cabin_Drone_Video

.. code-block:: json

   {
     "prompt": "Cinematic top-down aerial drone shot, looking straight down at a dense, dark pine forest at night. In the dead center, a single, solitary wooden cabin with a warm light glowing from one window. The cabin is completely isolated, surrounded by endless trees and fog. The camera slowly zooms in towards the roof of the cabin. High contrast, moonlight shadows, photorealistic, 8k resolution, mysterious atmosphere.",
     "negative_prompt": "text, watermark, logo, humans, people, animals, roads, cars, other buildings, power lines, daylight, cartoon, low quality",
     "camera_movement": "Zoom In"
   }

- Scholar_s_Cabin_Alien_Monolith_Video

.. code-block:: json

   {
     "prompt": "Interior of the same rustic, dimly lit wooden cabin. The room is a cluttered scholar's study, filled with stacks of old books covering the desk and piled high on the wooden floor. In the center, a middle-aged man with salt-and-pepper hair stands perfectly still with his back to the camera, staring out of a dark window. To the side of the room stands a looming, human-sized sleek black monolith (alien technology); it has a matte obsidian finish with a very faint, singular soft blue pulse of light (minimalist). The man does not move. Atmospheric lighting, dust particles in the air, cinematic composition.",
     "negative_prompt": "text, watermark, face, bright neon lights, multicolored lights, explosion, fire, blurry, distorted anatomy, messy rendering, modern furniture",
     "camera_movement": "Pan Right"
   }

- Sci_Fi_Glitch_Video_Generation

   For this one, I sent some of the photos of my pitch deck presentation to the agent.

.. code-block:: json

   {
     "prompt": "Sci-fi glitch video sequence where attached photographs appear to come alive, high-energy cinematic opening, aggressive digital glitch effects, scanlines, chromatic aberration, holographic overlays, photos subtly animating with parallax motion, flickering lights, data distortion, rapid cuts synced to beat, cyberpunk sci-fi atmosphere, neon accents, dark futuristic tone, dynamic camera movement, immersive and intense",
     "negative_prompt": "static slideshow, no motion, smooth corporate transitions, calm pacing, natural colors, warm lighting, vintage or retro style, fantasy elements, cartoon animation, soft focus, low energy, minimal effects"
   }

- Earth_Under_Alien_Control

.. code-block:: json

   {
     "prompt": "Cinematic wide-angle view of Earth in the year 2421 under alien control, seen from space. The planet is partially in darkness with subtle glowing alien structures and orbital constructs encircling Earth. Massive non-human ships form a quiet blockade in orbit. Soft bioluminescent lights trace unfamiliar geometric patterns across continents. Atmosphere slightly altered with faint aurora-like energy bands. Hyper-realistic, high detail, dramatic lighting, science fiction, realistic scale, no humans visible, no symbols or readable markings.",
     "negative_prompt": "text, numbers, letters, logos, symbols, watermarks, captions, UI elements, labels, maps, flags, cartoon style, anime, low resolution, blurry, noisy, oversaturated, fantasy magic, steampunk, medieval elements",
     "style": "cinematic science fiction realism",
     "camera": {
       "angle": "orbital wide shot",
       "distance": "low Earth orbit"
     },
     "lighting": "dramatic rim lighting from the sun with deep planetary shadows",
     "color_palette": "cold blues, deep blacks, muted greens, subtle violet highlights",
     "composition": "Earth centered, alien structures framing the planet without obscuring it"
   }

