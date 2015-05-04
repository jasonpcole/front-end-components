# Body Parts

## Inspired by Pea.rs - a spot for me to keep bits of markup and styling that I have found myself writing over and over. No more!

### Navigation

__Horizonal Nav - Links__

```HTML
<nav role="navigation">
	<ul>
		<li><a href="#">This is a link</a></li>
		<li class="active"><a href="#">Active Link</a></li>
		<li><a href="#">Lorem link</a></li>
		<li><a href="#">Dolor link two</a></li>
		<li><a href="#">Here is a link</a></li>
	</ul>
</nav>
```

```CSS
nav[role="navigation"] li {
	float: left;
	font-size: 14px;
	border-right: 1px solid #ddd;
	}
nav[role="navigation"] li:last-child {
	border-right: none;
	}
nav[role="navigation"] li a {
	float: left;
	padding: 0 10px;
	text-decoration: none;
	color: #999;
	border-radius: 4px;
	}
nav[role="navigation"] li a:hover,
nav[role="navigation"] li a:focus {
	color: #333;
	}
nav[role="navigation"] li a:active {
	color: #666;
	}
nav[role="navigation"] li.active a {
	font-weight: bold;
	color: #333;
	}
```

__Horizonal Nav - Buttons__

```HTML
<nav role="navigation">
	<ul>
		<li><a href="#">This is a link</a></li>
		<li class="active"><a href="#">Active Button</a></li>
		<li><a href="#">Lorem link</a></li>
		<li><a href="#">Dolor link two</a></li>
		<li><a href="#">Here is a link</a></li>
	</ul>
</nav>
```

```CSS
nav[role="navigation"] li {
	float: left;
	margin: 0 4px 0 0;
	font-size: 14px;
	}
nav[role="navigation"] li a {
	float: left;
	padding: 8px 12px;
	text-decoration: none;
	color: #fff;
	background: #bbb;
	-webkit-border-radius: 4px;
	-moz-border-radius: 4px;
	border-radius: 4px;
	}
nav[role="navigation"] li a:hover,
nav[role="navigation"] li a:focus {
	background: #999;
	}
nav[role="navigation"] li a:active {
	background: #888;
	}
nav[role="navigation"] li.active a {
	color: #fff;
	background: #666;
	}
```

__Pagination__

```HTML
<nav class="page">
	<ul>
		<li class="page-prev"><a href="#">← Prev</a></li>
		<li><a href="#">1</a></li>
		<li><a href="#">2</a></li>
		<li><a href="#">3</a></li>
		<li class="page-next"><a href="#">Next →</a></li>
	</ul>
</nav>
```

```CSS
nav.page ul {
	text-align: center;
	}
nav.page ul li {
	display: inline;
	margin: 0 4px 0 0;
	}
nav.page ul li a {
	padding: 3px 8px;
	font-size: 14px;
	font-weight: bold;
	border: 1px solid #ddd;
background: #fff;
	border-radius: 4px;
	}
nav.page ul li a:hover,
nav.page ul li a:focus {
	background: #f0f0f0;
	border-color: #ccc;
	}
nav.page ul li a:active {
	background: #fff;
	border-color: #ddd;
	}
```

__Breadcrumbs__

```HTML
<nav class="breadcrumb">
	<a href="#">This is a link</a> /
	<a href="#">Lorem link</a> /
	<a href="#">Dolor link two</a> /
	<a href="#">Here is a link</a> /
	<strong>Active Link</strong>
</nav>
```

```CSS
nav.breadcrumb {
	font-size: 14px;
	color: #ccc;
	}
nav.breadcrumb a {
	margin: 0 5px;
	text-decoration: none;
	color: #999;
	}
nav.breadcrumb a:first-child {
	margin-left: 0;
	}
nav.breadcrumb a:hover,
nav.breadcrumb a:focus {
	color: #333;
	}
nav.breadcrumb a:active {
	color: #666;
	}
nav.breadcrumb strong {
	margin-left: 5px;
	font-weight: bold;
	color: #333;
	}
```

__Breadcrumbs__

```HTML
<nav class="breadcrumb">
	<a href="#">This is a link</a> /
	<a href="#">Lorem link</a> /
	<a href="#">Dolor link two</a> /
	<a href="#">Here is a link</a> /
	<strong>Active Link</strong>
</nav>
```

```CSS
nav.breadcrumb {
	font-size: 14px;
	color: #ccc;
	}
nav.breadcrumb a {
	margin: 0 5px;
	text-decoration: none;
	color: #999;
	}
nav.breadcrumb a:first-child {
	margin-left: 0;
	}
nav.breadcrumb a:hover,
nav.breadcrumb a:focus {
	color: #333;
	}
nav.breadcrumb a:active {
	color: #666;
	}
nav.breadcrumb strong {
	margin-left: 5px;
	font-weight: bold;
	color: #333;
	}
```

### Lists

__Definition List__

```HTML
<dl>
	<dt>The title is here</dt>
	<dd>Lorem ipsum definition goes here dolor sit amet.</dd>
	<dt>The title is here</dt>
	<dd>Lorem ipsum definition goes here dolor sit amet.</dd>
	<dt>The title is here</dt>
	<dd>Lorem ipsum definition goes here dolor sit amet.</dd>
</dl>
```

```CSS
dl dt {
	font-size: 16px;
	font-weight: bold;
	line-height: 1.2;
	}
dl dd {
	margin: 0 0 10px 0;
	font-size: 14px;
	line-height: 1.4;
	color: #666;
	}
```

### Content

__Footer__

```HTML
<footer role="contentinfo">
	<nav role="navigation">
		<ul>
			<li><a href="#">This is a link</a></li>
			<li><a href="#">Active Link</a></li>
			<li><a href="#">Lorem link</a></li>
			<li><a href="#">Dolor link two</a></li>
			<li><a href="#">Here is a link</a></li>
		</ul>
	</nav>
	<p>Copyright © 2012 Company Co. All rights reserved.</p>
</footer>
```

```CSS
footer[role="contentinfo"] {
	padding: 15px 0 0 0;
	font-size: 14px;
	border-top: 1px solid #ddd;
	}
footer[role="contentinfo"] nav ul li {
	display: inline;
	margin: 0 10px 0 0;
	padding: 0 10px 0 0;
	font-weight: bold;
	border-right: 1px solid #ccc;
	}
footer[role="contentinfo"] nav ul li:last-child {
	margin: 0;
	padding: 0;
	border: none;
	}
footer[role="contentinfo"] p {
	margin: 10px 0;
	}
```



