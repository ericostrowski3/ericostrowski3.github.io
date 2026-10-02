# Eric Ostrowski's website

Source for [www.ericsco.de](https://www.ericsco.de), Eric Ostrowski's personal
website. The site currently displays a "rework in progress" landing page.

## Project files

- `index.html` — page content and structure.
- `style.css`, `variables.css`, and `icons.css` — styling.
- `assets/` — fonts and images.
- `favicon.svg` — site icon.
- `CNAME` — custom domain configuration.

## Local preview

The static page uses plain HTML and CSS. From the repository directory, start
a local server with Python 3:

```sh
python3 -m http.server 8000
```

Then open [localhost:8000](http://localhost:8000). Edit the HTML or CSS and
refresh the browser to see changes.
