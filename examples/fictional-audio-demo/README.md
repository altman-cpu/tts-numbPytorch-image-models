# Fictional audio demo

A dependency-free, consent-based browser demo. It speaks only a short fictional disclaimer after the user checks the consent box and presses **Play**. **Stop audio** cancels playback. There is no autoplay, recording, network request, account, or saved user data.

## Run locally

From the repository root:

```sh
python -m http.server 8000 --bind 0.0.0.0 --directory examples/fictional-audio-demo
```

Then open <http://localhost:8000>. Use a browser with speech synthesis enabled. No `npm install` is needed; this is a static HTML page using the browser's built-in speech synthesis.

This demo is standalone and is not part of the `timm` Python package.
