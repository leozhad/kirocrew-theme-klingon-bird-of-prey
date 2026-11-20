# Kiro Crew theme: Klingon · Bird-of-Prey

An unofficial Kiro Crew theme modeled on the Klingon Bird-of-Prey bridge in *Star Trek III* to *VI* (1984 to 1991): Kruge's ship, the captured *Bounty*, Klaa's ship and Chang's.

- **Look:** Klaa's targeting display in *The Final Frontier*. A faint red triangle lattice behind the chat, a session list framed by glowing green sides, amber panel light for the text, orange target triangles for secondary text, code in the bronze octagonal housing of the bridge viewscreen.
- **Thinking indicator:** an orange target of lit triangles with an amber bracket closing on it.
- **Welcome mark:** the Klingon Empire emblem as the films show it, black prongs edged in gold on a pale disc ringed in gold, traced from the Klingon transmission at the start of *The Undiscovered Country*, with the Klingon phrase *Qapla'!* ("Success!") under it.
- **Screensaver:** after 15 minutes with no key press, click, scroll or touch, the targeting display fills the screen: green sides, the red lattice, orange glyph columns and corner triangles, the app's name drawn out of lit triangles with a bracket locking onto it, the red triangle indicator that sits above Chang's viewscreen, and *Qapla'!* in the lower right corner. Press a key or click to dismiss it; the click does not reach the app. The dashboard's nav, session list and chat header stay on top, so the display fills the area to their right. It does not run when the OS is set to reduce motion, and it stops after 30 minutes.
- **Desktop splash:** while the desktop app waits for its gateway, the same targeting display in the bronze housing, with *Qapla'!* in the lower right corner. It holds still when the OS asks for reduced motion.
- **Code:** code blocks, diffs and the file viewer use the `everforest-dark` scheme (green, orange, red and amber) in both modes.
- **Light mode:** the same as dark. The films have no light screens.
- **Type:** Chakra Petch, a free sans whose letters have cut corners, like the screen housings. The Klingon screens carry no Latin type, only Klingon glyphs, so there is no film face to match.
- **Shapes:** cut (bevelled) corners use CSS `corner-shape: bevel`, which Chrome, Edge and the desktop app draw. A browser without it shows rounded corners instead.
- **Glyphs:** the Klingon-style glyphs on the splash and the screensaver are original, made in code. They are decoration: they spell nothing, as the film graphics did not.
- **Sounds:** harsh, buzzy console tones when the theme turns on or off, when a reply arrives, on notifications, and when an approval waits, and a rising shimmer when the theme turns on (a nod to the decloak). Original sounds made in code. None is taken from the films. They stay silent under reduced motion and while sounds are muted.

Choosing this theme turns the screensaver on. The first time you pick it, Kiro Crew asks whether to play its sounds. Turn either off later under Settings → Display → Theme → Experience (Overlays for the screensaver, Sounds for the sounds).

Needs Kiro Crew 0.13.0 or newer; older versions refuse the pack.

Pick System under Settings → Display → Font Family to keep the OS font.

| Chat | Screensaver | Desktop splash | Welcome mark | First pick |
|---|---|---|---|---|
| ![Amber text on black over a faint red triangle lattice, the session list framed by glowing green sides, code in bronze bevelled housings, a green button](.github/screenshots/bird-of-prey-dark.png) | ![A bronze bevelled housing: a red triangle lattice in a trapezoid with glowing green sides, KIRO CREW drawn out of lit orange triangles, an amber bracket, orange glyph columns, a red triangle indicator above](.github/screenshots/bird-of-prey-screensaver.png) | ![Desktop splash: the Bird-of-Prey targeting display, green sides, a red lattice, KIRO CREW in lit orange triangles with a bracket](.github/screenshots/bird-of-prey-splash.jpg) | ![A new chat's welcome screen: the Klingon emblem, black prongs edged in gold on a pale disc, with Qapla'! under it, above an amber greeting and six starter cards](.github/screenshots/bird-of-prey-welcome.jpg) | ![The dialog "Enable Klingon · Bird-of-Prey experience?" with Sounds and Overlays checked, and Keep colors only and Save buttons](.github/screenshots/bird-of-prey-first-pick.jpg) |

## The two Klingon packs

| Repo | Films |
|---|---|
| [kirocrew-theme-klingon-k-tinga](https://github.com/leozhad/kirocrew-theme-klingon-k-tinga) | *Star Trek: The Motion Picture* (1979) |
| This one | *Star Trek III to VI* (1984 to 1991) |

## Install

1. Open Settings → Display → Theme.
2. Under **Install Theme**, choose **GitHub** and paste `https://github.com/leozhad/kirocrew-theme-klingon-bird-of-prey`.
3. Install, then pick **Klingon · Bird-of-Prey** in the Theme list.

To update, install the same URL again.

From a browser that is not on the gateway's machine (a phone, say), use a zip instead: on GitHub choose **Code → Download ZIP**, then in Install Theme set **Theme source** to **Zip file** and pick that file. Kiro Crew finds the pack inside the zip's one top-level folder.

## Use your own sounds

The sounds are WAV files in `audio/`, named in `audio/manifest.json`: `activate` and `deactivate` (the theme turns on or off), `received` (a reply arrives), `notify` (notifications) and `approval` (an approval waits). To play your own, clone or unzip this repo, replace any of those files with a sound of your own under the same name, and install that folder (**Local folder**) or a zip of it. Kiro Crew accepts WAV, MP3 or OGG; if you change the extension, change `src` in `audio/manifest.json` to match. Keep each file under 512 KB. Kiro Crew stops a sound after its `maxDuration` (at most 5 s for `activate`, 1 s for `received`, 2 s for the others). Do not edit the installed copy: reinstalling replaces it.

## Film evidence

Colours were measured on [TrekCore](https://movies.trekcore.com/gallery/) Blu-ray screencaps: the film's hue and saturation, with brightness set for contrast (body text at least 7:1, secondary text and status colours at least 4.5:1). The frames are not in this repo.

Sources: *The Search for Spock* and *The Voyage Home* 4K remaster Blu-ray (2021); *The Final Frontier* and *The Undiscovered Country* 4K remaster Blu-ray (2022). Bridge set as built for *The Voyage Home*: Jack T. Collis (design); backlit graphics: Michael Okuda; moving video displays: Video Images; in *The Final Frontier* it also carried production designer Herman Zimmerman's work ([Memory Alpha, Klingon Bird-of-Prey (2280s)](https://memory-alpha.fandom.com/wiki/Klingon_Bird-of-Prey_(2280s))).

| Colour | Film, frame | What it is | Film hue, sat |
|---|---|---|---|
| lattice | V 542 | the red triangle lattice of Klaa's targeting display | 2°, 1.00 |
| edge | V 542 | its glowing green sides | 137°, 0.92 |
| target | V 542 | the orange target and corner triangles | 20°, 0.98 |
| amber | V 681 | the amber backlit panel on Klaa's bridge | 37°, 0.69 |
| monitor | III 775 | the cyan Enterprise wireframe on Kruge's monitor | 197°, 0.92 |
| script | III 775 | the pink glyphs under it (saturation floor 40/255) | 324°, 0.31 |
| console | VI 1734 | the green-lit console blocks on Chang's bridge | 157°, 0.56 |
| panel | IV 409 | the red backlit console panels on the *Bounty* | 1°, 0.89 |
| bars | IV 409 | the orange bars on the same panels | 21°, 0.72 |
| indicator | VI 1749 | the red triangle indicator over Chang's viewscreen (value floor 60/255) | 358°, 0.83 |
| housing | III 775 | the bronze housing round Kruge's monitor (saturation floor 5/255) | 28°, 0.32 |

Shapes: the targeting display is a trapezoid, wide at the top, with the green bars along its slanted sides and a thin yellow-green line inside each (V 542). Orange triangles sit in its upper corners and orange glyphs run down the left side in short columns (542). The target is drawn out of lit lattice triangles, and a bracket closes on it (542, 543). Red stepped rails sit at the right (542). The viewscreen and monitor housings are bronze octagons, a rectangle with cut corners (III 775, VI 1749); a strip of red triangles, alternately up and down, sits above Chang's screen (VI 1749).

Type: none on the Klingon screens. The orange "60" countdown digits in III (frames 848, 869, 872) are the Enterprise's self-destruct, seen on a Klingon monitor, so they are not used. Chakra Petch, as above.

Emblem: see "The emblem" below. The amber backlit panel on Klaa's bridge (V 681) carries a red-orange mark, but it is out of focus and its two side arms both rise, so it is not a clear emblem; only its amber is used (as `amber`).

### The emblem

Frame: *The Undiscovered Country*, Chapter 1, frame 140 (the same graphic in 139, 147 and 150): the Klingon Empire emblem on the *Excelsior*'s viewscreen as the Klingon transmission comes in after Praxis. Memory Alpha's file "Klingon emblem.jpg" is the same shot ("The emblem of the Klingon Empire displayed on the USS Excelsior viewscreen in 2293"). It is the clearest emblem in the five films: full frame, sharp edges, flat colour.

What it shows: three separate black prongs, each with a gold edge, over a pale disc ringed in gold. The top prong is a long kite: a needle tip far above the disc, widest just below the ring, a point at the disc's centre. The lower left prong sweeps down and out to a hooked tip below the disc; the lower right prong sweeps out to the right, its tip a little above its base. The lower prongs' tips reach past the ring; their inner corners nearly meet under the top prong's point.

| Colour | What it is | Film hue, sat, value |
|---|---|---|
| prong | the black inside each prong (a warm near-black) | 5°, 0.29, 0.18 |
| gold | the prongs' edges and the ring | 31°, 0.62, 0.95 |
| disc | the pale disc | 282°, 0.08, 0.85 |

The emblem is a mark, not text, so it keeps the film's brightness as well. The build's frame check re-measures all three on the frame.

Trace: the frame was upscaled 2x and sharpened; the black was taken at half intensity between the black (value 0.18) and the gold or pale round it, and also as the dip between the two gold edges where the top prong narrows to its tip; the gold beyond the ring is everything that is not the red screen; the disc and the ring are circles fitted to the pale disc's edge and the ring's outer edge (radius 112.0 and 126.4 px, centre 886.0, 474.1). Each outline was then refitted as smooth cubic Bézier curves within 1.2 px of the trace (the top prong's left gold edge is one curve, within 1.6 px), sharp only at its corners (the prong tips, the kite's side points and the inner notches): 29 curve segments in all, where the first traced polygons had 122 points and showed the trace's bumps. The drawn prongs cover the frame's black with an IoU of 0.90 (0.91 before smoothing), and 95% of the pixels round the emblem fall in the same class (prong, gold, disc or screen) in the frame and in the drawing. The outline is kept as vector data; the frame is not stored.

Other appearances checked: *The Search for Spock*, Kruge's bridge (frames 104, 116, 117): a yellow triangular plaque on the wall with a red long prong, dark lower prongs and a green disc, as Memory Alpha describes the 2280s emblem; through the bridge haze it is too soft to trace or measure. *The Final Frontier*, frame 681: the panel above. *The Motion Picture*: none (see that section).

Both packs draw the frame-140 emblem in the frame-140 colours: no film gives the K't'inga a different one that a frame confirms.

### The phrase

*Qapla'!* ("Success!"), in Marc Okrand's spelling from *The Klingon Dictionary* (p. 171): capital Q, lowercase l, a straight apostrophe, then the exclamation mark. It sits under the emblem on the welcome mark, on each splash and on each screensaver, set in the pack's font. It is the only Klingon phrase in the packs; the new-chat greeting stays English, because Kiro Crew 0.13 gives a pack no way to change it.

Not used: the Enterprise wireframe on Kruge's monitor (III 775) is a Federation ship on a Klingon screen; the *Bounty*'s console inlays (IV 326, 331, 332) are Starfleet light-table graphics in the Klingon ship; Chang's console lamps (VI 1734, 1736, 1756) are physical buttons, not displays. The *Bounty*'s grey-brown viewport housing (IV 364, 401) matches the bronze measured in III and was not measured separately.

## Credits and licenses

See [`LICENSE.txt`](LICENSE.txt). The pack, its artwork, its glyph shapes and its sounds are MIT; the sounds are original, synthesized in code, and inspired by the films. The font, Chakra Petch, is under the SIL Open Font License 1.1.

Unofficial, non-commercial fan art. Star Trek, the Klingon emblem, the ships and related marks are trademarks of their owners (CBS Studios / Paramount). Not affiliated with or endorsed by them. This repo ships no film images and no film audio.
