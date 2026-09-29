# Underwater Optics Bench

An interactive 3D lab for teaching underwater imaging, made for the OS207 *Light and imaging* lecture.

**Open the lab:** https://fabbiologia.github.io/underwater-optics-bench/

## What's in it

1. **Focus in air** – a thin lens on an optical bench. Move the focus, aperture and focal length and watch each subject's cone of light converge in front of, on or behind the sensor, with a simulated photo showing the blur.
2. **Behind the port** – a camera housing on a seagrass bed. Compare flat and dome ports: apparent distance and size, angle of view, colour fringing and the dome's virtual image.
3. **Light in water** – a cut-away water column. Surface reflection and refraction, Snell's window, colour loss with depth, a turbidity slider from clear ocean to turbid estuary, strobes, backscatter and white balance.

Tabs 2 and 3 include worksheets. Model answers are hidden behind a "Show model answers" button.

Link straight to a tab with `#focus`, `#port` or `#light` at the end of the address.

## Notes

- Everything is in one file, `index.html`. The 3D library ([three.js](https://threejs.org/) r128) loads from cdnjs, so the page needs an internet connection.
- It needs a current browser with WebGL 2. The water tab is demanding on older or low-power laptops.
- Water attenuation values are rounded approximations after Jerlov water types, for teaching.

## Licence

© 2026 Fabio Favoretto. This work is licensed under a [Creative Commons Attribution 4.0 International licence (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). You may share and adapt it for any purpose, including commercially, as long as you give appropriate credit, link to the licence and indicate if changes were made. The full legal text is in [LICENSE](LICENSE).

Suggested credit: *Underwater Optics Bench* by Fabio Favoretto, CC BY 4.0, https://fabbiologia.github.io/underwater-optics-bench/

[three.js](https://threejs.org/) is not part of this work. It is © the three.js authors, used under the MIT licence, and loaded from cdnjs.
