# HTML5ify-textmate

A Textmate Plugin that let you html5ify your HTML markup in one click.

## What does it do exactly?

In one word: Magic.

In some more words: It removes all trailing slashes (/) from your void elements (e.g. input, br, col) and removes type="text/javascript" and the CDATA-stuff form script tags, because they are obsolete and considered the standard in html5 or in the latter case, are not needed in HTML (the cdata is only needed in well-formed XML).