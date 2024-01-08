# Caffè Beltrami template guide

This is a short guide on how to use the Caffè Beltrami template. A working example can be found under the `example` folder.

## For speakers

To use the template just copy all the content of the `src` folder into your project folder. Then, add `\usepackage{cb-style}` at the start of your project. Edit the file `info.csv` with your infos and add a photo of yours named `speaker-0.ext` (do not substitute `speaker` with your name). The supported extensions are the one natively supported by LaTeX, such as `.jpg`, `.jpeg`, `.png`, ecc.

## For organizers

It is possible to add a `preview` option to the template as follows
``` \usepackage[preview]{cb-style}```
In this way it is possible to preview the next talk infos. To do so, fill the file `preview.csv` with the correct data and add it to the project folder.
