# Scratch files

These files are used to generate most the images on the site. It's easier than raw files because you can edit them and re-export them later! All of the files that have `ai-` in front of them were auto-generated from these Illustrator files.

If you'd like to add a new file but don't know your way around Illustrator, that's okay - just create a normal `png` image and save it into the `assets` folder of the directory you're in.

## Editing an existing image and exporting changes

Open the appropriate file, make your edits, and then export using `File > Export > Export for Screens`, with the following options:

* **Scale:** 1x
* **Format:** PNG
* **Suffix:** None
* **Export to:** the appropriate folder (`lines.ai` goes to `lines/assets/`, etc)
* **Background Color:** Transparent (you'll need to click the little gear to find this option)

## Adding a new image

Open the appropriate file, then add a new artboard. Name the artboard (`Window > Artboards`, then double-click the new artboard in the list), make your drawing, then export using the instructions above.

## Creating new files

If you'd like to make your own Illustrator file, make sure your **filename matches the directory the files will go into**. `lines.ai` will export into `lines/assets/`, `legends.ai` will export into `legends/assets/`, etc.

## `process.jsx`

Is a script that goes through all of the `.ai` files and exports each artboard to the appropriate directories. You can run it if you'd like, but you don't really need to worry about it.