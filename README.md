# Electronic Circuit AR (Hiro Marker)

This is a single-page GitHub Pages project. The 3D circuit is constructed in HTML with A-Frame primitives and JavaScript; no Blender or GLB file is required.

## Deploy to GitHub Pages

1. Create a GitHub repository, for example `electronic-circuit-hiro-ar`.
2. Upload `index.html` to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose branch `main` and folder `/ (root)`, then Save.
6. Wait for GitHub Pages to publish the site. The URL is usually:
   `https://YOUR-USERNAME.github.io/electronic-circuit-hiro-ar/`

## Use AR

- Open the HTTPS GitHub Pages URL on your phone.
- Allow camera access.
- Show the standard Hiro marker to the camera:
  https://raw.githubusercontent.com/AR-js-org/AR.js/master/data/images/hiro.png
- Keep the marker flat, well lit, and fully visible.
- The model is anchored to the Hiro marker.

## Notes

- Internet is required because A-Frame and AR.js are loaded from CDNs.
- AR.js marker tracking and camera access require a supported browser and HTTPS.
- If the camera does not start, try Chrome on Android or another compatible mobile browser, check camera permissions, and reload the page.
- The model is a stylized educational visualization, not a functioning electrical schematic.
