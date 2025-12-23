The Teacher - Documentation
==========================

This repository contains the documentation for **"The Teacher"**, the final project for the "Media Content Production" University Course (Academic Year 2025–2026).

How to Maintain This Documentation
=================================

You can update this documentation in two ways: directly on GitHub (easiest for small text changes) or on your local computer (better for large changes).

Option 1: Quick Edits (GitHub UI)
--------------------------------

If you just need to add a link, fix a typo, or paste your Gen-AI prompts, you can do it right here in the browser.

1. Navigate to the ``docs/source/`` folder.
2. Click on the file you want to edit:

   * ``overview.rst``: The story synopsis.
   * ``structure.rst``: Screenplay, branches, Arcweave link, and Gen-AI prompts.
   * ``media.rst``: YouTube video links.

3. Click the **Pencil Icon** (Edit file) in the top right.
4. Make your changes.

   * **Heads up**: These files use **reStructuredText (.rst)** format. It cares about indentation and underlines (like ``====`` or ``----``). Try to follow the existing pattern.

5. Scroll down to **Commit changes**, write a short message (e.g., ``Added Arcweave link``), and click **Commit changes**.

**How to add a new page (e.g., "Characters"):**

1. Create a new file in ``docs/source/`` (e.g., ``characters.rst``) and add your content.
2. Open ``docs/source/index.rst``.
3. Add the filename (without ``.rst``) to the list under ``.. toctree::`` (ensure it is indented to match the others):

   .. code-block:: rst

      .. toctree::

         overview
         structure
         media
         characters

**Example:**

To add a YouTube video to ``media.rst``, open the file and change the placeholder:

.. code-block:: rst

   * `My New Video Title <https://youtube.com/...>`_

Option 2: Local Development (Advanced)
-------------------------------------

If you want to preview how the documentation looks before publishing, follow these steps on your computer.

**Prerequisites:**

* Python installed.

**Steps:**

1. **Clone the repository** to your machine.
2. **Install dependencies**:

   Open a terminal/command prompt in the project folder and run:

   .. code-block:: bash

      pip install -r docs/requirements.txt

3. **Build the documentation**:

   Navigate to the ``docs`` folder and run the build command.

   * **Mac/Linux**:

     .. code-block:: bash

        cd docs
        make html

   * **Windows**:

     .. code-block:: bat

        cd docs
        make.bat html

4. **View the result**:

   Open the generated file ``docs/build/html/index.html`` in your web browser.
