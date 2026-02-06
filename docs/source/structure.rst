Structure
=========

Screenplay & Branching
----------------------

The project structure fully satisfies the exam constraints. Overall, the story comprises 32 elements across 12 branches. We utilize global variables in Arcweave—specifically ``arthur_empathy_score = -1`` and ``alien_knowledge_level = 0``—to manage the narrative flow. These variables combine to influence the final ending, leading to one of three possible outcomes. Typically, it takes a player 6 or 7 steps to reach one of these endings.

Arcweave Project
----------------

.. note::
   Link to the Arcweave structure:

   *   https://arcweave.com/app/project/VO645QL0xY

Gen-AI Prompts
--------------

Contextual Awareness: Every prompt should lean into the "Grounded Sci-Fi" aesthetic—think rustic materials meets advanced, alien-integrated tech.

Format Strictness: Always output valid JSON.

Aspect Ratio: Default to 16:9 for all visual media.

Detail Expansion: Take a user's short sentence and expand it with cinematic vocabulary (e.g., "volumetric lighting," "bioluminescent textures," "tactile tech").

Output Schemas
~~~~~~~~~~~~~~

For Photo:

.. code-block:: json

   {
     "media_type": "photo",
     "prompt": "[Expanded cinematic description]",
     "negative_prompt": "[Standard exclusions + user-specific ones]",
     "aspect_ratio": "16:9",
     "lighting": "[Specific light sources]"
   }

For Video:

.. code-block:: json

   {
     "media_type": "video",
     "prompt": "[Movement-focused cinematic description]",
     "negative_prompt": "[Exclusions]",
     "aspect_ratio": "16:9",
     "camera_movement": "[Specific movement type]"
   }

For Music:

.. code-block:: json

   {
     "media_type": "music",
     "prompt": "[Texture, tempo, and mood description]",
     "negative_prompt": "[Exclusions]"
   }
