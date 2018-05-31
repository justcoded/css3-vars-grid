# CSS3 Variables Grid
Easy feature for faster building of grid of web-pages that based on CSS variables.

## How to use
Just add ``css3-vars-grid.css`` in your ``<head>``:

``<link rel="stylesheet" type="text/css" href="path/css3-vars-grid.css"/>``

## Customizing of the CSS3 Variables Grid
By default there are CSS-variables in ``css3-vars-grid.css``:

	:root {
		--grid-gutter-width-xs: 10px;
		--grid-gutter-width-sm: 10px;
		--grid-gutter-width-md: 15px;
		--grid-gutter-width-lg: 15px;
		--grid-gutter-width-xl: 15px;
		--container-max-width-sm: 540px;
		--container-max-width-md: 720px;
		--container-max-width-lg: 960px;
		--container-max-width-xl: 1140px;
	}

Where:

``--grid-gutter-width-*`` - padding between columns. Gets divided in half for the left and right.

``--container-max-width-*`` - it defines the maximum width of ``.container`` for different screen sizes.

It depends on width of screen:

* ``xs`` - for ``max-width: 575px``
* ``sm`` - for ``min-width: 576px``
* ``md`` - for ``min-width: 768px``
* ``lg`` - for ``min-width: 992px``
* ``xl`` - for ``min-width: 1200px``

You can change each of them by redefine in your custom CSS file.

## Browsers support
You can use the **_CSS3 Variables Grid_** in next browsers:

* Chrome 49+
* Firefox 31+
* Safari 9.1+
* EDGE 16+
* Safari Mobile 9.1+
* Chrome for Android 49+