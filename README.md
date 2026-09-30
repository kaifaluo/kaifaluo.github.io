# Kaifa Luo — personal website

Source for https://kaifaluo.github.io/.

- `index.html`: homepage, styling, and publication lists.
- `images/`: profile photographs and retained research figures.
- `CNAME`: existing GitHub Pages domain configuration.

## Preview locally

Run `python3 -m http.server 8000` from this directory, then open
http://localhost:8000/ in a browser. No build step is required.
The page loads Tailwind CSS, Inter, and Lucide icons from external services.

## Updating publications

Edit the ordered lists in `index.html`. Keep published papers newest first;
the `reversed` attribute numbers each list automatically. Place preprints and
author-confirmed under-review work in the preceding section. Preserve author
order and link published titles to their DOI.

## Credits

Originally adapted from [Jon Barron's academic website template](https://github.com/jonbarron/jonbarron.github.io).
