![Haxe logo](template/haxe-logo.svg)

## Haxe Slides

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

---

## Presenting

#### Keyboard shortcuts

<table class="light-keys">
	<tbody>
		<tr>
			<td>
				<span class="key"><b>↑</b></span>,
				<span class="key"><b>←</b></span>,
				<span class="key">Pg Up</span>,
				<span class="key">k</span>
			</td>
			<td>Go to previous slide</td>
		</tr>
		<tr>
			<td>
				<span class="key"><b>↓</b></span>,
				<span class="key"><b>→</b></span>,
				<span class="key">Pg Dn</span>,
				<span class="key">Space</span>,
				<span class="key">j</span>
			</td>
			<td>Go to next slide</td>
		</tr>
		<tr>
			<td>
				<span class="key">Home</span>
			</td>
			<td>Go to first slide</td>
		</tr>
		<tr>
			<td>
				<span class="key">End</span>
			</td>
			<td>Go to last slide</td>
		</tr>
		<tr>
			<td>
				Number + <span class="key">Return</span>
			</td>
			<td>Go to specific slide</td>
		</tr>
		<tr>
			<td>
				<span class="key">b</span>&nbsp;/
				<span class="key">m</span>&nbsp;/
				<span class="key">f</span>
			</td>
			<td>Toggle blackout / mirrored / fullscreen mode</td>
		</tr>
		<tr>
			<td>
				<span class="key">c</span>
			</td>
			<td>Clone slideshow</td>
		</tr>
		<tr>
			<td>
				<span class="key">p</span>
			</td>
			<td>Toggle presenter mode</td>
		</tr>
		<tr>
			<td>
				<span class="key">t</span>
			</td>
			<td>Restart the presentation timer</td>
		</tr>
		<tr>
			<td>
				<span class="key">?</span>,
				<span class="key">h</span>
			</td>
			<td>Toggle this help</td>
		</tr>
	</tbody>
</table>
