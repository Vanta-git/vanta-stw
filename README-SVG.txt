# Vanta SVG build

`index.svg` wraps the original `index.html` in an XHTML iframe inside SVG.

This version intentionally uses an iframe instead of executing the original page
directly inside the SVG document. That gives the original Vanta code a real HTML
`document` and `document.body`, preventing errors such as:

`Cannot read properties of null (reading 'appendChild')`

All original folders and files from the supplied site ZIP are preserved.
