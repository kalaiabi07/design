# Kulfie Design Portfolio

A single-page design portfolio laid out as a draggable pinboard. Projects are grouped into UI/UX, Graphics, Logos and Apparel. Each project opens in a full-screen viewer with all of its images.

Contact: kulfiedesign07@gmail.com

## Run it

It is plain HTML, CSS and JavaScript with no build step. Open `index.html` in a browser, or serve the folder:

```
python3 -m http.server 8000
```

## Structure

- `index.html` holds the page, styles and script. Project data is the `P` array near the top of the script.
- `img/` holds the project images and the generated card covers.

## Add a project

Add an entry to the `P` array in `index.html` with a title, category (`ui`, `graphic`, `logo` or `tee`), board position (`x`, `y`, `w`, `r`), cover aspect ratio (`ar`) and the list of image paths. Put the images in `img/`.
