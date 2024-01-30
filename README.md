# Simple Grid+

Lightweight (~2KB uncompressed) and responsive CSS grid & utility components for easier front-end development. Optionally includes typography as well.

Based on [Simple Grid](https://github.com/zachacole/Simple-Grid) originally created by Zach Cole.

## Components

### Grid

Simple Grid+ is a mobile-first 12-column CSS grid system to make developing responsive websites easy and fast.

All the code you need is simple and familiar. A parent container class contains the grid. Within the container are rows. Row classes denote rows of content, which can be filled with up to 12 columns. Columns must be nested within a row.

```HTML
<div class="container">
	<div class="row">
		<div class="col-3">
			<!-- This content will take up 3/12 (or 1/4) of the container -->
		</div>
		<div class="col-3">
			<!-- This content will take up 3/12 (or 1/4) of the container -->
		</div>
		<div class="col-6">
			<!-- This content will take up 6/12 (or 1/2) of the container -->
		</div>
	</div>
</div>
```

To control the sizing behavior, you can apply a breakpoint to your column classes (EX: `.col-6-sm`).
Not specifying a breakpoint is equal to using the medium breakpoint (EX: `.col-6-md`).

### Utility

- `left`: Aligns content to the left.
- `right`: Aligns content to the right.
- `center`: Centers content.
- `justify`: Applies the "justify" content alignment.
- `hidden-sm`
- `hidden-md`

### Breakpoints

- `sm`: 33.75em; // 540px
- `md`: 45em; // 720px
- `lg`: 60em; // 960px
n

### Typography

Note: typography is not included in the default Simple Gride+ CSS files and must be included seperately.

- `font-light`
- `font-regular`
- `font-heavy`

## Building

1. `npm i`
2. `npm run build`
