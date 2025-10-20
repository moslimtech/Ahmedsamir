AR Hologram Test (Gold Glowing Image)
------------------------------------

Files:
- index.html         : Open this file in a browser (hosted via HTTPS or localhost) on your mobile to test AR.
- logo.png           : The image you provided (converted to PNG).

Quick test:
1. Upload the folder to GitHub Pages / Netlify, or run a local server:
   - python3 -m http.server 8000
   - open on your mobile: http://<PC-IP>:8000/index.html
2. Allow camera permission when the page asks.
3. Point the camera at the Hiro marker image:
   https://raw.githubusercontent.com/AR-js-org/AR.js/master/aframe/examples/marker-training/examples/hiro.png

Adjust material in index.html:
- emissive -> glow color (#ffd700 is gold)
- emissiveIntensity -> increase for stronger glow
- Width/height of plane to scale the displayed image.

Enjoy!
