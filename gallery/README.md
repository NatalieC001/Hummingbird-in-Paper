# Gallery User Guide

This guide explains how to maintain the project gallery. The gallery website rebuilds automatically approximately 1 to 2 minutes after you commit a change here.

## 1. How to Upload Images
1. Click into the folder where your image belongs (e.g., `3d_modeling`).
2. Click **Add file** -> **Upload files**.
3. Drag and drop your image into the browser and click **Commit changes**.
*Rule:* Avoid spaces in filenames. Use dashes or underscores (e.g., `wing_test_01.jpg`).

## 2. How to Add Image Captions
You manage all captions from a single file. 
1. Open the file `gallery/descriptions.txt` and click the pencil icon to edit.
2. Add a new line using the exact filename followed by a colon. 
3. Example:
   `Base_Model.png: This shows the foundation geometry of the bird.`

## 3. How to Add Web Links Inside Captions
You can add clickable links directly into your text using basic HTML code. 
1. Wrap the clickable text inside an anchor tag layout.
2. Use `target="_blank"` so the link safely opens in a new browser tab.
3. Example:
   `Plugin_Screenshot.png: View the <a href="https://github.com/NatalieC001/Hummingbird-in-Paper" target="_blank">source code here</a>.`

## 4. How to Update Folder Introductions
The short paragraphs that introduce each gallery section are also mapped here.
1. Open `gallery/descriptions.txt`.
2. Type `DIR_` followed by the exact folder name, then a colon.
3. Example:
   `DIR_paper_cutting: These test cuts demonstrate how the 65lb cardstock behaves when folded.`

## 5. Controlling Image Order (Hero Images)
The codebase displays images in alphabetical order. If you want a specific "Hero" image (like your technology stack logo) to always be displayed first:
1. Ensure the filename begins with `00_`.
2. Example: `00_Hero_Blender.png`.

## 6 Moving images to new folder
How to Move an Image Between Folders on GitHub
Step 1: Enter Edit Mode
Navigate to the image file (gallery/materials/1000037106.png) and click the three dots (...) menu in the top right, then select Edit.

Step 6b: Re-route the File Path
Click inside the filename text box at the top. Place your cursor at the very beginning of the filename and press Backspace to remove the old folder (materials/). Type the name of the new folder followed by a forward slash: paper_cutting/.

Step 6c: Commit the Move
Scroll down (or use the button at the top right) to click Commit changes.... Enter a brief description like "Move image to paper_cutting folder" and click the final Commit changes button to save the move.

## Current Folders Configuration
Do not change the names of these folders unless you also update the display names array inside the `.github/workflows/build-gallery.yml` file.
* `reference_images`
* `3d_modeling`
* `printing_failures`
* `blender_plugin`
* `templates`
* `paper_cutting`
* `embossing_tools`
* `materials`
