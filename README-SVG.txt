Vanta SVG build

index.svg is a thin fullscreen SVG wrapper around the normal index.html app.
The proxy continues running in normal HTML, avoiding SVG document-environment
problems.

To change the repository name/owner, edit vanta-config.js:
repoOwner
repoName
branch
repoUrl
rawUrl

The local proxy/backend files remain included, so changing the repository
configuration does not remove the working local backend.
