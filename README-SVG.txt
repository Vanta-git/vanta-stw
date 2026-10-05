Vanta SVG build

index.svg is the SVG entry point. It contains a full-size XHTML iframe that loads index.html normally.
This keeps the original proxy/service-worker/backend paths working instead of putting the page in srcdoc.
The SVG uses a normal aspect ratio so it does not stretch/zoom the UI.
