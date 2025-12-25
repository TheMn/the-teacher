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

- Arthur_s_House

.. code-block:: json

   {
     "prompt": "Cinematic scene of a middle-aged man with salt-and-pepper hair walking toward a remote forest cabin, viewed from behind. The cabin resembles a small wooden lodge surrounded by dense pine trees, isolated and quiet. Autumn season with fallen leaves, muted orange and brown foliage, light mist drifting through the forest. The man wears a dark coat and walks alone on a narrow path, posture calm and deliberate. His hair is clearly salt-and-pepper in color. Natural lighting, soft overcast sky, realistic proportions, moody atmosphere, grounded science-fiction tone, no visible face.",
     "negative_prompt": "text, numbers, letters, signs, logos, watermarks, captions, UI elements, faces visible, front-facing person, multiple people, modern city elements, futuristic buildings, bright summer colors, snow, winter scenery, cartoon style, anime, painting, low resolution, blurry",
     "style": "cinematic realism",
     "camera": {
       "angle": "rear view, slightly elevated",
       "depth_of_field": "shallow, background softly blurred"
     },
     "lighting": "soft natural light with forest shadows and light mist diffusion",
     "color_palette": "muted browns, dark greens, soft grays, subtle amber highlights",
     "composition": "man centered in foreground, cabin partially visible ahead, framed by trees"
   }

- Arthur_Studied_Language

.. code-block:: json
   
   {
     "prompt": "The same middle-aged man now portrayed at around 30 years old, wearing glasses, fully immersed in studying. He sits at a cluttered wooden desk in a cozy, dimly lit room filled with stacks of books and scattered papers. His posture is focused, leaning slightly forward, eyes scanning a thick open book, with a faint warm lamp light illuminating his face. Dust particles float in the air, creating an atmospheric, cinematic scene. Realistic textures, soft shadows, photorealistic details, high-resolution, scholarly, introspective mood.",
     "negative_prompt": "text, watermark, logos, modern furniture, electronic devices, other people, cartoon style, anime, low quality, blurry, oversaturated colors, fantasy elements, exaggerated expressions",
     "camera_movement": "slow pan across the desk",
     "lighting": "warm desk lamp, soft ambient shadows",
   }

- Arthur_Teaches_The_Fabricator

.. code-block:: json
   
   {
     "prompt": "The same man now in his older version, positioned exactly like in the 30-ish scene, wearing his usual attire, teaching his knowledge to a sleek, black, human-sized monolith-like machine (attached photo), while looking and slightly leaning towards it",
     "negative_prompt": "text, watermark, logos, modern electronics, other humans, cartoon style, anime, low quality, blurry, fantasy elements, exaggerated expressions",
     "lighting": "warm desk lamp, soft ambient shadows",
   }

- Arthur_Stand_Walks_Toward_The_Fabricator

.. code-block:: json

   {
     "prompt": "Using the attached reference photos for accurate appearance, depict the same person in a realistic, cinematic scene. The person is calmly walking toward a modern device placed in the foreground, then stopping and quietly observing it for a few moments. Neutral body language, relaxed posture, natural facial expression. Soft ambient lighting, shallow depth of field, realistic textures, high detail, photorealistic style, eye-level camera angle, subtle motion implied, calm and contemplative mood.",
     "negative_prompt": "blurry, low resolution, exaggerated emotions, aggressive posture, smiling at camera, looking away from device, distorted anatomy, extra limbs, unrealistic proportions, overexposed, harsh shadows, cartoon, anime, illustration, painterly style, motion blur, noise, artifacts",
   }

- Fabricator_Blinking

.. code-block:: json

   {
     "prompt": "Close-up shot of the device only, centered in the same place but a closer frame, realistic and high-detail. The camera is completely steady. The device emits light in a clear sequential cycle: first completely off, then smoothly turning white, then off again, then blue, then off again, then red. cinematic lighting, realistic reflections, sharp focus, photorealistic style. Calm, controlled atmosphere.",
     "negative_prompt": "people, hands, faces, camera shake, motion blur, fast transitions, flickering, blinking lights, exaggerated glow, lens flare, overexposed, underexposed, noise, artifacts, low resolution, cartoon, anime, illustration, distorted geometry, tilted frame",
   }

- Almost_Failed_Mirror

.. code-block:: json

   {
     "prompt": "Depict the same person just after waking up, calmly walking toward the mirror. Slightly sleepy posture, relaxed body language. The person stops close to the mirror and looks into their own reflection quietly for a few moments. Natural morning light, soft shadows, realistic skin texture, neutral facial expression, cinematic realism, eye-level camera angle, calm and introspective mood.",
     "negative_prompt": "exaggerated expressions, smiling at camera, looking away from mirror, distorted reflection, unrealistic lighting, harsh shadows, messy framing, motion blur, camera shake, extra limbs, distorted anatomy, cartoon, anime, illustration, painterly style, low resolution, noise, artifacts",
   }
