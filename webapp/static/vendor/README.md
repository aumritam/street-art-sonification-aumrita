# Local eye-tracking assets

This directory vendors the browser runtime required by the optional eye-tracking mode so the installation does not depend on a CDN during use.

- `webgazer/webgazer.js`: WebGazer.js `3.5.3`, unmodified `dist/webgazer.js` from the official npm package.
- `webgazer/mediapipe/face_mesh/`: the MediaPipe Face Mesh files shipped inside the same WebGazer package. `app.js` points WebGazer at this folder through `params.faceMeshSolutionPath`.

WebGazer.js is distributed under the GNU General Public License v3 (see `webgazer/LICENSE.md`). MediaPipe is distributed under the Apache License 2.0.
