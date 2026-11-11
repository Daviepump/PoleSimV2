PoleSimulator_V2_Web

This folder contains a standalone web-hostable copy of the working V2 simulator.

Important:
- This folder is independent from the original Pole Simulator project.
- It does not overwrite or modify the original repository.
- It is intended to be uploaded to GitHub and hosted on GitHub Pages.

Files included:
- index.html
- vendor/ (Three.js and MediaPipe vendor assets)

How to test locally:
1. Open a terminal in this folder.
2. Run a local static server, for example:
   python -m http.server 8000
3. Open:
   http://localhost:8000/
4. Choose a local 360° MP4, enable the camera, calibrate, then press START.

GitHub Pages:
- Upload this entire folder to a GitHub repo as the Pages content, or use the folder as the root of a branch.
- Once published, open the GitHub Pages URL in a browser.
- Allow camera access when prompted.

This folder is meant for testing only. Nothing is pushed or published automatically.
