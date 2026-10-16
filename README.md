# Underwater Optics Bench

An interactive 3D lab for teaching underwater imaging, made for the OS207 *Light and imaging* lecture.

**Open the lab:** https://fabbiologia.github.io/underwater-optics-bench/

## What's in it

1. **Hearing the spectrum** – every colour of light played as a note, 40 octaves lower, so pitch rises with the energy of each photon. Sweep from red to violet, compare red and blue, and extend into ultraviolet and infrared.
2. **Photons and water** – a sunlit column of water at molecular scale. Launch a ray of sunlight and watch the molecules absorb the red photons in the first few metres while blue travels on, so the light left turns blue with depth. Each photon's energy is compared with the steps of O–H vibration a water molecule can absorb.
3. **Focus in air** – a thin lens on an optical bench. Move the focus, aperture and focal length and watch each subject's cone of light converge in front of, on or behind the sensor, with a simulated photo showing the blur.
4. **Behind the port** – a camera housing on a seagrass bed. Compare flat and dome ports: apparent distance and size, angle of view, colour fringing and the dome's virtual image.
5. **Light in water** – a cut-away water column. Surface reflection and refraction, Snell's window, colour loss with depth, a turbidity slider from clear ocean to turbid estuary, strobes, backscatter and white balance.

Tabs 4 and 5 include worksheets for students. Model answers and teaching notes are not published here; they live in the lecturer's offline teaching guide.

Link straight to a tab with `#sound`, `#photons`, `#focus`, `#port` or `#light` at the end of the address. The first tab plays tones through the speakers, but only after you press a button or the keyboard.

## Notes

- Everything is in one file, `index.html`. The 3D library ([three.js](https://threejs.org/) r128) loads from cdnjs, so the page needs an internet connection.
- It needs a current browser with WebGL 2. The water tab is demanding on older or low-power laptops.
- Water attenuation values are rounded approximations after Jerlov water types, for teaching. The photons tab uses pure-water absorption after Pope and Fry (1997); its infrared values and overtone band strengths are approximate.

## Licence

© 2026 Fabio Favoretto. This work is licensed under a [Creative Commons Attribution 4.0 International licence (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). You may share and adapt it for any purpose, including commercially, as long as you give appropriate credit, link to the licence and indicate if changes were made. The full legal text is in [LICENSE](LICENSE).

Suggested credit: *Underwater Optics Bench* by Fabio Favoretto, CC BY 4.0, https://fabbiologia.github.io/underwater-optics-bench/

[three.js](https://threejs.org/) is not part of this work. It is © the three.js authors, used under the MIT licence, and loaded from cdnjs.
