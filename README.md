# Portfolio

Hero prototype: a WebGL card deck with soft inertial scroll.

Single self-contained `index.html`, no dependencies. Covers are painted to
textures on a canvas, cards are subdivided planes bent in a vertex shader
(bow, curl, ripple), with chromatic aberration and grain in the fragment
shader. DOM fallback when WebGL is unavailable.

Live: https://vod123qwe.github.io/portfolio/
