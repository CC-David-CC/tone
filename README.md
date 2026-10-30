# Tone.js system tool

An app can call `const Tone = await host.tools.loadTone()` to use the Tone.js
synthesis and scheduling API in the browser. Start audio in a user gesture with
`await Tone.start()`. An app owns and must dispose any synths, scheduled events,
or audio resources it creates. The library is lazy-loaded and has no standalone
window. Run `npm ci --prefix apps/system/tone --ignore-scripts` before building.
