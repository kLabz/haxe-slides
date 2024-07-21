# Haxe Slides

Haxe Presentations inspired by [hxslides](https://github.com/ncannasse/hxslides), with:

* Html generated from markdown thanks to [backslide](https://github.com/sinedied/backslide) / [Remark.js](https://github.com/gnab/remark)
* Light and dark theme
* Publishing through github pages

---

## Demo

Github pages host generated presentations for `.md` files in the repository:

* [Slides from README](https://klabz.github.io/haxe-slides/)
* [Light theme demo](https://klabz.github.io/haxe-slides/demo.html)
* [Dark theme demo](https://klabz.github.io/haxe-slides/demo-dark.html)

---

## Usage

Installation:

```sh
npm install # Install backslide
```

Live reload server when writing a presentation:

```sh
npm run serve # Then open http://localhost:8000/
```

Generate html files in `www` folder:

```sh
npm run export # Export .md presentations as html in www/ folder
```
