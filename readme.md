Python Hypertext Markup
=======================

I've developed a hobby of developing prototypes of bad programming languages. PyHP is a fruit of that effort.

PyHP is a low performance fast development webapp  language. It might be good for prototyping or personal tool development.

Usage is simple, in an HTML file open a `<?` tag, code in python then close with a `?>` tag.

Use the `Page.write(String)` function to output inline into the HTML file.

	<html>
	<body>
	<b>
	<?
	Page.write("Hello world")
	?>
	</b>
	</body>
	</html>

Arguments (post and get) are available by the `Page.args` dict.


Any python files or packages you want to import can be stored in the "lib" directory
