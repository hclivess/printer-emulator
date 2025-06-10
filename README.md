```

And here is the updated README file.


```markdown
# Historical Document Generator

## Overview

The Historical Document Generator is a browser-based tool designed to create authentic-looking historical documents. Users can add and manipulate text blocks and images, apply various "aging" effects like ink blots, character jitter, and text corruption, and place them on a variety of pre-designed or user-uploaded templates.

This entire application is self-contained in a single HTML file, requiring no backend or complex setup. It leverages modern web technologies like CSS for styling and the HTML Canvas API for a robust, pixel-perfect export feature.

## Features

* **Interactive Canvas:** Drag, resize, and rotate text and image elements directly on the document.

* **Rich Text Effects:** A suite of sliders allows for fine-tuned control over the look and feel of the text:

  * **Font:** Choose from a curated list of 12 historical and typewriter-style fonts.
  * **Size:** Adjust the font size of any text block.
  * **Corruption:** Introduce random, glitch-like characters to simulate degradation.
  * **Jitter:** Slightly offset each character for a less uniform, hand-typed appearance.
  * **Rotation:** Add subtle rotation to individual characters.
  * **Ink Saturation:** Control the opacity and faintness of the text.
  * **Blot:** Simulate ink blots and smudges for added realism.

* **Background Templates:**
  * Choose from several built-in document backgrounds (Ovation Invoice, Hotel Bill, Lined Paper, etc.).
  * **Upload your own image** to use as a custom template.

* **Project Management:**

  * **Save:** Save your entire project layout (including element positions, text content, and all style settings) to a local JSON file.
  * **Load:** Load a previously saved project file to continue your work.

* **High-Quality Export:**

  * **Export to PNG:** Generate a high-resolution PNG image of your final document. The export function uses a manual canvas rendering process to ensure what you see on screen is exactly what you get in the final file, with no cutoffs or alignment errors.

## How to Use

1. **Open the HTML File:** Simply open the `index.html` file in a modern web browser.

2. **Choose a Template:**
   * Use the "Background Template" dropdown to select a built-in base for your document.
   * Or, click the **"Upload Template"** button to choose your own image as a background.

3. **Add Content:**

   * Click **"Add Text Block"** to create a new piece of text.
   * Click **"Add Image"** to upload an image from your computer.

4. **Edit and Style:**

   * Click on any element to select it.
   * **Drag** the element to move it.
   * Use the **blue handle** (bottom-right) to resize it.
   * Use the **orange handle** (top-center) to rotate it.
   * **Double-click** a text block to edit its content. Click away when you are finished.
   * With a text block selected, use the sliders in the control panel to apply effects.

5. **Save, Load, or Export:**

   * Click **"Save Project"** to download a `.json` file of your work.
   * Click **"Load Project"** to upload and restore a saved `.json` file.
   * Click **"Export PNG"** to download the final document as a high-quality image.

This tool provides a simple yet powerful way to create visually interesting and historically-styled documents for creative projects, games, or fun.
