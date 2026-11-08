# Poppy AR

Phone test page for the Poppy AR project: checks what the phone supports (WebGPU, WebXR AR, camera, speech)
and measures how fast small vision-language models (LFM2.5-VL-450M, SmolVLM-256M) run on-device in the browser.

Live page: https://dawidnec5.github.io/poppy-ar/

- `index.html` — the test page (Transformers.js 4.3.2 from jsDelivr, models from Hugging Face).
- `coi-serviceworker.js` — enables cross-origin isolation on GitHub Pages so WASM can use multiple threads
  (coi-serviceworker v0.1.7, MIT).
