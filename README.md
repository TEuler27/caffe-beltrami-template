# Caffè Beltrami template guide

This is a short guide on how to use the Caffè Beltrami template. A working example can be found under the `example` folder.

## For speakers

### Basic usage

To use the template just copy all the content of the `src` folder into your project folder. Then, add `\usepackage{cb-style}` at the start of your project. Edit the file `info.csv` with your infos and add a photo of yours named `speaker-0.ext` (do not substitute `speaker` with your name). The supported extensions are the one natively supported by LaTeX, such as `.jpg`, `.jpeg`, `.png`, ecc.

### Required packages

The template require the following packages:
- `PTSansNarrow`
- `fontenc`
- `tikz`
- `tabularray`
- `ninecolors`
- `csvsimple-l3`
- `asmmath`

If you need to use one of them in your presentation consider not importing them, since they are already included by the template.

### Draft option

You can use the template with a draft option as follow
```
\usepackage[draft]{cbstyle}
```
This will prevent the template from building at each compilation the first three slides.

### Sections

You can organize the presentation in sections as usual. If you want to generate a section title page use the command `\sectionpage`. Math symbols in the section title are not supported.

### Colors

You can use the colors of the theme in your project with the following keywords:
- `giallo` for the yellow,
- `grigio` for the background color,
- `blu` for the dark blue,
- `celeste` for the light blue.

### Itemize

The itemize environment will automatically use a custom bullet.

### Theorems

Theorems environment will automatically use the theme color.

## For organizers

It is possible to add a `preview` option to the template as follows
```
\usepackage[preview]{cb-style}
```
In this way it is possible to preview the next talk infos. To do so, fill the file `preview.csv` with the correct data and add it to the project folder.
