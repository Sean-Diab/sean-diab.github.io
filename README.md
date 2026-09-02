# Sean Diab — personal website

A static portfolio deployed with GitHub Pages at <https://sean-diab.github.io/>.

## Main files

- `index.html`: portfolio content, styles, metadata, and lightweight interaction scripts
- `profile_pic.jpeg`: full-resolution portrait used on the page and in social metadata
- `resume.pdf`: downloadable resume
- `reviser_edit_demo.mp4`: Reviser editing-trajectory demo
- `reviser_examples_300m.html` and `reviser_examples_100m.html`: self-contained interactive Reviser trajectory explorers
- `faceoff_shot_1.png` through `faceoff_shot_4.png`: native iOS and Android FaceOff screenshots

## Local preview

From the repository root, run:

```sh
python3 -m http.server 8000
```

Then open <http://localhost:8000/>.

## Deployment

The live site is served from the repository's GitHub Pages branch. Before publishing, verify the page locally, commit the intended files, and push the deployment branch.

An optional FaceOff overview video can be added later as `faceoff_demo.mp4`; its container remains hidden while the file is absent.
