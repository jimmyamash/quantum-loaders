quantum-loaders
===============

Minimal CSS3 Loading Animations

Each loader can be called with their respective names/classes:

For all loaders, add class `quantum`, this will handle positioning.

Heartbeat:
`<div class="quantum heartbeat">`

Gooey:
`<div class="quantum gooey">`

Hypno:
`<div class="quantum hypno">`

Positioning is absolute by default, and can be set to relative by the user by using `quantum-r` instead of `quantum` as the initial class. Colors and sizes are static, but can also be modified externally.

@keyframes are cross-browser using -webkit, -moz, and static keyframes.
