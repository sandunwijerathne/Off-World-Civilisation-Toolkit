# Google Flow — Video Prompts (9:16 Vertical)
### Off-World Civilisation Toolkit · 50 concepts

Three shots per concept, ~8 seconds each, cut together into a ~24-second vertical reel.
Every shot tells Flow exactly how to use your uploaded reference images.

---

## Setup — do this once

**In Flow's settings panel:**

| Setting | Value |
|---|---|
| Model | Veo 3.1 (or the newest Veo available to you) |
| Aspect ratio | **9:16 (portrait)** |
| Outputs per prompt | 2–4 — pick the best take, discard the rest |
| Audio | On |

> If your Flow build does not offer 9:16 for the model you select, generate 16:9 and centre-crop.
> Every prompt below keeps the subject inside a centred vertical safe area so a crop still works.

**Assets to prepare per concept — two PNGs:**

1. **`<name>_render.png`** — your generated photoreal hero image of the machine. *This is the
   authority on what the machine looks like.*
2. **`<name>_blueprint.png`** — the cyanotype blueprint sheet, exported from the repo SVG.

The blueprint SVGs are 1400 × 1000 landscape. To use one as a 9:16 first frame, export at
2800 × 2000 and pad it onto a 1080 × 1920 prussian-blue canvas (around `#0b2545`), main view
centred, title block near the bottom. A browser screenshot, Inkscape, or any SVG-to-PNG
converter will do the export.

---

## Which Flow mode for which shot

| Shot | Flow mode | What you upload |
|---|---|---|
| **A — Blueprint ignition** | **Frames to Video** | First frame = **blueprint PNG**. Last frame = **render PNG**. |
| **B — Hero action** | **Ingredients to Video** | Ingredient 1 = **render PNG**, labelled with the machine name. Ingredient 2 = **blueprint PNG** (optional — holds detail accuracy). |
| **C — Payoff / scale** | **Ingredients to Video**, or **Extend** the Shot B clip in Scenebuilder | Same ingredients as Shot B. |

**Naming your ingredients matters.** When you add the render as an ingredient, label it with the
exact machine name used in the prompt (e.g. `LT-1 Ariadne surveyor`). Flow binds the prompt words
to the ingredient label — a mismatch is the commonest cause of the model inventing a different
machine.

---

## The reference-image contract

Every Shot B and C prompt below opens with this line. Do not delete it — it is what stops Veo
redesigning your hardware:

> *Reference image is the exact machine: match its geometry, proportions, colour, panel layout,
> antenna and boom placement, and stencilled markings precisely. Do not redesign, restyle, or
> add hardware that is not in the reference.*

Shot A prompts carry the equivalent instruction for the two frames.

---

## Universal negative prompt

Paste into Flow's negative-prompt field, or append to the prompt as `Avoid:`

```
on-screen text, subtitles, captions, watermarks, logos, UI overlays, gibberish lettering,
morphing geometry, melting hardware, warped panels, duplicated machines, cartoon style, anime,
illustration, plastic toy look, heavy chromatic aberration, shaky handheld camera, whip pans,
rapid cuts, people looking at camera, undescribed floating debris, fantasy elements,
glowing magic energy
```

Keep text out of the frame entirely — add captions in the editor using the hook line supplied
with each concept.

---

## Audio policy

Veo generates native audio. Two rules keep it consistent and physically honest across all 50:

- **In vacuum:** the audio is a *structure-borne* recording — sound conducted through the
  machine's own frame, as a contact microphone would hear it. No air, so no whoosh, no roar,
  no explosions.
- **No dialogue, no narration, no lyrics.** Voice-over goes on afterwards.

Each prompt carries its own audio line. Keep it.

---

## Assembling the reel in Scenebuilder

1. Generate Shots A, B and C separately. Keep the best take of each.
2. Add them to Scenebuilder in order A → B → C.
3. Trim Shot A so the reveal lands about 2.5 s in.
4. Overlay the hook line over Shot A, and the GitHub handle over the last second of Shot C.
5. Export 1080 × 1920.

Caption source: [`facebook-reels-captions.md`](facebook-reels-captions.md) — same concept numbering.

---
---

# Spacecraft & Space Journeys

## 01 · The Lagrange Loom

**Upload:** `lagrange_loom_blueprint.png` · `lagrange_loom_render.png`
**Ingredient label:** `LL-1 Aranea tether-deployer satellite`
**Hook:** *Every rocket throws away its road.*

**Shot A — Blueprint ignition** *(Frames to Video: blueprint → render)*
```
Vertical 9:16. Opens on a cyanotype engineering blueprint sheet filling the frame — deep
prussian-blue paper, fine white and cyan linework, faint drafting grid, monospaced title block
reading LL-1 ARANEA. The camera pushes slowly in on the side elevation of the tether-weaving
spacecraft. The white linework begins to glow and lift off the paper, drawing itself into three
dimensions; the drafting grid dissolves into the black of low Earth orbit and the blue curve of
the planet rises behind. The wireframe fills with real material — gold insulation foil, deep-blue
solar arrays, white radiator panels — until it becomes exactly the satellite in the final frame.
One continuous move, no cut, and the finished hardware does not morph. Audio: paper rustle, a
faint drafting-pen scratch, a low rising synth swell settling into deep vacuum hum. No dialogue.
```

**Shot B — Hero action** *(Ingredients to Video)*
```
Vertical 9:16. Reference image is the exact machine: match its geometry, proportions, colour,
panel layout, antenna and boom placement, and stencilled markings precisely. Do not redesign,
restyle, or add hardware that is not in the reference. The LL-1 Aranea tether-deployer satellite
holds station in low Earth orbit while a taut white braided tether spools steadily out of its
nadir face and runs down out of frame. A small cargo pod with a grapple fixture drifts in from
the lower left, cold-gas thrusters firing in short puffs, closing on the tether's capture claw.
Navigation strobes blink. The camera orbits slowly right around the spacecraft at fixed distance,
hard sunlight raking from upper left, Earth's terminator and night-side city lights sliding past
below. Audio: structure-borne — deep sub-bass hum, spool motor whine, thin metallic creak of
tether under load, faint telemetry chirps. No dialogue.
```

**Shot C — Payoff / scale** *(Ingredients to Video, or Extend Shot B)*
```
Vertical 9:16. Same satellite, matched exactly to the reference image. The camera pulls back
smoothly and fast, revealing the tether running kilometres downward until the spacecraft is a
bright speck against the blue limb of Earth. The captured cargo pod swings around the tether's arc
and releases, coasting away and upward, gaining speed in silence. Deep black space, sharp stars,
thin blue atmospheric glow. Audio: the hum thins to almost nothing as the camera retreats, one
clean low tone. No dialogue.
```

---

## 02 · The Magsail Cruiser

**Upload:** `magsail_cruiser_blueprint.png` · `magsail_cruiser_render.png`
**Ingredient label:** `M2P2 magsail demonstrator with 100 m superconducting hoop`
**Hook:** *A ship with no engine and no fuel tank.*

**Shot A — Blueprint ignition** *(Frames to Video: blueprint → render)*
```
Vertical 9:16. Opens on a cyanotype blueprint sheet filling the frame — prussian-blue paper,
white and cyan linework, drafting grid, monospaced title block. The camera pushes in on the drawn
circle of the superconducting hoop and its eight tether spokes. The linework ignites, glowing
white, and lifts off the page into three dimensions; the grid dissolves into black space with a
distant blue crescent Earth. The wireframe fills with real material — gold foil bus, white
cryocooler radiators, a slender silver ring — becoming exactly the spacecraft in the final frame.
One continuous move, no cut. Audio: paper rustle, drafting-pen scratch, a rising electrical tone
resolving into steady cryogenic hum. No dialogue.
```

**Shot B — Hero action** *(Ingredients to Video)*
```
Vertical 9:16. Reference image is the exact machine: match its geometry, proportions, colour,
panel layout, antenna and boom placement, and stencilled markings precisely. Do not redesign,
restyle, or add hardware that is not in the reference. The M2P2 magsail demonstrator hangs in high
Earth orbit. Current comes up in the hundred-metre superconducting hoop: the slender ring
brightens as it catches sunlight, frost flashes off the coil housing, and a barely visible bluish
plasma glow inflates outward into a vast translucent bubble around the ring. Small gas nozzles
near the hub emit soft puffs. The camera drifts slowly along the plane of the hoop from edge-on
toward three-quarter, the ring opening from a bright line into a full circle. Audio:
structure-borne — low cryocooler drone, a rising harmonic as the field energises, faint ionised
crackle, telemetry ticks. No dialogue.
```

**Shot C — Payoff / scale** *(Ingredients to Video, or Extend Shot B)*
```
Vertical 9:16. Same spacecraft, matched exactly to the reference image. Slow top-down view of the
full hoop against deep black space, Earth small and blue far below, emphasising high orbit. The
entire ring tilts a few degrees — tacking — the plasma bubble deforming with it, sunlight sweeping
around the cable. No thruster plume anywhere. Audio: a single sustained low tone, faint solar-wind
hiss. No dialogue.
```

---

## 03 · The Beam-Rider Interstellar Probe

**Upload:** `beam_rider_probe_blueprint.png` · `beam_rider_probe_render.png`
**Ingredient label:** `one-metre dielectric lightsail prototype with wafer spacecraft`
**Hook:** *The first starship will weigh less than a coin.*

**Shot A — Blueprint ignition** *(Frames to Video: blueprint → render)*
```
Vertical 9:16. Opens on a cyanotype blueprint sheet filling the frame — prussian-blue paper, fine
white linework, drafting grid, monospaced title block. The camera pushes in on the drawn circular
sail and its centre-mounted chip. The linework glows and lifts off the page into three dimensions;
the drafting grid dissolves into the soft white light of an aerospace cleanroom, and the wireframe
fills with real material — an iridescent membrane on a carbon-fibre hoop, held in a gloved hand —
becoming exactly the image in the final frame. One continuous move, no cut. Audio: paper rustle,
drafting-pen scratch, a rising tone resolving into cleanroom air-handler roar. No dialogue.
```

**Shot B — Hero action** *(Ingredients to Video)*
```
Vertical 9:16. Reference image is the exact object: match its geometry, proportions, colour and
markings precisely. Do not redesign or add hardware that is not in the reference. A researcher in
a white bunny suit and blue nitrile gloves slowly tilts the one-metre lightsail prototype under
cleanroom lighting. Rainbow interference patterns sweep across the impossibly thin dielectric
membrane as the angle changes, the researcher's silhouette faintly visible through it. At the
sail's centre the postage-stamp black silicon wafer spacecraft, with four camera apertures and
gold traces, stays rock steady on hair-thin tethers. Shallow depth of field on the membrane,
optical test bench soft behind. Audio: cleanroom air handling, faint suit-fabric rustle, a soft
equipment beep. No dialogue.
```

**Shot C — Payoff / scale** *(Ingredients to Video, or Extend Shot B)*
```
Vertical 9:16. Same objects, matched exactly to the reference image. Extreme macro slide across
the wafer spacecraft at the sail's centre — gold traces, four tiny lenses, the edge of a tether
attachment — then a slow rack focus past it to the vacuum chamber behind, where a red-orange laser
beam path glows through a viewport. Soft laboratory light, shallow depth of field throughout.
Audio: low chamber pump drone, a single relay click, faint fan hiss. No dialogue.
```

---

## 04 · The Hibernation Transit Pod

**Upload:** `hibernation_pod_blueprint.png` · `hibernation_pod_render.png`
**Ingredient label:** `Torpor Berth Trial Unit 01 hibernation capsule`
**Hook:** *The cheapest cargo you can send to Mars is a sleeping human.*

**Shot A — Blueprint ignition** *(Frames to Video: blueprint → render)*
```
Vertical 9:16. Opens on a cyanotype blueprint sheet filling the frame — prussian-blue paper, fine
white linework, drafting grid, monospaced title block. The camera pushes in on the drawn
longitudinal section of the hibernation berth. The linework glows and lifts off the page into
three dimensions; the grid dissolves into the cool light of a space-medicine laboratory, and the
wireframe fills with real material — matte white medical panels, a curved transparent canopy, a
contoured padded interior — becoming exactly the berth in the final frame. One continuous move,
no cut. Audio: paper rustle, drafting-pen scratch, a rising tone settling into a slow, calm
heart-rate monitor beep. No dialogue.
```

**Shot B — Hero action** *(Ingredients to Video)*
```
Vertical 9:16. Reference image is the exact machine: match its geometry, proportions, colour,
panel layout and markings precisely. Do not redesign or add hardware that is not in the reference.
Inside the Torpor Berth Trial Unit 01 a calm volunteer in a snug sensor suit lies still, eyes
closed. The curved transparent canopy lowers smoothly and seals. Fine frost patterns creep across
the cooling mattress and along the blue coolant tubing at the edges. On the monitor above, the
heart-rate trace slows visibly and the core-temperature readout steps down toward 33.4 C. An
articulated robotic care arm with an IV line adjusts a fraction and holds. The camera pushes in
slowly along the length of the capsule toward the occupant's face. Cool clinical lighting, shallow
depth of field. Audio: soft pneumatic seal hiss, coolant pump hum, a slowing monitor beep.
No dialogue.
```

**Shot C — Payoff / scale** *(Ingredients to Video, or Extend Shot B)*
```
Vertical 9:16. Same berth, matched exactly to the reference image. Slow overhead descent looking
straight down at the sealed capsule, the sleeping volunteer visible through frost-edged glass, the
vital-signs monitor glowing softly at the head end. The laboratory around it falls away into cool
shadow. Everything still. Audio: one sustained low pump tone, a distant monitor beep, room tone.
No dialogue.
```

---

## 05 · The Orbital Propellant Kelp Farm

**Upload:** `propellant_depot_blueprint.png` · `propellant_depot_render.png`
**Ingredient label:** `Orbital Depot Demo 1 cryogenic propellant station`
**Hook:** *Orbit's first real industry will be selling water.*

**Shot A — Blueprint ignition** *(Frames to Video: blueprint → render)*
```
Vertical 9:16. Opens on a cyanotype blueprint sheet filling the frame — prussian-blue paper, fine
white linework, drafting grid, monospaced title block. The camera pushes in on the drawn general
arrangement of the depot: central truss, tank cluster, sunshield. The linework glows and lifts off
the page into three dimensions; the grid dissolves into black space with Earth's blue curvature
rising below, and the wireframe fills with real material — gold-and-blue solar wings, white
spherical cryogenic tanks in gleaming insulation foil, a flat silver sunshield — becoming exactly
the station in the final frame. One continuous move, no cut. Audio: paper rustle, drafting-pen
scratch, a rising tone settling into deep vacuum hum and cryo-pump throb. No dialogue.
```

**Shot B — Hero action** *(Ingredients to Video)*
```
Vertical 9:16. Reference image is the exact station: match its geometry, proportions, colour,
panel layout and stencilled markings precisely. Do not redesign or add hardware that is not in the
reference. A cylindrical water-tanker spacecraft completes its final approach and soft-docks at
one end of the Orbital Depot Demo 1. The articulated fuel boom swings across and mates; frost
blooms along the cryogenic transfer lines and drifts away as fine ice crystals. A second upper
stage waits at the far docking port, navigation strobes blinking. The camera tracks slowly along
the truss from the tanker toward the tank cluster, sunlight raking from the left, Earth's cloud
tops sliding past below. Audio: structure-borne — docking latch clunk, cryo pump throb, valve
actuation clicks, deep hull hum. No dialogue.
```

**Shot C — Payoff / scale** *(Ingredients to Video, or Extend Shot B)*
```
Vertical 9:16. Same station, matched exactly to the reference image. The camera pulls back and up
to a wide three-quarter view of the whole depot against the blue curve of Earth — tanker docked at
one end, upper stage at the other, sunshield edge-on and bright. The solar wings track a few
degrees. Deep black space, a few sharp stars. Audio: hum thinning to a single low sustained tone,
a faint telemetry chirp. No dialogue.
```

---

# Off-World Civilisation Tools

## 06 · The Regolith Forge Crawler "Terramother"

**Upload:** `regolith_forge_crawler_blueprint.png` · `regolith_forge_crawler_render.png`
**Ingredient label:** `ISRU Build Demo 1 sinter-and-print unit`
**Hook:** *Cities should be waiting for their citizens when they arrive.*

**Shot A — Blueprint ignition** *(Frames to Video: blueprint → render)*
```
Vertical 9:16. Opens on a cyanotype blueprint sheet filling the frame — prussian-blue paper, fine
white linework, drafting grid, monospaced title block. The camera pushes in on the drawn side
elevation of the crawler and its sintering chamber. The linework glows and lifts off the page into
three dimensions; the grid dissolves into grey cratered lunar terrain under a black sky, and the
wireframe fills with real material — gold thermal foil, white radiators, dusty tracked feet, a
camera mast — becoming exactly the machine in the final frame. One continuous move, no cut.
Audio: paper rustle, drafting-pen scratch, a rising tone settling into a low mechanical grind and
the tick of cooling metal. No dialogue.
```

**Shot B — Hero action** *(Ingredients to Video)*
```
Vertical 9:16. Reference image is the exact machine: match its geometry, proportions, colour,
panel layout and stencilled markings precisely. Do not redesign or add hardware that is not in the
reference. The ISRU Build Demo 1 unit works on the lunar surface: its scoop arm lifts a load of
grey regolith and tips it into the insulated sintering chamber, whose viewport pulses faintly
orange. The robotic printing nozzle arm sweeps slowly sideways, laying a fresh course of fused
grey ceramic onto a low curved wall, print layers clearly visible. Dust lifts in slow lunar
ballistic arcs and falls straight back down — no billowing. The camera tracks low and left along
the wall, hard raking sunlight from one side, black sky above. Audio: structure-borne — servo
whine, granular hiss of pouring regolith, a deep furnace hum, relay clicks. No dialogue.
```

**Shot C — Payoff / scale** *(Ingredients to Video, or Extend Shot B)*
```
Vertical 9:16. Same machine, matched exactly to the reference image. The camera pulls back low
across the dust to reveal the finished curved wall running away from the unit, its printed courses
catching hard sunlight, a long black shadow stretching across the regolith. The blue marble of
Earth sits low on the black horizon behind. Audio: the furnace hum drops away to a slow ticking of
cooling ceramic, then near silence. No dialogue.
```

---

## 07 · The Cryo-Volatile Harvester

**Upload:** `cryo_harvester_blueprint.png` · `cryo_harvester_render.png`
**Ingredient label:** `Polar Ice Rover 01 lunar ice-mining rover`
**Hook:** *There are craters on the Moon where the Sun has never risen.*

**Shot A — Blueprint ignition** *(Frames to Video: blueprint → render)*
```
Vertical 9:16. Opens on a cyanotype blueprint sheet filling the frame — prussian-blue paper, fine
white linework, drafting grid, monospaced title block. The camera pushes in on the drawn side
elevation of the six-wheeled rover and its heated auger arm. The linework glows and lifts off the
page into three dimensions; the grid dissolves into the pitch blackness of a permanently shadowed
polar crater, and the wireframe fills with real material — gold foil, white panels, frost-glinting
structure — becoming exactly the rover in the final frame, lit only by its own floodlights. One
continuous move, no cut. Audio: paper rustle, drafting-pen scratch, a rising tone settling into a
deep cold drone and the hum of lamp ballasts. No dialogue.
```

**Shot B — Hero action** *(Ingredients to Video)*
```
Vertical 9:16. Reference image is the exact machine: match its geometry, proportions, colour,
panel layout and stencilled markings precisely. Do not redesign or add hardware that is not in the
reference. Inside a permanently shadowed lunar crater, the Polar Ice Rover 01 creeps forward on
six wheels, lit almost entirely by its own hard white floodlights, which carve sharp cones through
absolute darkness. The heated auger arm lowers and presses into grey icy regolith; a thin wisp of
sublimating vapour curls up and vanishes instantly. The LIDAR mast rotates. Frost glints on the
lower structure. Everything outside the beams is total black. The camera moves low and close
alongside the rover with a wide lens. Audio: structure-borne — drill motor grind, wheel gearbox
whine, a low power-unit drone, faint relay clicks. No dialogue.
```

**Shot C — Payoff / scale** *(Ingredients to Video, or Extend Shot B)*
```
Vertical 9:16. Same rover, matched exactly to the reference image. The camera rises and pulls back
until the rover is a small island of light in overwhelming blackness, its lamp cones the only
illumination for kilometres. Far above and behind, the crater rim catches a thin blade of raw
sunlight against a black star-flecked sky. Audio: the drone recedes, leaving a single low tone and
the faintest lamp-ballast hum. No dialogue.
```

---

## 08 · The Atmospheric Terraforming Seeder

**Upload:** `terraforming_seeder_blueprint.png` · `terraforming_seeder_render.png`
**Ingredient label:** `Contained Bio-Trial 01 Mars bioreactor and survey drone`
**Hook:** *Terraforming will not start with mirrors the size of continents.*

**Shot A — Blueprint ignition** *(Frames to Video: blueprint → render)*
```
Vertical 9:16. Opens on a cyanotype blueprint sheet filling the frame — prussian-blue paper, fine
white linework, drafting grid, monospaced title block. The camera pushes in on the drawn section
of the sealed bioreactor chamber. The linework glows and lifts off the page into three dimensions;
the grid dissolves into rusty Martian regolith beneath layered ochre canyon walls and a pale pink
sky, and the wireframe fills with real material — gold thermal insulation, transparent walls, a
faint green film of cyanobacteria inside — becoming exactly the station in the final frame. One
continuous move, no cut. Audio: paper rustle, drafting-pen scratch, a rising tone settling into
thin Martian wind and a soft pump. No dialogue.
```

**Shot B — Hero action** *(Ingredients to Video)*
```
Vertical 9:16. Reference image is the exact equipment: match its geometry, proportions, colour,
panel layout and markings precisely. Do not redesign or add hardware that is not in the reference.
At the foot of a sheltered Martian canyon, the camera pushes slowly in on the sealed
transparent-walled bioreactor. Inside, grow-lights brighten and a vivid green film of
cyanobacteria clings to Martian soil; condensation beads and runs down the inner glass. Beside it,
the lightweight solar survey drone's rotor begins to turn, red dust shivering off its long thin
wings. Thin wind moves fine dust across the regolith. Soft Martian daylight, shallow depth of
field on the green-tinged chamber. Audio: thin high wind, a small circulation pump, rotor spin-up,
a soft electronic chime. No dialogue.
```

**Shot C — Payoff / scale** *(Ingredients to Video, or Extend Shot B)*
```
Vertical 9:16. Same equipment, matched exactly to the reference image. The survey drone lifts off
in low Martian gravity, slow and floaty, kicking a small ring of red dust, and rises past the
camera. The camera tilts up to follow it against layered ochre canyon walls and a pale pink dusty
sky, the little green bioreactor left glowing below. Audio: rotor thrum thinning in the thin
atmosphere, wind, then quiet. No dialogue.
```

---

## 09 · The Planetary Power Loop

**Upload:** `power_loop_blueprint.png` · `power_loop_render.png`
**Ingredient label:** `SSP Demo 1 rectenna array and power satellite`
**Hook:** *A colony's most fragile organ is its power supply.*

**Shot A — Blueprint ignition** *(Frames to Video: blueprint → render)*
```
Vertical 9:16. Opens on a cyanotype blueprint sheet filling the frame — prussian-blue paper, fine
white linework, drafting grid, monospaced title block. The camera pushes in on the drawn beam path
linking satellite and ground rectenna. The linework glows and lifts off the page into three
dimensions; the grid dissolves into a grey cratered surface under a black sky, and the wireframe
fills with real material — fine metallic mesh panels on a low frame below, a gold-and-blue power
satellite above — becoming exactly the scene in the final frame. One continuous move, no cut.
Audio: paper rustle, drafting-pen scratch, a rising tone settling into a faint electrical
transformer hum. No dialogue.
```

**Shot B — Hero action** *(Ingredients to Video)*
```
Vertical 9:16. Reference image is the exact hardware: match its geometry, proportions, colour,
mesh pattern and stencilled markings precisely. Do not redesign or add hardware that is not in the
reference. The camera glides low across the fine metallic mesh of the SSP Demo 1 ground rectenna,
close enough to read the weave, past cable runs and a small instrument shed whose status beacon
begins to blink green as power arrives. Then the camera tilts up smoothly into the black sky to
find the compact solar-power satellite — bright gold-and-blue photovoltaic panel, flat phased-array
transmitter face aimed straight down — glinting in raw sunlight. A very faint haze marks the beam
path between them. Hard sunlight, sharp shadows on grey ground. Audio: transformer hum rising as
the beacon lights, a relay clunk, faint high-frequency whine. No dialogue.
```

**Shot C — Payoff / scale** *(Ingredients to Video, or Extend Shot B)*
```
Vertical 9:16. Same hardware, matched exactly to the reference image. Wide establishing shot
holding both the ground array in the foreground and the satellite as a bright point high in the
black sky, the faint beam haze connecting them. The Earth sits low and blue on the horizon. Long
sharp shadows stretch from the array. Audio: a steady low transformer hum, one soft telemetry
chirp. No dialogue.
```

---
---

# Black Holes & Extreme Physics

> Concepts 10 and 12 are far-horizon illustrations, not buildable near-term products. Keep that
> framing in the caption — it is the reason the catalogue is credible.

## 10 · The Ergosphere Siphon

**Upload:** `ergosphere_siphon_blueprint.png` · `ergosphere_siphon_render.png`
**Ingredient label:** `ergosphere siphon ring station around a spinning black hole`
**Hook:** *A spinning black hole is a flywheel with the mass of a star.*

**Shot A — Blueprint ignition** *(Frames to Video: blueprint → render)*
```
Vertical 9:16. Opens on a cyanotype blueprint sheet filling the frame — prussian-blue paper, fine
white linework, drafting grid, monospaced title block. The camera pushes in on the drawn ring
encircling a black disc. The linework glows and lifts off the page into three dimensions; the grid
dissolves into deep space and a brilliant warped accretion disk of orange-white plasma resolves
behind it, its light bent into a halo by gravitational lensing. The wireframe fills with real
material — a vast slender engineered ring studded with habitat modules and radiators — becoming
exactly the scene in the final frame. One continuous move, no cut. Audio: paper rustle,
drafting-pen scratch, a rising tone opening into an immense low subsonic drone. No dialogue.
```

**Shot B — Hero action** *(Ingredients to Video)*
```
Vertical 9:16. Reference image is the exact structure: match its geometry, proportions, module
spacing and colour precisely. Do not redesign or add structures that are not in the reference. The
camera arcs slowly around the colossal ring station orbiting a rapidly spinning black hole. The
black hole is a perfect black sphere ringed by a brilliant warped accretion disk of orange-white
plasma, lensed into a bright halo above and below, a faint blue-white relativistic jet along the
spin axis. Plasma filaments churn in the disk. The ring's mass-driver ports glow in sequence as
they fire. Distorted, lensed starfields wheel behind. Overwhelming scale, scientific-visualisation
realism. Audio: an immense sub-bass drone, slow harmonic beating, distant metallic resonance
through the ring structure. No dialogue.
```

**Shot C — Payoff / scale** *(Ingredients to Video, or Extend Shot B)*
```
Vertical 9:16. Same structure, matched exactly to the reference image. A thin stream of luminous
mass packages leaves the ring and arcs inward toward the swirling region near the black hole,
stretching and reddening as it goes, its path visibly bent. The camera holds still and lets the
scale do the work: the ring vast, the packages tiny, the hole absolute. Audio: the drone deepens,
one long descending tone. No dialogue.
```

---

## 11 · The Gravitational Lens Telescope Fleet

**Upload:** `gravlens_fleet_blueprint.png` · `gravlens_fleet_render.png`
**Ingredient label:** `SGL Pathfinder 1 deep-space telescope spacecraft`
**Hook:** *The largest telescope humanity will ever own is the Sun.*

**Shot A — Blueprint ignition** *(Frames to Video: blueprint → render)*
```
Vertical 9:16. Opens on a cyanotype blueprint sheet filling the frame — prussian-blue paper, fine
white linework, drafting grid, monospaced title block. The camera pushes in on the drawn side
elevation of the telescope and its coronagraph boom. The linework glows and lifts off the page into
three dimensions; the grid dissolves into a dense black starfield with the Sun reduced to an
intensely bright pinpoint, and the wireframe fills with real material — gold and black thermal
insulation, a high-gain dish, a radioisotope unit with fins — becoming exactly the spacecraft in
the final frame. One continuous move, no cut. Audio: paper rustle, drafting-pen scratch, a rising
tone settling into a vast, cold, near-silent hum. No dialogue.
```

**Shot B — Hero action** *(Ingredients to Video)*
```
Vertical 9:16. Reference image is the exact machine: match its geometry, proportions, colour,
insulation pattern, boom and antenna placement and stencilled markings precisely. Do not redesign
or add hardware that is not in the reference. The SGL Pathfinder 1 telescope spacecraft cruises
through the outer solar system. The camera drifts slowly along its length from the black
coronagraph disc on its extended boom, down the slender insulated body, to the radioisotope unit
at the rear. Micro-thrusters fire in tiny, precise puffs to hold pointing. The high-gain dish
rotates a few degrees to track a Sun that is now only an intensely bright star. Everything is cold,
dark and enormous; sharp stars fill the black. Audio: structure-borne — a faint reaction-wheel
whine, a soft thruster tick, deep silence underneath. No dialogue.
```

**Shot C — Payoff / scale** *(Ingredients to Video, or Extend Shot B)*
```
Vertical 9:16. Same spacecraft, matched exactly to the reference image. The camera pulls back
steadily until the telescope is a tiny glinting speck against an immense field of sharp stars, the
Sun a single bright point behind it, nothing else in frame. Absolute stillness, absolute distance.
Audio: the hum fades to nothing but one sustained sub-bass note. No dialogue.
```

---

## 12 · The Accretion-Disk Weather Buoy

**Upload:** `accretion_buoy_blueprint.png` · `accretion_buoy_render.png`
**Ingredient label:** `armoured accretion-disk sensor buoy and shielded relay craft`
**Hook:** *The most violent weather in the universe is wrapped around black holes.*

**Shot A — Blueprint ignition** *(Frames to Video: blueprint → render)*
```
Vertical 9:16. Opens on a cyanotype blueprint sheet filling the frame — prussian-blue paper, fine
white linework, drafting grid, monospaced title block. The camera pushes in on the drawn elongated
orbit dipping toward a disk edge. The linework glows and lifts off the page into three dimensions;
the grid dissolves into a swirling whirlpool of superheated orange-white and blue plasma around a
dark lensed void, and the wireframe fills with real material — small heavily armoured metallic
probes on glowing orbital paths — becoming exactly the scene in the final frame. One continuous
move, no cut. Audio: paper rustle, drafting-pen scratch, a rising tone opening into roaring
broadband plasma noise. No dialogue.
```

**Shot B — Hero action** *(Ingredients to Video)*
```
Vertical 9:16. Reference image is the exact hardware: match probe geometry, armour plating,
proportions and colour precisely. Do not redesign or add hardware that is not in the reference.
Seen from above the disk plane, a small armoured sensor buoy skims along its elongated orbit and
dips toward the turbulent outer edge of a brilliant accretion disk. Magnetic filaments twist and a
bright flare erupts along the disk as the probe passes, washing its hull in orange light. Twin thin
blue relativistic jets rise from the poles of the dark lensed void at the centre. The camera tracks
with the probe, matching its arc. Violent, luminous, immense. Audio: roaring broadband noise
rising and falling with the flare, a hard metallic ping through the probe's hull, telemetry bursts.
No dialogue.
```

**Shot C — Payoff / scale** *(Ingredients to Video, or Extend Shot B)*
```
Vertical 9:16. Same hardware, matched exactly to the reference image. The probe swings back out
away from the disk, trailing a faint data-link beam across the black to a larger shielded relay
craft holding station far out against the starfield. The camera pulls back to hold disk, probe and
relay in one frame, the sense of distance enormous. Audio: the roar recedes into a low seething
hiss, a clean data-burst chirp. No dialogue.
```

---
---

# Defense Systems

## 13 · The Kinetic Chaff Halo

**Upload:** `chaff_halo_blueprint.png` · `chaff_halo_render.png`
**Ingredient label:** `Guardian-1 station with kinetic chaff micro-satellite halo`
**Hook:** *Armour that thinks.*

**Shot A — Blueprint ignition** *(Frames to Video: blueprint → render)*
```
Vertical 9:16. Opens on a cyanotype blueprint sheet filling the frame — prussian-blue paper, fine
white linework, drafting grid, monospaced title block. The camera pushes in on the drawn spherical
halo of micro-satellites around a station. The linework glows and lifts off the page into three
dimensions; the grid dissolves into black space above Earth's blue curvature, and the wireframe
fills with real material — a modular station with solar arrays and radiators, surrounded by dozens
of small matte grey cubes — becoming exactly the scene in the final frame. One continuous move,
no cut. Audio: paper rustle, drafting-pen scratch, a rising tone settling into a low orbital hum
and scattered thruster ticks. No dialogue.
```

**Shot B — Hero action** *(Ingredients to Video)*
```
Vertical 9:16. Reference image is the exact hardware: match station and micro-satellite geometry,
proportions, colour and stencilled markings precisely. Do not redesign or add hardware that is not
in the reference. Dozens of fist-sized matte grey cube micro-satellites hold a loose spherical halo
around the Guardian-1 station in low Earth orbit, status LEDs blinking out of sync. On one side of
the halo, a group of them fires tiny gold thrusters in short precise puffs and slides into a denser
cluster, as if reacting to something off-frame; the rest hold formation. The camera moves slowly
through the sparse halo toward the station, cubes drifting past close to the lens with slight
motion blur. Hard sunlight from the left, Earth's cloud tops below. Audio: structure-borne — soft
cold-gas puffs, a low station hum, clipped digital coordination chirps. No dialogue.
```

**Shot C — Payoff / scale** *(Ingredients to Video, or Extend Shot B)*
```
Vertical 9:16. Same hardware, matched exactly to the reference image. The camera pulls back to a
wide three-quarter view of the whole halo — the station at its centre, dozens of tiny cubes
catching sunlight as a faint spherical shell of glints against the black, Earth's night side with
city lights below. Audio: the hum drops away, leaving scattered soft thruster ticks, then quiet.
No dialogue.
```

---

## 14 · The Mini-Magnetosphere Deflector

**Upload:** `magneto_deflector_blueprint.png` · `magneto_deflector_render.png`
**Ingredient label:** `Mag-Shield Demo 1 superconducting coil satellite`
**Hook:** *Earth has an invisible organ keeping you alive.*

**Shot A — Blueprint ignition** *(Frames to Video: blueprint → render)*
```
Vertical 9:16. Opens on a cyanotype blueprint sheet filling the frame — prussian-blue paper, fine
white linework, drafting grid, monospaced title block. The camera pushes in on the drawn circular
coil and its field lines. The linework glows and lifts off the page into three dimensions; the grid
dissolves into black space above Earth's blue curvature, and the wireframe fills with real material
— gold thermal foil, white radiators, a two-metre superconducting coil ring with frosted cryogenic
plumbing — becoming exactly the satellite in the final frame. One continuous move, no cut. Audio:
paper rustle, drafting-pen scratch, a rising electrical tone settling into cryocooler hum.
No dialogue.
```

**Shot B — Hero action** *(Ingredients to Video)*
```
Vertical 9:16. Reference image is the exact machine: match its geometry, proportions, colour,
panel layout, boom placement and stencilled markings precisely. Do not redesign or add hardware
that is not in the reference. The Mag-Shield Demo 1 satellite runs its field-inflation experiment.
Frost thickens visibly on the coil housing and cryogenic plumbing. Small gas-injection nozzles
around the coil release faint puffs, and a barely visible bluish plasma glow swells outward into a
soft translucent bubble around the ring. The particle-detector booms extend a little further and
hold. The camera pushes in slowly along the axis of the coil, so the ring opens toward the lens.
Hard sunlight from the left, Earth below. Audio: structure-borne — cryocooler drone, valve clicks,
a rising harmonic as the field inflates, faint ionised crackle. No dialogue.
```

**Shot C — Payoff / scale** *(Ingredients to Video, or Extend Shot B)*
```
Vertical 9:16. Same satellite, matched exactly to the reference image. The camera pulls back to a
three-quarter wide view: the small spacecraft, the frost-white coil, and the faint plasma bubble
around it, held against the vast blue curve of Earth and deep black space. The bubble shimmers
once and steadies. Audio: the harmonic settles to a single sustained tone, faint telemetry chirps.
No dialogue.
```

---

## 15 · The Asteroid Herder

**Upload:** `asteroid_herder_blueprint.png` · `asteroid_herder_render.png`
**Ingredient label:** `Gravity Tractor PDCO deep-space spacecraft`
**Hook:** *Planetary defense is the one weapon system every nation wants its rivals to have.*

**Shot A — Blueprint ignition** *(Frames to Video: blueprint → render)*
```
Vertical 9:16. Opens on a cyanotype blueprint sheet filling the frame — prussian-blue paper, fine
white linework, drafting grid, monospaced title block. The camera pushes in on the drawn
spacecraft and the canted thruster geometry beside an asteroid outline. The linework glows and
lifts off the page into three dimensions; the grid dissolves into deep black space with a dark
cratered asteroid resolving at the left, and the wireframe fills with real material — gold and
black insulation, enormous deep-blue solar wings, angled ion thrusters — becoming exactly the
spacecraft in the final frame. One continuous move, no cut. Audio: paper rustle, drafting-pen
scratch, a rising tone settling into a steady low ion-drive hum. No dialogue.
```

**Shot B — Hero action** *(Ingredients to Video)*
```
Vertical 9:16. Reference image is the exact machine: match its geometry, proportions, colour,
solar-wing size, thruster angles, antenna placement and stencilled markings precisely. Do not
redesign or add hardware that is not in the reference. The Gravity Tractor spacecraft holds station
a short distance off a rugged grey near-Earth asteroid. Its ion thrusters glow steady blue, canted
outward so their faint exhaust plumes point away from the rock and never touch it. The huge
deep-blue solar wings track sunlight a few degrees. The asteroid's cratered surface fills the left
of frame, lit hard from one side, rotating almost imperceptibly. The camera drifts slowly through
the empty gap between craft and asteroid — nothing connects them but gravity. Audio:
structure-borne — a smooth low ion-drive hum, reaction-wheel whine, occasional thruster ticks.
No dialogue.
```

**Shot C — Payoff / scale** *(Ingredients to Video, or Extend Shot B)*
```
Vertical 9:16. Same spacecraft, matched exactly to the reference image. The camera pulls back to
show the whole asteroid and the small bright spacecraft hovering beside it, holding its gap, blue
plumes angled harmlessly into the void. Pure black space, dense sharp stars, a small distant Sun.
Nothing dramatic happens — that is the point. Audio: a single steady low hum, one telemetry chirp.
No dialogue.
```

---

## 16 · The Directed-Energy Debris Broom

**Upload:** `debris_broom_blueprint.png` · `debris_broom_render.png`
**Ingredient label:** `Orbital Debris Remediation Test Range laser facility`
**Hook:** *Orbit is filling with shrapnel moving ten times faster than a rifle bullet.*

**Shot A — Blueprint ignition** *(Frames to Video: blueprint → render)*
```
Vertical 9:16. Opens on a cyanotype blueprint sheet filling the frame — prussian-blue paper, fine
white linework, drafting grid, monospaced title block. The camera pushes in on the drawn beam path
rising from a dome toward a debris fragment. The linework glows and lifts off the page into three
dimensions; the grid dissolves into a star-filled high-desert night sky, and the wireframe fills
with real material — an observatory dome open to the sky, a tracking telescope on a robotic mount,
lit equipment sheds — becoming exactly the facility in the final frame. One continuous move,
no cut. Audio: paper rustle, drafting-pen scratch, a rising tone settling into night desert wind
and a chiller fan. No dialogue.
```

**Shot B — Hero action** *(Ingredients to Video)*
```
Vertical 9:16. Reference image is the exact facility: match dome shape, telescope mount, building
layout, signage and colour precisely. Do not redesign or add structures that are not in the
reference. On a high desert mountaintop at night, the open observatory dome rotates a few degrees
with a low grinding hum. A thin, crisp green-cyan laser beam snaps on and fires in rapid pulses
straight up into a star-filled sky, scattering faintly in the thin high-altitude air, tracking a
point far overhead. Beside it, the precision tracking telescope slews smoothly to follow the same
point. Interior lights glow in the equipment sheds. Long-exposure astrophotography look, deep
starry sky with the Milky Way, cool moonlight on the terrain. Audio: dome drive grind, the sharp
staccato tick of a pulsed laser, chiller fans, desert wind. No dialogue.
```

**Shot C — Payoff / scale** *(Ingredients to Video, or Extend Shot B)*
```
Vertical 9:16. Same facility, matched exactly to the reference image. The camera tilts up from the
dome along the green-cyan beam into a dense field of stars, the beam thinning to a needle and
losing itself against the Milky Way. Far overhead, one tiny point of light shifts a fraction.
Audio: pulse ticks fading under rising wind, then a clean silence. No dialogue.
```

---
---

# Weaponry (Conceptual)

> Concepts 17 and 18 are deliberately **not** hardware glamour shots. The source studies frame them
> as an arms-control museum exhibit and a policy illustration. Keep that framing — it is the whole
> argument.

## 17 · The Hypervelocity Rail Interceptor

**Upload:** `rail_interceptor_blueprint.png` · `rail_interceptor_render.png`
**Ingredient label:** `orbital interceptor exhibition model under glass`
**Hook:** *In orbit, speed is the explosive.*

**Shot A — Blueprint ignition** *(Frames to Video: blueprint → backlit exhibit panel render)*
```
Vertical 9:16. Opens on a cyanotype principle schematic filling the frame — prussian-blue paper,
fine white linework, drafting grid, monospaced title block. The camera pushes in slowly. Instead
of becoming hardware, the schematic recedes and resolves into a large backlit wall panel in a
museum gallery, the same blue drawing now glowing behind glass beneath a heading panel, with warm
gallery spotlights raking across a polished concrete floor and a plinth in the foreground. One
continuous move, no cut. Audio: paper rustle, drafting-pen scratch, a rising tone resolving into
quiet gallery room tone and distant footsteps. No dialogue.
```

**Shot B — Hero action** *(Ingredients to Video)*
```
Vertical 9:16. Reference image is the exact exhibit: match the model's sculptural form, plinth,
vitrine, wall panel layout and gallery architecture precisely. Do not redesign or add objects that
are not in the reference. A slow dolly move past a stylised, deliberately simplified scale model of
a conceptual orbital interceptor under glass on a plinth — abstract matte grey and gold, a long
slender rail structure and solar panels, unmistakably a model rather than working hardware. Warm
gallery spotlights throw deep shadows; reflections slide across the vitrine glass as the camera
passes. Behind it, the backlit cyanotype schematic panel glows. Two visitors stand reading,
unhurried, seen from behind. Architectural photography style, shallow depth of field on the model,
sombre and thoughtful. Audio: gallery room tone, soft footsteps on concrete, a faint HVAC hum.
No dialogue.
```

**Shot C — Payoff / scale** *(Ingredients to Video, or Extend Shot B)*
```
Vertical 9:16. Same exhibit, matched exactly to the reference image. The camera leaves the model
and pushes slowly into the adjacent backlit infographic panel showing an expanding debris cloud
spreading around Earth, until the spreading cloud fills the frame. A visitor's silhouette crosses
the light. Audio: room tone and one set of receding footsteps, then near-silence. No dialogue.
```

---

## 18 · The Dazzler Constellation

**Upload:** `dazzler_constellation_blueprint.png` · `dazzler_constellation_render.png`
**Ingredient label:** `split-frame orbital policy illustration`
**Hook:** *The most dangerous moment in an orbital standoff is the choice between nothing and destruction.*

**Shot A — Blueprint ignition** *(Frames to Video: blueprint → editorial illustration render)*
```
Vertical 9:16. Opens on a cyanotype principle schematic filling the frame — prussian-blue paper,
fine white linework, drafting grid, monospaced title block. The camera pushes in slowly and the
drawing desaturates and resolves into an editorial illustration of one orbital scene above a curved
blue Earth, divided by a thin vertical line into two contrasting halves. One continuous move,
no cut, no hardware close-ups. Audio: paper rustle, drafting-pen scratch, a rising tone settling
into a muted, serious low drone. No dialogue.
```

**Shot B — Hero action** *(Ingredients to Video)*
```
Vertical 9:16. Reference image is the exact composition: match the split-frame layout, the dividing
line, the palette and the two halves precisely. Do not redesign or add elements that are not in the
reference. A slow lateral pan across a single orbital scene above curved blue Earth. On one side:
the aftermath of a destructive anti-satellite strike — a shattered satellite and an expanding cloud
of hundreds of glinting fragments drifting apart along the orbit, cold and chaotic, faint fragment
trails wrapping the planet. The camera crosses the thin dividing line. On the other side: an
intact, undamaged satellite in darkness, its camera aperture briefly washed in soft light and then
clear again, everything about it untouched, calm and orderly, no fragments anywhere. Muted serious
palette, documentary realism. Audio: a low uneasy drone over the fragment side, resolving into a
single clean sustained tone over the intact side. No dialogue.
```

**Shot C — Payoff / scale** *(Ingredients to Video, or Extend Shot B)*
```
Vertical 9:16. Same composition, matched exactly to the reference image. The camera pulls back so
both halves sit in one frame against the curve of Earth: permanent debris on one side, a working
satellite on the other, the dividing line down the centre. Everything holds still. Audio: the two
tones settle into one quiet chord, then silence. No dialogue.
```

---
---

# AI Robots

## 19 · The Myrmidon Swarm

**Upload:** `myrmidon_swarm_blueprint.png` · `myrmidon_swarm_render.png`
**Ingredient label:** `Hull Inspector 07 six-legged hull crawler`
**Hook:** *A ship's hull should heal like skin.*

**Shot A — Blueprint ignition** *(Frames to Video: blueprint → render)*
```
Vertical 9:16. Opens on a cyanotype blueprint sheet filling the frame — prussian-blue paper, fine
white linework, drafting grid, monospaced title block. The camera pushes in on the drawn plan view
of the six-legged crawler. The linework glows and lifts off the page into three dimensions; the
grid dissolves into the white multi-layer insulation and metal panelling of a space-station hull,
and the wireframe fills with real material — a flat matte-white body, a camera stalk, six
articulated legs with wide grip pads — becoming exactly the robot in the final frame. One
continuous move, no cut. Audio: paper rustle, drafting-pen scratch, a rising tone settling into
tiny servo clicks and a low hull hum. No dialogue.
```

**Shot B — Hero action** *(Ingredients to Video)*
```
Vertical 9:16. Reference image is the exact robot: match its body shape, leg count and articulation,
grip pads, camera stalk, antenna, colour and stencilled markings precisely. Do not redesign or add
hardware that is not in the reference. Extreme macro: the hand-sized Hull Inspector 07 crawler
walks slowly across the exterior hull panel of a space station, six delicate legs placing and
releasing their wide textured grip pads one at a time on the quilted white insulation. Its camera
stalk swivels and fixes on a small micrometeoroid pit in the panel nearby; the robot changes course
toward it and stops over the damage. A status LED pulses. Hard raking sunlight throws a sharp
articulated shadow across the hull. Shallow depth of field, blue Earth soft behind. Audio:
structure-borne — tiny servo whirrs, faint pad-release taps, a low hull resonance. No dialogue.
```

**Shot C — Payoff / scale** *(Ingredients to Video, or Extend Shot B)*
```
Vertical 9:16. Same robot, matched exactly to the reference image. The camera pulls back off the
hull to reveal several identical crawlers spread across the station's white panels, each moving
independently on its own errand, tiny against the structure, with the blue curve of Earth and cloud
tops beyond. Audio: the servo sounds multiply into a soft scattered ticking, then thin out.
No dialogue.
```

---

## 20 · The Deep-Down Cryobot

**Upload:** `cryobot_blueprint.png` · `cryobot_render.png`
**Ingredient label:** `Subglacial Access Probe sterile melting probe`
**Hook:** *Under Europa's ice there is an ocean holding twice the water of every sea on Earth.*

**Shot A — Blueprint ignition** *(Frames to Video: blueprint → render)*
```
Vertical 9:16. Opens on a cyanotype blueprint sheet filling the frame — prussian-blue paper, fine
white linework, drafting grid, monospaced title block. The camera pushes in on the drawn
longitudinal section of the melting probe. The linework glows and lifts off the page into three
dimensions; the grid dissolves into blue-white Antarctic ice under a low golden polar sun, and the
wireframe fills with real material — a slender matte titanium probe with a rounded dark nose cone
and a fine tether spooling from its top — becoming exactly the probe in the final frame. One
continuous move, no cut. Audio: paper rustle, drafting-pen scratch, a rising tone settling into
polar wind and a generator drone. No dialogue.
```

**Shot B — Hero action** *(Ingredients to Video)*
```
Vertical 9:16. Reference image is the exact equipment: match probe geometry, proportions, colour,
tether reel, winch frame and site layout precisely. Do not redesign or add equipment that is not in
the reference. On the Antarctic ice sheet at low sun, the slender titanium melting probe hangs
vertically over a narrow, perfectly round meltwater hole in blue-white ice and begins to descend,
its fine communications tether paying steadily off the reel. Frost dusts the probe body. Two
scientists in heavy red polar gear and clean-room gloves steady it with gloved hands, breath
fogging in the cold air. Wind moves loose snow across packed sastrugi. Long blue shadows. Audio:
winch motor whine, cable creak, wind, generator drone, muffled crunch of boots on snow. No dialogue
or speech.
```

**Shot C — Payoff / scale** *(Ingredients to Video, or Extend Shot B)*
```
Vertical 9:16. Same site, matched exactly to the reference image. The camera pulls back and rises
to show the whole field camp — the orange shelter, the sterile handling tent, the winch frame, the
tiny figures — as a scatter of colour on a flat white horizon under a low golden polar sun, the
probe's hole a single dark point. Audio: wind takes over completely, the generator drone thinning
to nothing. No dialogue.
```

---
---

# Materials, Habitats & Human Factors

## 21 · The Regolith Sinter Dome

**Upload:** `sinter_dome_blueprint.png` · `sinter_dome_render.png`
**Ingredient label:** `ISRU Pad Unit 01 microwave sintering crawler`
**Hook:** *The first real lunar building will not be delivered. It will be baked in place.*

**Shot A — Blueprint ignition** *(Frames to Video: blueprint → render)*
```
Vertical 9:16. Opens on a cyanotype blueprint sheet filling the frame — prussian-blue paper, fine
white linework, drafting grid, monospaced title block. The camera pushes in on the drawn side
elevation of the tracked crawler and its microwave applicator head. The linework glows and lifts
off the page into three dimensions; the grid dissolves into grey lunar regolith under a black
star-flecked sky, and the wireframe fills with real material — a boxy white-and-grey dust-caked
body, heavy black treads, gold foil bays, an angled solar array — becoming exactly the machine in
the final frame. One continuous move, no cut. Audio: paper rustle, drafting-pen scratch, a rising
tone settling into a deep track rumble. No dialogue.
```

**Shot B — Hero action** *(Ingredients to Video)*
```
Vertical 9:16. Reference image is the exact machine: match its geometry, proportions, colour, track
design, applicator head placement and stencilled markings precisely. Do not redesign or add
hardware that is not in the reference. The ISRU Pad Unit 01 crawls slowly forward across the grey
lunar surface, its rectangular microwave applicator head riding just above the ground at the rear.
Directly beneath the head the loose powdery regolith darkens, slumps and fuses into a smooth glassy
surface, the boundary between fused pavement and loose dust sharp and clean. Dust disturbed by the
treads rises in slow lunar arcs and drops straight back. The camera tracks low and level alongside
the machine at ground height. Hard raking low sunlight, long black shadow. Audio: structure-borne —
deep track rumble, gearbox whine, a steady magnetron hum, small stones ticking off the hull.
No dialogue.
```

**Shot C — Payoff / scale** *(Ingredients to Video, or Extend Shot B)*
```
Vertical 9:16. Same machine, matched exactly to the reference image. The camera pulls back and
rises to reveal the finished strip of dark, smooth, glassy fused regolith stretching away behind
the crawler with a subtle sheen, in sharp contrast to the loose grey powder ahead of it. Black
star-flecked sky, the Earth small and blue near the horizon, one long black shadow across the pad.
Audio: the rumble fades to a low hum and the tick of cooling glass. No dialogue.
```

---

## 22 · The Ice-Shell Habitat

**Upload:** `ice_shell_habitat_blueprint.png` · `ice_shell_habitat_render.png`
**Ingredient label:** `Storm Shelter water-wall crew module`
**Hook:** *The water you drink is the wall that keeps you alive.*

**Shot A — Blueprint ignition** *(Frames to Video: blueprint → render)*
```
Vertical 9:16. Opens on a cyanotype blueprint sheet filling the frame — prussian-blue paper, fine
white linework, drafting grid, monospaced title block. The camera pushes in on the drawn cross
section of the module, showing the thick water jacket around a small inner space. The linework
glows and lifts off the page into three dimensions; the grid dissolves into a spacecraft interior,
and the wireframe fills with real material — transparent-faced water tanks, faint blue water, gold
foil on the exterior, a warmly lit inner cabin — becoming exactly the cutaway in the final frame.
One continuous move, no cut. Audio: paper rustle, drafting-pen scratch, a rising tone settling into
a soft water gurgle and cabin fan hum. No dialogue.
```

**Shot B — Hero action** *(Ingredients to Video)*
```
Vertical 9:16. Reference image is the exact module: match its geometry, proportions, tank layout,
plumbing, colour and markings precisely. Do not redesign or add hardware that is not in the
reference. A clean technical cutaway of the Storm Shelter module. The camera pushes slowly inward
through the thick transparent-faced water jacket — faintly blue, bubbles drifting and rotating
inside, frost creeping across the cold outer skin — and comes to rest on the snug warmly lit
interior, where one astronaut in a soft flight suit floats reading a tablet, hair drifting, a water
dispenser and sleep restraints beside them. Cool exterior light against warm interior light. Audio:
soft water gurgle and slosh, cabin fan hum, a page-swipe tap. No dialogue.
```

**Shot C — Payoff / scale** *(Ingredients to Video, or Extend Shot B)*
```
Vertical 9:16. Same module, matched exactly to the reference image. The camera arcs slowly around
the outside of the cutaway, the water jacket glowing faintly blue from the cabin light within,
bubbles rising through the baffles, frost thickening on the outer skin. Through a small window,
black space and the edge of a larger station. Audio: gurgle and hum settling to a single calm low
tone. No dialogue.
```

---

## 23 · The Self-Healing Pressure Skin

**Upload:** `self_healing_skin_blueprint.png` · `self_healing_skin_render.png`
**Ingredient label:** `Self-Sealing Panel Test Article 03`
**Hook:** *The most dangerous thing that can hit a spacecraft is too small to see.*

**Shot A — Blueprint ignition** *(Frames to Video: blueprint → render)*
```
Vertical 9:16. Opens on a cyanotype blueprint sheet filling the frame — prussian-blue paper, fine
white linework, drafting grid, monospaced title block. The camera pushes in on the drawn layer
stack of the panel: two firm skins with a fluid layer between. The linework glows and lifts off the
page into three dimensions; the grid dissolves into the quilted wall of a space-station module, and
the wireframe fills with real material — a laptop-sized layered composite panel with a matte face
and a faintly translucent edge — becoming exactly the panel in the final frame. One continuous
move, no cut. Audio: paper rustle, drafting-pen scratch, a rising tone settling into quiet cabin
room tone. No dialogue.
```

**Shot B — Hero action** *(Ingredients to Video)*
```
Vertical 9:16. Reference image is the exact panel: match its layer structure, proportions, surface
finish, placard, stickers and markings precisely. Do not redesign or add objects that are not in
the reference. Crisp macro on the Self-Sealing Panel Test Article 03 mounted on a station interior
wall. A tiny puncture appears in the centre of the matte face with a small puff. The translucent
fluid layer sandwiched inside wells up into the hole, darkens, and sets into a small hardened bead
flush with the surface, leaving a faint discoloured halo around it. The whole event takes a couple
of seconds and then everything is still. Very shallow depth of field, cool white cabin lighting.
Audio: a sharp tick of impact, a brief hiss cutting off abruptly, then quiet cabin room tone and a
distant fan. No dialogue.
```

**Shot C — Payoff / scale** *(Ingredients to Video, or Extend Shot B)*
```
Vertical 9:16. Same panel, matched exactly to the reference image. A slow rack focus from the
sealed bead across to the printed placard and inspection stickers beside the panel, then a gentle
pull back to show the panel small against the cluttered technical wall of the module, handrails and
equipment soft behind. Audio: steady cabin room tone, one soft equipment beep. No dialogue.
```

---

## 24 · The Basalt Fibre Spinnery

**Upload:** `basalt_spinnery_blueprint.png` · `basalt_spinnery_render.png`
**Ingredient label:** `Basalt Fibre Line 01 melt-and-draw unit`
**Hook:** *Sintered domes are brilliant in compression — and useless in tension.*

**Shot A — Blueprint ignition** *(Frames to Video: blueprint → render)*
```
Vertical 9:16. Opens on a cyanotype blueprint sheet filling the frame — prussian-blue paper, fine
white linework, drafting grid, monospaced title block. The camera pushes in on the drawn section of
the furnace and bushing plate. The linework glows and lifts off the page into three dimensions; the
grid dissolves into a pressurised off-world workshop module, and the wireframe fills with real
material — a heavy insulated furnace housing glowing deep orange through a slot, a
platinum-coloured bushing plate, a large winding spool — becoming exactly the line in the final
frame. One continuous move, no cut. Audio: paper rustle, drafting-pen scratch, a rising tone
settling into a furnace roar and spool whine. No dialogue.
```

**Shot B — Hero action** *(Ingredients to Video)*
```
Vertical 9:16. Reference image is the exact equipment: match furnace housing, bushing plate, spool,
control panel, cable trays and markings precisely. Do not redesign or add equipment that is not in
the reference. The Basalt Fibre Line 01 runs. Beneath the platinum-coloured bushing plate a curtain
of dozens of fine molten filaments streams continuously downward, glowing bright orange at the top
and cooling to dark solid grey as they fall, gathering into a single strand that winds steadily onto
a large rotating spool already wrapped in fine golden-grey fibre. Heat shimmer rises above the
furnace slot; warm orange light flickers across nearby surfaces while the rest of the module stays
cool and industrial. The camera pushes in through the filament curtain toward the spool. Audio:
furnace roar, the high whine of the winder, a soft crackle from the melt, extraction fans.
No dialogue.
```

**Shot C — Payoff / scale** *(Ingredients to Video, or Extend Shot B)*
```
Vertical 9:16. Same equipment, matched exactly to the reference image. The camera pulls back to
show the whole draw line at a three-quarter angle — the glowing furnace, the falling filament
curtain, the turning spool, the bin of dark crushed basalt feedstock waiting at the input end — the
warm glow of the melt sharply contrasted against the cool industrial module. Slight haze in the air.
Audio: the roar drops under a steady mechanical rhythm of the winder. No dialogue.
```

---

## 25 · The Variable-Gravity Sleep Centrifuge

**Upload:** `sleep_centrifuge_blueprint.png` · `sleep_centrifuge_render.png`
**Ingredient label:** `Sleep Centrifuge Test berth and rotating arm`
**Hook:** *Weightlessness is quietly ruining the people who live in it.*

**Shot A — Blueprint ignition** *(Frames to Video: blueprint → render)*
```
Vertical 9:16. Opens on a cyanotype blueprint sheet filling the frame — prussian-blue paper, fine
white linework, drafting grid, monospaced title block. The camera pushes in on the drawn plan view
of the rotating arm and berth. The linework glows and lifts off the page into three dimensions; the
grid dissolves into a cluttered space-station research module, and the wireframe fills with real
material — a padded white-and-grey enclosed bunk pod, a sturdy short arm, a central hub with motor
housing — becoming exactly the machine in the final frame. One continuous move, no cut. Audio:
paper rustle, drafting-pen scratch, a rising tone settling into a slow bearing hum. No dialogue.
```

**Shot B — Hero action** *(Ingredients to Video)*
```
Vertical 9:16. Reference image is the exact machine: match berth shape, upholstery, arm length, hub
and motor housing, control panel and markings precisely. Do not redesign or add hardware that is
not in the reference. Inside a dimmed station research module, a volunteer astronaut in a soft
sleep suit lies in the padded berth, head toward the hub, feet outward, lightly strapped in, eyes
closed. The motor hub spins up and the arm begins a slow steady rotation; the berth settles
outward against the developing pull and the restraints go taut. Cable bundles sway slightly.
Readouts on the control panel step upward. Slight motion blur on the moving arm. Cool dim lighting
with a warm glow inside the berth. Audio: structure-borne — bearing hum rising in pitch, a soft
rhythmic pass of the arm, cabin fans, a slow calm breathing rhythm. No dialogue.
```

**Shot C — Payoff / scale** *(Ingredients to Video, or Extend Shot B)*
```
Vertical 9:16. Same machine, matched exactly to the reference image. Slow overhead view looking
down on the turning arm, the lit berth sweeping steadily around the hub, the cluttered module —
racks, laptops on Velcro, handrails — wheeling past in the dark around it. Calm and clinical.
Audio: a steady bearing hum and the soft rhythmic pass of the arm, nothing else. No dialogue.
```

---
---

# Food & Life Support

## 26 · The Closed Algal Loop

**Upload:** `algal_loop_blueprint.png` · `algal_loop_render.png`
**Ingredient label:** `Algal Air Unit 01 photobioreactor panel`
**Hook:** *The machines that let us live among the stars may look more like gardens than engines.*

**Shot A — Blueprint ignition** *(Frames to Video: blueprint → render)*
```
Vertical 9:16. Opens on a cyanotype blueprint sheet filling the frame — prussian-blue paper, fine
white linework, drafting grid, monospaced title block. The camera pushes in on the drawn tube array
and gas-loop schematic. The linework glows and lifts off the page into three dimensions; the grid
dissolves into a space-station module wall, and the wireframe fills with real material — a flat
panel of clear vertical tubes filling with vivid bright-green algae culture under LED grow-lights —
becoming exactly the unit in the final frame. One continuous move, no cut. Audio: paper rustle,
drafting-pen scratch, a rising tone settling into a soft pump and rising bubbles. No dialogue.
```

**Shot B — Hero action** *(Ingredients to Video)*
```
Vertical 9:16. Reference image is the exact unit: match tube array, manifolds, pumps, control box,
readout and printed label precisely. Do not redesign or add equipment that is not in the reference.
Macro on the Algal Air Unit 01: fine bubbles rise in streams through vivid bright-green algae
culture in the clear vertical tubes, swirling the fluid into slow green vortices, lit from within
by integrated LED grow-lights. Condensation beads on the outside of the glass. The green glow
spills onto the surrounding cabin surfaces. The camera drifts slowly upward along the tubes,
following the bubbles. Cool cabin lighting against the warm green glow. Audio: a soft diaphragm
pump, a steady stream of small bubbles, cabin fan hum, one quiet electronic beep. No dialogue.
```

**Shot C — Payoff / scale** *(Ingredients to Video, or Extend Shot B)*
```
Vertical 9:16. Same unit, matched exactly to the reference image. The camera pulls back and pans
along the full panel to the compact control box, its readout ticking over, the harvest port and
sample bottle beside it, then holds on the whole green-glowing array against the cluttered
technical interior of the station. Audio: pump and bubbles settle into a steady rhythm, one soft
chime. No dialogue.
```

---

## 27 · The Aeroponic Root Tower

**Upload:** `root_tower_blueprint.png` · `root_tower_render.png`
**Ingredient label:** `Aeroponic Tower 01 vertical growing column`
**Hook:** *Taking the farm to space means leaving behind its most basic ingredient: soil.*

**Shot A — Blueprint ignition** *(Frames to Video: blueprint → render)*
```
Vertical 9:16. Opens on a cyanotype blueprint sheet filling the frame — prussian-blue paper, fine
white linework, drafting grid, monospaced title block. The camera pushes in on the drawn section of
the column showing ports, misting nozzles and the root chamber. The linework glows and lifts off
the page into three dimensions; the grid dissolves into a habitat interior, and the wireframe fills
with real material — a sleek white cylindrical column studded with lush green lettuce and herbs
under pink-white grow-lights — becoming exactly the tower in the final frame. One continuous move,
no cut. Audio: paper rustle, drafting-pen scratch, a rising tone settling into a soft pump and a
misting hiss. No dialogue.
```

**Shot B — Hero action** *(Ingredients to Video)*
```
Vertical 9:16. Reference image is the exact unit: match column shape, port pattern, cutaway window,
reservoir, control panel and printed label precisely. Do not redesign or add equipment that is not
in the reference. Close on the cutaway window of the Aeroponic Tower 01: inside the dark chamber,
pale bare roots hang in still air, then a burst of fine mist floods the space and settles on them
in glistening droplets. Outside the column, the lush green lettuce and herb tops tremble slightly
under the pink-white LED grow-lights. The camera rises slowly up the column from the reservoir at
the base, past the misted roots, into the bright canopy of leaves. Audio: a nutrient pump kicking
in, a soft misting hiss, LED ballast hum, faint leaf rustle. No dialogue.
```

**Shot C — Payoff / scale** *(Ingredients to Video, or Extend Shot B)*
```
Vertical 9:16. Same unit, matched exactly to the reference image. The camera pulls back to show the
whole two-metre column of greens glowing pink-green in the habitat, the harvest basket of picked
leaves beside it, the technical interior of the module soft behind. Crisp, clean, vibrant. Audio:
pump and hiss settle to a steady hum, one soft chime. No dialogue.
```

---

## 28 · The Insect Protein Reactor

**Upload:** `insect_reactor_blueprint.png` · `insect_reactor_render.png`
**Ingredient label:** `Protein Reactor 01 BSF rearing cabinet`
**Hook:** *The livestock that fits off-world is the one we spent history keeping out of the kitchen.*

**Shot A — Blueprint ignition** *(Frames to Video: blueprint → render)*
```
Vertical 9:16. Opens on a cyanotype blueprint sheet filling the frame — prussian-blue paper, fine
white linework, drafting grid, monospaced title block. The camera pushes in on the drawn tray stack
and airflow arrows. The linework glows and lifts off the page into three dimensions; the grid
dissolves into a habitat interior, and the wireframe fills with real material — a white enclosed
cabinet with a transparent front, slide-out trays, climate vents and a readout — becoming exactly
the unit in the final frame. One continuous move, no cut. Audio: paper rustle, drafting-pen scratch,
a rising tone settling into a quiet ventilation hum. No dialogue.
```

**Shot B — Hero action** *(Ingredients to Video)*
```
Vertical 9:16. Reference image is the exact unit: match cabinet shape, tray layout, vents, readout,
frass drawer and printed labels precisely. Do not redesign or add equipment that is not in the
reference. Clean, clinical, well lit, presented as tidy food-production equipment and never
grotesque. One slide-out tray of the Protein Reactor 01 draws smoothly forward, revealing black
soldier fly larvae moving slowly over a bed of dark composted crop waste. The humidity and
temperature readout ticks. Fine mesh screens and gasketed edges are clearly visible. The camera
pushes in evenly on the open tray, holds briefly, then eases back. Cool even lighting, shallow
depth of field. Audio: a drawer slide, ventilation hum, a soft granular rustle, an electronic beep.
No dialogue.
```

**Shot C — Payoff / scale** *(Ingredients to Video, or Extend Shot B)*
```
Vertical 9:16. Same unit, matched exactly to the reference image. The camera pans off the cabinet
to the bench beside it and settles on the tray of harvested dried larvae and the jar of pale
protein flour with its scoop, then widens slightly to include the frass drawer labelled for
fertiliser. Clean product-photography lighting throughout. Audio: ventilation hum, the soft scuff
of the scoop, one chime. No dialogue.
```

---
---

# Resource Extraction & Transport

## 29 · The Perchlorate Scrubber

**Upload:** `perchlorate_scrubber_blueprint.png` · `perchlorate_scrubber_render.png`
**Ingredient label:** `Perchlorate Scrubber 01 sealed soil-detox skid`
**Hook:** *Martian soil is not just infertile. It is poisonous.*

**Shot A — Blueprint ignition** *(Frames to Video: blueprint → render)*
```
Vertical 9:16. Opens on a cyanotype blueprint sheet filling the frame — prussian-blue paper, fine
white linework, drafting grid, monospaced title block. The camera pushes in on the drawn process
flow from intake hopper to bioreactor. The linework glows and lifts off the page into three
dimensions; the grid dissolves into rusty Martian regolith under a dusty pink sky, and the
wireframe fills with real material — a compact industrial skid with a stainless hopper, sealed wash
tank, separation drum and bioreactor — becoming exactly the unit in the final frame. One continuous
move, no cut. Audio: paper rustle, drafting-pen scratch, a rising tone settling into thin Martian
wind and a slow drum rumble. No dialogue.
```

**Shot B — Hero action** *(Ingredients to Video)*
```
Vertical 9:16. Reference image is the exact machine: match skid layout, hopper, tanks, drum,
plumbing, hazard striping and printed labels precisely. Do not redesign or add equipment that is
not in the reference. At a Mars surface base, rusty-red regolith pours from the stainless intake
hopper of the Perchlorate Scrubber 01 into the sealed wash-and-mixing tank. The separation drum
turns steadily. Cloudy liquid churns behind the bioreactor's small viewing window, and a fine
stream of clean pale detoxified soil falls onto a growing pile at the output end, visibly different
from the red raw feed. Fine dust drifts across the frame. The camera tracks slowly along the skid
from intake to output. Hard low sunlight, dusty pink sky. Audio: granular pour, drum rumble, pump
throb, valve clicks, thin wind. No dialogue.
```

**Shot C — Payoff / scale** *(Ingredients to Video, or Extend Shot B)*
```
Vertical 9:16. Same machine, matched exactly to the reference image. The camera pulls back to hold
both piles in frame — rusty-red toxic regolith at the intake, clean pale soil at the output —
against the ochre Martian landscape and dusty pink sky, dust caked on the skid's lower surfaces,
hazard striping catching the low sun. Audio: the machinery settles into a steady rhythm under
rising wind. No dialogue.
```

---

## 30 · The Atmospheric Water Condenser

**Upload:** `water_condenser_blueprint.png` · `water_condenser_render.png`
**Ingredient label:** `Atmospheric Water Condenser 01 night-cycle unit`
**Hook:** *The surest water is the water you do not have to travel to.*

**Shot A — Blueprint ignition** *(Frames to Video: blueprint → render)*
```
Vertical 9:16. Opens on a cyanotype blueprint sheet filling the frame — prussian-blue paper, fine
white linework, drafting grid, monospaced title block. The camera pushes in on the drawn section of
the finned cold plate and collection tank. The linework glows and lifts off the page into three
dimensions; the grid dissolves into a cold Martian night, rusty regolith under a star-filled dark
sky, and the wireframe fills with real material — a compact appliance-sized unit with a broad
finned cold-plate array tilted to the sky — becoming exactly the machine in the final frame. One
continuous move, no cut. Audio: paper rustle, drafting-pen scratch, a rising tone settling into
thin night wind and a low fan. No dialogue.
```

**Shot B — Hero action** *(Ingredients to Video)*
```
Vertical 9:16. Reference image is the exact machine: match its geometry, fin pattern, intake screen,
tank, placards and printed label precisely. Do not redesign or add hardware that is not in the
reference. Macro on the tilted black cold plates of the Atmospheric Water Condenser 01 on the
Martian surface at night. A thin coating of white frost creeps visibly across the fins, thickening
and glinting under cold blue moonlight. The low-power intake fan turns slowly behind its dust
screen. Rime builds around the unit's lower edges. A single status light glows warm amber. Very
shallow depth of field, extreme stillness, breath-cold atmosphere. Audio: thin high wind, a slow
fan, faint tick of contracting metal in the cold. No dialogue.
```

**Shot C — Payoff / scale** *(Ingredients to Video, or Extend Shot B)*
```
Vertical 9:16. Same machine, matched exactly to the reference image. A droplet of meltwater runs
down a fin and into the collection pipe at the base. The camera pulls back low across frost-dusted
red regolith to hold the whole unit against a star-filled dark sky, with Phobos small overhead and
dim habitat lights out of focus in the distance. Audio: a single water drip, wind, then quiet.
No dialogue.
```

---

## 31 · The Lunar Mass Driver

**Upload:** `mass_driver_blueprint.png` · `mass_driver_render.png`
**Ingredient label:** `Mass Driver 01 lunar electromagnetic launch track`
**Hook:** *The moment the Moon stops being a destination and becomes a source.*

**Shot A — Blueprint ignition** *(Frames to Video: blueprint → render)*
```
Vertical 9:16. Opens on a cyanotype blueprint sheet filling the frame — prussian-blue paper, fine
white linework, drafting grid, monospaced title block. The camera pushes in on the drawn elevation
of the segmented drive-coil track. The linework glows and lifts off the page into three dimensions;
the grid dissolves into grey cratered lunar regolith under a black star-dusted sky, and the
wireframe fills with real material — a long low straight rail of segmented coil modules running to
the horizon, support pylons, solar field, control building — becoming exactly the installation in
the final frame. One continuous move, no cut. Audio: paper rustle, drafting-pen scratch, a rising
tone settling into a deep capacitor charge whine. No dialogue.
```

**Shot B — Hero action** *(Ingredients to Video)*
```
Vertical 9:16. Reference image is the exact installation: match track segmentation, coil housings,
pylon spacing, control building, solar field, hazard markings and printed label precisely. Do not
redesign or add structures that are not in the reference. The Mass Driver 01 fires. A compact launch
bucket carrying a block of processed metal accelerates down the segmented track, and the drive
coils flash in a fast travelling sequence along its length as it passes. Dust lifts from the
regolith beside the rails in slow lunar arcs and falls straight back — no billowing. The camera is
mounted low beside the track looking along it toward the elevated far end, the bucket rushing past
the lens. Harsh sunlight, long sharp shadows. Audio: structure-borne — a rising capacitor whine,
a rapid sequence of hard electromagnetic cracks conducted through the rail, then abrupt silence.
No dialogue.
```

**Shot C — Payoff / scale** *(Ingredients to Video, or Extend Shot B)*
```
Vertical 9:16. Same installation, matched exactly to the reference image. From the elevated end of
the track, the launch bucket releases its payload, which coasts silently out into black star-dusted
sky on a flat trajectory while the empty bucket decelerates back down the rail. The camera holds
still and lets the payload shrink to a point, the blue-white crescent of Earth low on the horizon
behind. Audio: the whine dies away completely — total silence as the payload leaves. No dialogue.
```

---

## 32 · The Skyhook Tether

**Upload:** `skyhook_tether_blueprint.png` · `skyhook_tether_render.png`
**Ingredient label:** `rotating skyhook tether station with capture head`
**Hook:** *Reaching orbit is the famous part. It is not the hard part.*

**Shot A — Blueprint ignition** *(Frames to Video: blueprint → render)*
```
Vertical 9:16. Opens on a cyanotype blueprint sheet filling the frame — prussian-blue paper, fine
white linework, drafting grid, monospaced title block. The camera pushes in on the drawn tether
sweeping about its central station. The linework glows and lifts off the page into three dimensions;
the grid dissolves into black star-filled space above a grey cratered moon, and the wireframe fills
with real material — a long slender multi-strand cable, a compact cylindrical station with solar
panels, a robotic capture head at the tip — becoming exactly the scene in the final frame. One
continuous move, no cut. Audio: paper rustle, drafting-pen scratch, a rising tone settling into a
low structural groan. No dialogue.
```

**Shot B — Hero action** *(Ingredients to Video)*
```
Vertical 9:16. Reference image is the exact hardware: match tether braiding, station geometry,
solar panels, capture-head design and running lights precisely. Do not redesign or add hardware
that is not in the reference. The tip of the rotating skyhook tether sweeps down toward a small
cargo pod rising from the grey cratered moon below. The braided redundant cable is taut and
catching hard sunlight along its length; the robotic grapple claw at the tip opens and reaches. The
two close on each other with the slow, inevitable geometry of orbital mechanics. Running lights
blink on the distant central station. The camera rides alongside the capture head, matching its
arc, the moon wheeling below. Audio: structure-borne — a deep cable groan under load, servo whine
from the claw, sharp latch clunk, telemetry chirps. No dialogue.
```

**Shot C — Payoff / scale** *(Ingredients to Video, or Extend Shot B)*
```
Vertical 9:16. Same hardware, matched exactly to the reference image. The camera pulls far back to
show the entire tether stretched across the frame in slow end-over-end rotation, the captured pod
riding at one tip, the compact station at the centre, the grey moon filling the lower frame and a
distant blue planet beyond. Vast scale, hard sunlight one side, deep shadow the other. Audio: the
groan thins to one long low tone. No dialogue.
```

---
---

# Surface Infrastructure

## 33 · The Regolith Rail Grader

**Upload:** `rail_grader_blueprint.png` · `rail_grader_render.png`
**Ingredient label:** `Sinter Grader 01 solar road-sintering crawler`
**Hook:** *Roads are the first thing a civilisation builds when it means to stay.*

**Shot A — Blueprint ignition** *(Frames to Video: blueprint → render)*
```
Vertical 9:16. Opens on a cyanotype blueprint sheet filling the frame — prussian-blue paper, fine
white linework, drafting grid, monospaced title block. The camera pushes in on the drawn elevation
of the crawler and its solar concentrator mirror. The linework glows and lifts off the page into
three dimensions; the grid dissolves into a level grey lunar plain under a black star-dusted sky,
and the wireframe fills with real material — a low boxy crawler on wide dusty tracks with a curved
polished mirror above it — becoming exactly the machine in the final frame. One continuous move,
no cut. Audio: paper rustle, drafting-pen scratch, a rising tone settling into a deep track rumble.
No dialogue.
```

**Shot B — Hero action** *(Ingredients to Video)*
```
Vertical 9:16. Reference image is the exact machine: match its geometry, proportions, mirror shape
and mounting, blade, track design, hazard striping and printed label precisely. Do not redesign or
add hardware that is not in the reference. The Sinter Grader 01 crawls slowly forward across the
lunar plain. Its curved polished concentrator mirror focuses a brilliant point of light onto the
ground beneath its belly; the regolith at the focus glows fierce orange-white and fuses. The
grading blade at the front trims the loose surface ahead. Dust lifted by the tracks rises in slow
ballistic arcs and falls straight back. The camera tracks low and level alongside the machine at
ground height, the sinter glow lighting its underside. Harsh low sunlight, long sharp shadows.
Audio: structure-borne — deep track rumble, gearbox whine, the faint crackle of fusing rock,
stones ticking off the hull. No dialogue.
```

**Shot C — Payoff / scale** *(Ingredients to Video, or Extend Shot B)*
```
Vertical 9:16. Same machine, matched exactly to the reference image. The camera pulls back and
rises to reveal the finished road behind the crawler — a dark, smooth, glassy strip running away
toward a habitat module and lander in the far distance — in sharp contrast to the loose grey
powdery regolith ahead of it. Black star-dusted sky, one long black shadow. Audio: the rumble
recedes, leaving the tick of cooling glass. No dialogue.
```

---

## 34 · The Lava Tube Surveyor "Ariadne"

**Upload:** `lava_tube_surveyor_blueprint.png` · `lava_tube_surveyor_render.png`
**Ingredient label:** `LT-1 Ariadne tethered lava-tube survey drone`
**Hook:** *The best shelter on the Moon may be a hole that has waited three billion years.*

**Shot A — Blueprint ignition** *(Frames to Video: blueprint → render)*
```
Vertical 9:16. Opens on a cyanotype blueprint sheet filling the frame — prussian-blue paper, fine
white and cyan linework, faint drafting grid, monospaced title block reading LT-1 ARIADNE. The
camera pushes in on the drawn cross-section through the surface, the skylight and the cavern below.
The linework glows and lifts off the page into three dimensions; the drafting grid dissolves into
the black of a lunar collapse pit, and the wireframe fills with real material — a rugged
suitcase-sized drone on a taut armoured cable, lamps burning, dark basalt walls around it —
becoming exactly the scene in the final frame. One continuous move, no cut. Audio: paper rustle,
drafting-pen scratch, a rising tone settling into winch hum and deep cave silence. No dialogue.
```

**Shot B — Hero action** *(Ingredients to Video)*
```
Vertical 9:16. Reference image is the exact machine: match its geometry, proportions, lidar head,
stereo cameras, floodlight placement, thermal blanketing and stencilled markings precisely. Do not
redesign or add hardware that is not in the reference. The LT-1 Ariadne survey drone descends
steadily on its taut armoured tether into a lunar collapse pit. Its bright white floodlights throw
hard cones of light that sweep slowly across a curving wall of rough dark basalt, picking out
texture and then losing it to total blackness. The scanning lidar head rotates continuously. Far
below, a rubble-strewn floor drifts in and out of the beams. Fine dust hangs in the light. The
camera looks slightly down past the drone into the void, descending with it. Audio:
structure-borne — winch motor hum, cable creak, the whirr of the rotating lidar, a deep dead
acoustic. No dialogue.
```

**Shot C — Payoff / scale** *(Ingredients to Video, or Extend Shot B)*
```
Vertical 9:16. Same machine, matched exactly to the reference image. The camera tilts up from the
drone along the cable toward the mouth of the pit far above, where a hard shaft of raw sunlight
enters and lights a slice of wall and a column of hanging dust motes, the opening a small bright
irregular hole in absolute darkness. Audio: the winch hum drops away to almost nothing, one faint
cable creak, then silence. No dialogue.
```

---
---

# Off-World Industry (Volume II)

> Concept 39 is dual-use and the source study treats it at textbook-principle level only — no plant,
> no apparatus, no hardware prompt. Its shots are a governance museum exhibit instead, the same
> convention as 17 and 18. Keep that framing.

## 35 · The Hopper Freighter "Grasshopper"

**Upload:** `hopper_freighter_blueprint.png` · `hopper_freighter_render.png`
**Ingredient label:** `Hopper 01 uncrewed cargo hopper`
**Hook:** *Every settlement discovers its roads end long before its ambitions do.*

**Shot A — Blueprint ignition** *(Frames to Video: blueprint → render)*
```
Vertical 9:16. Opens on a cyanotype blueprint sheet filling the frame — prussian-blue paper, fine
white and cyan linework, faint drafting grid, monospaced title block reading HF-1 GRASSHOPPER. The
camera pushes in along the long dashed ballistic arc drawn over scalloped crater rims, following
it down to the small lander figure at the landing end. The linework glows and lifts off the page
into three dimensions; the grid dissolves into a remote grey lunar plain under a black sky, and the
wireframe fills with real material — spherical propellant tanks in gold and white blanketing on an
exposed metal frame, four splayed legs, a cargo container strapped on top — becoming exactly the
hopper in the final frame. One continuous move, no cut, and the finished hardware does not morph.
Audio: paper rustle, drafting-pen scratch, a rising tone settling into a deep engine rumble.
No dialogue.
```

**Shot B — Hero action** *(Ingredients to Video)*
```
Vertical 9:16. Reference image is the exact machine: match its geometry, proportions, colour, tank
layout, leg design, cargo container and stencilled markings precisely. Do not redesign, restyle, or
add hardware that is not in the reference. The Hopper 01 cargo hopper descends the last few metres
onto a dark sintered landing pad, its single throttled engine firing a pale, almost invisible
translucent plume. Grey dust sprays outward from the pad in a flat radial fan of straight ballistic
streaks that fly far and fall without billowing — no air to hold them up. The four splayed legs
flex as the footpads touch; the engine cuts instantly and the plume vanishes. The camera holds a
low three-quarter angle, descending with the vehicle. Harsh low sunlight, long knife-edged shadows,
black star-dusted sky. Audio: structure-borne — deep engine rumble conducted through the frame,
RCS thruster ticks, a heavy leg-strut clunk, then abrupt silence. No dialogue.
```

**Shot C — Payoff / scale** *(Ingredients to Video, or Extend Shot B)*
```
Vertical 9:16. Same hopper, matched exactly to the reference image. The engine relights and the
hopper lifts cleanly off the pad, pitching over onto a long ballistic arc. The camera stays on the
ground and tilts up to follow as it climbs over a distant crater rim and shrinks to a bright point
against the black sky, the plume barely visible. On the pad, the last of the dust settles straight
down. Audio: the rumble fades with distance through the ground to nothing, then silence.
No dialogue.
```

---

## 36 · The Vacuum Vapour Refinery "Alembic"

**Upload:** `vapour_refinery_blueprint.png` · `vapour_refinery_render.png`
**Ingredient label:** `Vapour Refinery 01 solar vacuum distillation unit`
**Hook:** *The alchemists could never make a good enough vacuum. The Moon has one for free.*

**Shot A — Blueprint ignition** *(Frames to Video: blueprint → render)*
```
Vertical 9:16. Opens on a cyanotype blueprint sheet filling the frame — prussian-blue paper, fine
white and cyan linework, faint drafting grid, monospaced title block reading VR-1 ALEMBIC. The
camera pushes in on the drawn heated crucible and the row of four collector plates running from hot
to cold. The linework glows and lifts off the page into three dimensions; the grid dissolves into a
lunar industrial yard under a black sky, and the wireframe fills with real material — a squat
gold-blanketed furnace vessel, a polished parabolic concentrator above it, an insulated manifold
leading to four finned collector drums — becoming exactly the refinery in the final frame. One
continuous move, no cut. Audio: paper rustle, drafting-pen scratch, a rising tone settling into a
low crucible hum. No dialogue.
```

**Shot B — Hero action** *(Ingredients to Video)*
```
Vertical 9:16. Reference image is the exact machine: match its geometry, proportions, colour,
concentrator, manifold, collector drum sizes, fin pattern and stencilled markings precisely. Do not
redesign or add hardware that is not in the reference. The polished parabolic concentrator of
Vapour Refinery 01 focuses a blinding point of sunlight onto the crucible port; the beam itself is
invisible in the vacuum, only the focal point blazes. Through the small inspection window the
crucible interior brightens from dull red to fierce orange. The camera tracks slowly along the
insulated manifold from the hot furnace past each progressively smaller collector drum to the last,
where an open access hatch reveals a bright metallic film condensed on the inner wall, catching the
light. No heat shimmer — there is no air. Harsh sunlight, long sharp shadows. Audio:
structure-borne — a deep crucible hum, rhythmic thermal ticking of expanding flanges, actuator
clicks. No dialogue.
```

**Shot C — Payoff / scale** *(Ingredients to Video, or Extend Shot B)*
```
Vertical 9:16. Same refinery, matched exactly to the reference image. A slow rack focus from the
metallic film inside the open collector drum across to the pallet beside the unit, stacked with
gleaming recovered metal ingots, then a gentle pull back to show the whole refinery on its sintered
pad, the concentrator's focal glow lighting nearby surfaces against a black star-dusted sky. Audio:
the hum steadies, one soft cooling tick. No dialogue.
```

---

## 37 · The Orbital Foundry Ring "Hephaestus"

**Upload:** `foundry_ring_blueprint.png` · `foundry_ring_render.png`
**Ingredient label:** `Casting Bay 03 containerless levitation chamber`
**Hook:** *Every casting on Earth carries the fingerprints of its mould — and the weight it had to bear while it cooled.*

**Shot A — Blueprint ignition** *(Frames to Video: blueprint → render)*
```
Vertical 9:16. Opens on a cyanotype blueprint sheet filling the frame — prussian-blue paper, fine
white and cyan linework, faint drafting grid, monospaced title block reading OF-1 HEPHAESTUS. The
camera pushes past the drawn foundry ring into the magnified detail circle of a containerless bay:
levitation coils above and below, a sphere suspended in the gap touching nothing. The linework
glows and lifts off the page into three dimensions; the grid dissolves into a heavy ribbed
industrial chamber, and the drawn sphere fills with molten orange-white metal floating between
copper coils — becoming exactly the casting bay in the final frame. One continuous move, no cut.
Audio: paper rustle, drafting-pen scratch, a rising tone settling into a deep electromagnetic hum.
No dialogue.
```

**Shot B — Hero action** *(Ingredients to Video)*
```
Vertical 9:16. Reference image is the exact chamber: match its wall ribbing, coil placement, sphere
size, manipulator arm, viewport, sensor booms and stencilled markings precisely. Do not redesign or
add hardware that is not in the reference. Inside Casting Bay 03, a beach-ball-sized sphere of
molten metal floats perfectly still in the exact centre, touching nothing. Slow waves ripple across
its shimmering orange-white surface and settle; surface tension pulls it back to a near-perfect
sphere. The copper levitation coils above and below pulse faintly, and the sphere stretches
gently into an ellipse, then holds. The robotic manipulator arm with its heat-shielded gripper eases
closer but never makes contact. The camera orbits slowly around the sphere. The molten metal is the
only warm light, against cool blue-white instrument lighting. Audio: a deep steady coil hum rising
in pitch as the field shapes the melt, servo whine, pyrometer ticks. No dialogue.
```

**Shot C — Payoff / scale** *(Ingredients to Video, or Extend Shot B)*
```
Vertical 9:16. Same chamber, matched exactly to the reference image. The camera drifts backward
past the floating glowing sphere toward the rear window, keeping the sphere large and warm in the
foreground while the view through the glass resolves: the grey curve of a moon, black star-dusted
space, and a glimpse of the station's long radiator panels. Audio: the coil hum settles to one
sustained low tone. No dialogue.
```

---

## 38 · The Solar Concentrator Kiln "Archimedes"

**Upload:** `concentrator_kiln_blueprint.png` · `concentrator_kiln_render.png`
**Ingredient label:** `Solar Kiln 01 tracking concentrator dish`
**Hook:** *Sunlight is the one thing a settlement never has to mine, make or carry.*

**Shot A — Blueprint ignition** *(Frames to Video: blueprint → render)*
```
Vertical 9:16. Opens on a cyanotype blueprint sheet filling the frame — prussian-blue paper, fine
white and cyan linework, faint drafting grid, monospaced title block reading SC-1 ARCHIMEDES. The
camera pushes in along the drawn reflected beams converging from the mirrors onto one bright focal
point. The linework glows and lifts off the page into three dimensions; the grid dissolves into a
level grey lunar plain under a black sky, and the wireframe fills with real material — a polished
faceted parabolic dish on a motorised two-axis tracking frame, a ceramic receiver head just above
glowing regolith — becoming exactly the kiln in the final frame. One continuous move, no cut.
Audio: paper rustle, drafting-pen scratch, a rising tone settling into a low tracking-motor hum.
No dialogue.
```

**Shot B — Hero action** *(Ingredients to Video)*
```
Vertical 9:16. Reference image is the exact machine: match dish size, faceted mirror segments,
tracking frame, receiver arm, control box and stencilled markings precisely. Do not redesign or add
hardware that is not in the reference. The Solar Kiln 01 dish tracks a fraction of a degree on its
two-axis frame, keeping the low brilliant sun centred. The focused beam is invisible in the vacuum —
only the focal point shows, where the regolith beneath the ceramic receiver head glows a searing
orange-white. The receiver arm advances slowly, and behind it the finished strip of dark glassy
sintered pavement grows by a hand's width. Grey dust dulls the lower edges of the mirror. The camera
moves low along the ground toward the glowing focus, the dish looming above. Harsh sunlight,
knife-edged shadows. Audio: structure-borne — actuator motor whine, a faint crackle of fusing rock,
thermal ticking. No dialogue.
```

**Shot C — Payoff / scale** *(Ingredients to Video, or Extend Shot B)*
```
Vertical 9:16. Same machine, matched exactly to the reference image. The camera pulls back and
rises to a wide view: the single dish on the level plain, its focal glow a small intense point, the
dark sintered strip running away behind it, a habitat module in the far distance. The sun sits very
low and every shadow stretches long across the regolith, the dish still tracking. Black star-dusted
sky. Audio: the motor hum steadies into a single low tone. No dialogue.
```

---

## 39 · The Isotope Sorting Column "Aston"

**Upload:** `isotope_column_blueprint.png` · `isotope_column_render.png`
**Ingredient label:** `dual-use governance museum exhibit`
**Hook:** *The hard part of this machine was never the physics. It is who gets to run it.*

**Shot A — Blueprint ignition** *(Frames to Video: principle sheet → exhibit render)*
```
Vertical 9:16. Opens on a cyanotype principle sheet filling the frame — prussian-blue paper, fine
white linework, faint drafting grid, monospaced title block. The camera pushes in on the simple
physics diagram of two curved particle paths of different radii. No machine forms. Instead the
sheet recedes and resolves into a large softly lit wall panel in a quiet museum gallery, the same
blue drawing of two curved paths now printed behind glass, with a display case and a low bench in
the foreground under cool museum track lighting. One continuous move, no cut, no apparatus of any
kind appears. Audio: paper rustle, drafting-pen scratch, a rising tone resolving into hushed gallery
room tone. No dialogue.
```

**Shot B — Hero action** *(Ingredients to Video)*
```
Vertical 9:16. Reference image is the exact exhibit: match the display case, the antique
instrument, the wall panels, the gallery architecture and lighting precisely. Do not add equipment,
machinery or apparatus of any kind. A slow dolly move past a softly lit display case holding a
historical 1920s brass-and-glass mass spectrograph tube on a velvet mount, warm light catching the
brass, reflections sliding across the glass as the camera passes. Behind it, a large wall panel
carries a diagram of two curved particle paths of different radii and blocks of printed treaty
typography, soft and unreadable at this distance. Two visitors stand reading, seen from behind,
small against the panels. Polished floor with soft reflections, dust motes in the light beams.
Contemplative and restrained. Audio: hushed gallery room tone, soft footsteps, a faint HVAC hum.
No dialogue.
```

**Shot C — Payoff / scale** *(Ingredients to Video, or Extend Shot B)*
```
Vertical 9:16. Same exhibit, matched exactly to the reference image. The camera leaves the display
case and pushes slowly toward a second wall panel showing a simple horizontal timeline of
institutional markers that runs steadily along — and then stops, leaving a long conspicuous empty
stretch with no markers at all. The camera comes to rest on that empty gap. A visitor's silhouette
pauses in front of it. Audio: room tone, one set of footsteps stopping, then near-silence.
No dialogue.
```

---

## 40 · The Recycling Cascade "Ouroboros"

**Upload:** `recycling_cascade_blueprint.png` · `recycling_cascade_render.png`
**Ingredient label:** `Reclamation Bay 01 repair-first workshop`
**Hook:** *At one end of my catalogue, a starship pushed by light. At the other, a machine that sorts rubbish.*

**Shot A — Blueprint ignition** *(Frames to Video: blueprint → render)*
```
Vertical 9:16. Opens on a cyanotype blueprint sheet filling the frame — prussian-blue paper, fine
white and cyan linework, faint drafting grid, monospaced title block reading RC-1 OUROBOROS. The
camera pushes in and follows the drawn cascade downward through its five stacked stage boxes,
settling on the small residue box at the bottom. The linework glows and lifts off the page into
three dimensions; the grid dissolves into the cool light of a habitat workshop, and the wireframe
fills with real material — sorting bins along a wall, a workbench with a half-disassembled pump, a
regrind machine, a small crucible — becoming exactly the reclamation bay in the final frame. One
continuous move, no cut. Audio: paper rustle, drafting-pen scratch, a rising tone settling into
workshop room tone and an extraction fan. No dialogue.
```

**Shot B — Hero action** *(Ingredients to Video)*
```
Vertical 9:16. Reference image is the exact workshop: match bin layout, bench, pump parts, regrind
machine, crucible, wall screen, placards and stencilled markings precisely. Do not redesign or add
equipment that is not in the reference. In Reclamation Bay 01, a technician's gloved hands — no face
in frame — sweep a handheld material scanner over a scrap part, then drop it into the correct
sorting bin. The hands turn to the bench and seat a tagged part back into the half-disassembled
pump. The camera tracks slowly along the bench past the regrind machine, its hopper taking a
trickle of shredded polymer flake, to the compact induction crucible where a freshly cast ingot
cools with a warm glow. Clean, orderly, purposeful. Cool even workshop lighting. Audio: scanner
beep, the clink of a part into a metal bin, a regrind whirr, extraction fan, a low crucible hum.
No dialogue.
```

**Shot C — Payoff / scale** *(Ingredients to Video, or Extend Shot B)*
```
Vertical 9:16. Same workshop, matched exactly to the reference image. The camera pulls back to show
the whole reclamation wall — four sorting bins neatly filled, the bench, the wall screen with its
material-flow diagram, the cooling ingot — then settles slowly on the residue bin, which is almost
empty. Hold on it. Audio: workshop room tone and the fan, one soft scanner beep, then quiet.
No dialogue.
```

---
---

# Off-World Logistics

## 41 · The Orbital Tug Pool "Mule"

**Upload:** `tug_pool_blueprint.png` · `tug_pool_render.png`
**Ingredient label:** `Tug 04 reusable orbital tug`
**Hook:** *Every shipper in orbit builds its own ship, flies it once, and scuttles it.*

**Shot A — Blueprint ignition** *(Frames to Video: blueprint → render)*
```
Vertical 9:16. Opens on a cyanotype blueprint sheet filling the frame — prussian-blue paper, fine white and cyan linework, faint drafting grid, monospaced title block reading OT-1 MULE. The camera pushes in along the dashed transfer ellipse linking two concentric orbit rings around a banded planetary body, following it to the small tug-and-payload icon riding the ellipse. The linework glows and lifts off the page into three dimensions; the grid dissolves into the black of cislunar space, and the wireframe fills with real material — a squat cylindrical core in gold and white thermal blanketing, two spherical propellant tanks, a cluster of attitude thrusters, a docking ring at the bow — becoming exactly the tug in the final frame. One continuous move, no cut, and the finished hardware does not morph. Audio: paper rustle, drafting-pen scratch, a rising tone settling into a low electrical hum. No dialogue.
```

**Shot B — Hero action** *(Ingredients to Video)*
```
Vertical 9:16. Reference image is the exact machine: match its geometry, proportions, tank layout, thruster placement, docking ring and stencilled markings precisely. Do not redesign, restyle, or add hardware that is not in the reference. The Tug 04 reusable orbital tug closes the last few centimetres on a propellant depot in high orbit, a boxy cargo container clamped to its mid-section on standardised hardpoints. Fine attitude thrusters fire tiny corrective puffs; alignment guides on the docking ring line up with the depot's matching ring. The camera holds a slow three-quarter orbit around the pair as contact is made, a soft mechanical latch visible at the ring. Distant grey cratered moon below, black star-dusted sky, hard sunlight with a rim of light along the hull. Audio: structure-borne — faint thruster ticks conducted through the frame, a mechanical clunk of capture, then quiet. No dialogue.
```

**Shot C — Payoff / scale** *(Ingredients to Video, or Extend Shot B)*
```
Vertical 9:16. Same tug, matched exactly to the reference image. The camera pulls back to reveal the wider scene: three more tugs of the same design holding position nearby at different distances from the depot, one departing on a long outward spiral, one arriving from below, one idle and refuelling — a small fleet, not a lone vehicle. The depot's radiator panel catches the sunlight. Hold on the wide view. Audio: the mechanical hum fades to the quiet room tone of vacuum, then silence. No dialogue.
```

---

## 42 · The Ballistic Cargo Capsule "Trebuchet's Child"

**Upload:** `cargo_capsule_blueprint.png` · `cargo_capsule_render.png`
**Ingredient label:** `Cargo 17 ballistic entry capsule`
**Hook:** *A catalogue full of elaborate machines for going up deserves one honest, stupid machine for coming down.*

**Shot A — Blueprint ignition** *(Frames to Video: blueprint → render)*
```
Vertical 9:16. Opens on a cyanotype blueprint sheet filling the frame — prussian-blue paper, fine white and cyan linework, faint drafting grid, monospaced title block reading BC-1 TREBUCHET'S CHILD. The camera pushes in along the bold entry-corridor trajectory drawn between two dashed atmosphere arcs above a curved planetary horizon, following it down to the small blunt capsule icon with its detached bow shock. The linework glows and lifts off the page into three dimensions; the grid dissolves into a high, thin desert sky, and the wireframe fills with real material — a squat truncated-cone shield in charred dark grey, scuffed white thermal blanketing above it, a packed parafoil at the crown — becoming exactly the capsule in the final frame. One continuous move, no cut, and the finished hardware does not morph. Audio: paper rustle, drafting-pen scratch, a rising tone settling into a thin high-altitude wind. No dialogue.
```

**Shot B — Hero action** *(Ingredients to Video)*
```
Vertical 9:16. Reference image is the exact machine: match its geometry, proportions, heat-shield shape, blanketing, parafoil and stencilled markings precisely. Do not redesign, restyle, or add hardware that is not in the reference. The Cargo 17 ballistic entry capsule descends under its open grey ram-air parafoil a few hundred metres above a wide flat recovery zone, its underside still faintly glowing at the seams and streaked with scorch marks from entry. Control-line actuators at the risers twitch, steering it gently toward a marked landing target visible far below. The camera holds a slow diagonal tracking shot alongside the canopy, low sun throwing long shadows across the desert floor. Audio: structure-borne creak of the risers, thin wind past the canopy fabric, no engine, no dialogue.
```

**Shot C — Payoff / scale** *(Ingredients to Video, or Extend Shot B)*
```
Vertical 9:16. Same capsule, matched exactly to the reference image. It settles onto the crushable base with a soft compression and topples gently onto its side; the parafoil collapses and drifts down over the ground beside it. The camera stays low and wide, holding the small dust plume kicked up at touchdown as a distant recovery vehicle begins moving toward it across the flat desert. Hold on the still capsule, scorched and intact. Audio: a soft crushing thud, canopy fabric settling, then quiet ambient wind. No dialogue.
```

---

## 43 · The Regolith Paved Airstrip "Runway"

**Upload:** `airstrip_blueprint.png` · `airstrip_render.png`
**Ingredient label:** `Pad 01 certified landing pad`
**Hook:** *A patch of fused regolith is a construction outcome. A facility is a promise.*

**Shot A — Blueprint ignition** *(Frames to Video: blueprint → render)*
```
Vertical 9:16. Opens on a cyanotype blueprint sheet filling the frame — prussian-blue paper, fine white and cyan linework, faint drafting grid, monospaced title block reading RA-1 RUNWAY. The camera pushes in on the concentric site plan, travelling inward through the dashed exclusion ring and the bold bound-area circle to the cross-shaped touchdown marking at the centre. The linework glows and lifts off the page into three dimensions; the grid dissolves into a grey lunar plain under a black sky, and the wireframe fills with real material — a broad circular apron of dark glassy sintered regolith, a high-contrast cross marking with a bright centre target, squat survey monuments topped with retroreflectors at the corners, a cargo lander on four splayed legs at the centre — becoming exactly the pad in the final frame. One continuous move, no cut, and the finished hardware does not morph. Audio: paper rustle, drafting-pen scratch, a rising tone settling into near silence. No dialogue.
```

**Shot B — Hero action** *(Ingredients to Video)*
```
Vertical 9:16. Reference image is the exact landing pad: match its apron geometry, sintered surface, cross marking, pad identifier, survey monuments, placards and lander precisely. Do not redesign, restyle, or add hardware that is not in the reference. The cargo lander settles the last metre onto the pad centre, its throttled engine firing a pale, almost invisible plume. Beyond the pad's edge, loose grey regolith is scoured into flat, straight ballistic streaks that fly outward and fall without billowing — no air to hold them up — while on the fused pad itself nothing lifts. Four splayed legs flex as the footpads touch the crust; the engine cuts instantly and the plume vanishes. The camera holds a low three-quarter angle on the sharp edge where fused pad meets loose ground. Harsh low sunlight, long knife-edged shadows, black star-dusted sky. Audio: structure-borne — deep engine rumble conducted through the frame, RCS thruster ticks, a heavy leg-strut clunk, then abrupt silence. No dialogue.
```

**Shot C — Payoff / scale** *(Ingredients to Video, or Extend Shot B)*
```
Vertical 9:16. Same pad, matched exactly to the reference image. The camera rises slowly and pulls back until the whole concentric arrangement is visible from above — the dark circular apron, the cross marking, the four monuments at its corners, a short paved track leading toward a distant habitat, the lander small at the centre. Outside the pad edge, the last of the dust settles straight down. Hold on the wide view. Audio: the rumble fades with distance through the ground to nothing, then silence. No dialogue.
```

---

## 44 · The Subsurface Freight Line "Cuniculus"

**Upload:** `freight_line_blueprint.png` · `freight_line_render.png`
**Ingredient label:** `Freight 04 lava-tube freight train`
**Hook:** *The lava had no idea where we'd want to go — but it dug the tunnels anyway.*

**Shot A — Blueprint ignition** *(Frames to Video: blueprint → render)*
```
Vertical 9:16. Opens on a cyanotype blueprint sheet filling the frame — prussian-blue paper, fine white and cyan linework, faint drafting grid, monospaced title block reading SF-1 CUNICULUS. The camera pushes in on the long geological section, dropping down a skylight shaft with its hoist line into the cavern and following the double-line track between the two stations to the small train. The linework glows and lifts off the page into three dimensions; the grid dissolves into the total darkness of a lava tube, and the wireframe fills with real material — a low flatbed rail vehicle carrying two sealed grey containers, steel rails on a graded basalt floor, a flat reaction rail between them, work lights switching on — becoming exactly the train in the final frame. One continuous move, no cut, and the finished hardware does not morph. Audio: paper rustle, drafting-pen scratch, a rising tone settling into a low electrical hum. No dialogue.
```

**Shot B — Hero action** *(Ingredients to Video)*
```
Vertical 9:16. Reference image is the exact train: match its geometry, proportions, container layout, coil housings, work lights and stencilled markings precisely. Do not redesign, restyle, or add hardware that is not in the reference. The Freight 04 train glides along its rails through the lava tube, hard white work lights throwing beams down the tunnel and picking out the rough, ropy texture of the frozen-lava walls and the curved ceiling far above; beyond the beams the cave falls into total blackness. Large fallen breakdown blocks pass at the edge of the light, on the untouched floor beyond the graded track bed. The camera tracks low alongside at a three-quarter angle, matching the train's slow, steady speed. Audio: structure-borne — a low linear-motor hum conducted through the rails, a soft tick of the wheels over rail joints, nothing else. No dialogue.
```

**Shot C — Payoff / scale** *(Ingredients to Video, or Extend Shot B)*
```
Vertical 9:16. Same train, matched exactly to the reference image. It passes the camera and recedes down the tube, its tail lamp shrinking to a point in the blackness. Far ahead, a single shaft of pale sunlight falls through a skylight onto the cave floor, lighting hanging dust and a station platform with a hoist frame. Hold on the shaft of light. Audio: the hum fades with distance through the rails to nothing, then silence. No dialogue.
```

---

# Settlement Systems

## 45 · The Dust-Storm Seal Gate "Janus"

**Upload:** `seal_gate_blueprint.png` · `seal_gate_render.png`
**Ingredient label:** `Seal Gate 02 dust decontamination vestibule`
**Hook:** *The hull will hold. The door is where the planet gets in.*

**Shot A — Blueprint ignition** *(Frames to Video: blueprint → render)*
```
Vertical 9:16. Opens on a cyanotype blueprint sheet filling the frame — prussian-blue paper, fine white and cyan linework, faint drafting grid, monospaced title block reading SG-1 JANUS. The camera pushes in along the horizontal section, starting among the scattered dust dots at the dirty left end and travelling through three chambers separated by bold door lines, past the row of electrode ticks beneath the floor of Zone 2, toward the clean habitat at the right. The linework glows and lifts off the page into three dimensions; the grid dissolves into cool clinical interior light, and the wireframe fills with real material — matte white composite walls, a floor of dark grey dielectric panels with fine electrode traces, a high-voltage drive cabinet with status lights, a sealed inner hatch with a viewport — becoming exactly the vestibule in the final frame. One continuous move, no cut, and the finished hardware does not morph. Audio: paper rustle, drafting-pen scratch, a rising tone settling into a low electrical hum. No dialogue.
```

**Shot B — Hero action** *(Ingredients to Video)*
```
Vertical 9:16. Reference image is the exact vestibule: match its wall panels, dielectric floor, drive cabinet, grilles, hatch, placards and stencilled markings precisely. Do not redesign, restyle, or add hardware that is not in the reference. A dusty ochre-red Mars suit stands motionless on the floor panels facing the inner hatch, its boots and lower legs caked in fine rust-coloured dust. The sweep activates: a faint drift of dust lifts from the panel surface and travels in a slow wave toward the floor-level grille at the outer end, leaving the panel visibly cleaner behind it. Status lights on the drive cabinet pulse and the readout updates. The camera holds a low three-quarter angle at boot height, then rises slowly. Cool clinical interior lighting, with warm dusty orange light through the outer hatch window. Audio: a low electrical hum with a faint crackle, soft airflow into the return grilles. No dialogue.
```

**Shot C — Payoff / scale** *(Ingredients to Video, or Extend Shot B)*
```
Vertical 9:16. Same vestibule, matched exactly to the reference image. The camera pulls back to take in the whole chamber — the swept floor, the suit now noticeably cleaner at the boots, the drive cabinet, the sealed inner hatch — and settles on the outer hatch window, where a dust-hazed pink-orange sky and rusty terrain glow. Hold on the window. Audio: the hum fades to quiet ventilation room tone. No dialogue.
```

---

## 46 · The Buried Greenhouse Vault "Demeter"

**Upload:** `greenhouse_vault_blueprint.png` · `greenhouse_vault_render.png`
**Ingredient label:** `Grow Vault 01 buried salad vault`
**Hook:** *A glass dome full of crops is a radiation hole with a farm in it.*

**Shot A — Blueprint ignition** *(Frames to Video: blueprint → render)*
```
Vertical 9:16. Opens on a cyanotype blueprint sheet filling the frame — prussian-blue paper, fine white and cyan linework, faint drafting grid, monospaced title block reading GV-1 DEMETER. The camera pushes in on the vertical section, starting at the surface collector and the small sun above it and following the narrow shielded light duct down through the banded layer of overburden into the pressurised vault with its stacked growing racks. The linework glows and lifts off the page into three dimensions; the grid dissolves into a saturated pink-violet glow, and the wireframe fills with real material — windowless pale composite walls, an arched ceiling, vertical racks of lettuce and herbs beneath slim LED bars, a narrow ceiling duct carrying optical fibre to a diffuser panel — becoming exactly the vault in the final frame. One continuous move, no cut, and the finished hardware does not morph. Audio: paper rustle, drafting-pen scratch, a rising tone settling into ventilation fans and a faint drip. No dialogue.
```

**Shot B — Hero action** *(Ingredients to Video)*
```
Vertical 9:16. Reference image is the exact vault: match its rack layout, LED bars, ceiling arch, duct, diffuser panel, placards and stencilled markings precisely. Do not redesign, restyle, or add equipment that is not in the reference. The camera tracks slowly down the central aisle past the stacked racks, vivid green lettuce and herbs saturated by the magenta glow of the LED bars above each shelf. Nutrient drip lines glisten, faint condensation clings to cool panels, and a technician in soft work clothes — back to camera, no face in frame — lifts a tray to inspect it. At the far end the ceiling duct's diffuser panel glows natural white, a clear contrast against the pink light. Humid, still air. Audio: ventilation fans, the soft drip of nutrient lines, a quiet tray scrape. No dialogue.
```

**Shot C — Payoff / scale** *(Ingredients to Video, or Extend Shot B)*
```
Vertical 9:16. Same vault, matched exactly to the reference image. The camera pulls back and rises to show the whole space — the full aisle of racks glowing magenta, the arched ceiling, the technician small among the crops — then settles on the single white daylight panel at the far end. Hold on it. Audio: fans and drips fade to quiet room tone. No dialogue.
```

---

## 47 · The Modular Pressure Spine "Vertebra"

**Upload:** `pressure_spine_blueprint.png` · `pressure_spine_render.png`
**Ingredient label:** `MP-1 qualification article 01`
**Hook:** *Pressure vessels don't fail in the middle of a wall. They fail where the wall stops being a wall.*

**Shot A — Blueprint ignition** *(Frames to Video: blueprint → render)*
```
Vertical 9:16. Opens on a cyanotype blueprint sheet filling the frame — prussian-blue paper, fine white and cyan linework, faint drafting grid, monospaced title block reading MP-1 VERTEBRA. The camera pushes in along the plan of the five-segment corridor with modules plugged in above and below, travelling down to the magnified detail circle of the single reinforced port. The linework glows and lifts off the page into three dimensions; the grid dissolves into a vast aerospace test hall, and the wireframe fills with real material — a thick-walled aluminium cylinder with two large circular side ports, each ringed by a thickened machined collar with rounded edges, slung inside an open steel water tank — becoming exactly the test article in the final frame. One continuous move, no cut, and the finished hardware does not morph. Audio: paper rustle, drafting-pen scratch, a rising tone settling into industrial hall ambience and a pump hum. No dialogue.
```

**Shot B — Hero action** *(Ingredients to Video)*
```
Vertical 9:16. Reference image is the exact test article: match its cylinder, port collars, water tank, strain-gauge wiring, gantry, data racks and stencilled markings precisely. Do not redesign, restyle, or add equipment that is not in the reference. Inside the test hall the MP-1 qualification article hangs in its tank as the pressure controller cycles, the water surface shivering faintly with each pulse. On the gantry a screen's cycle counter ticks upward. The camera tracks slowly along the gantry past bundles of strain-gauge wiring toward a port rim where marker lines and a dye-penetrant stain circle one corner. An engineer's gloved hand — no face in frame — points at a trace on a screen. Harsh industrial lighting reflecting off the water. Audio: a pump thump on each pressure cycle, hydraulic hiss, relay clicks, low hall reverb. No dialogue.
```

**Shot C — Payoff / scale** *(Ingredients to Video, or Extend Shot B)*
```
Vertical 9:16. Same test article, matched exactly to the reference image. The camera pulls back and rises over the tank until the whole hall is in frame — the suspended segment, the gantry, the data racks — then settles on the cycle counter rolling over another digit. Hold on it. Audio: a pump thump on each cycle, fading into hall tone. No dialogue.
```

---

## 48 · The Thermal Mass Battery Wall "Hypocaust"

**Upload:** `thermal_battery_blueprint.png` · `thermal_battery_render.png`
**Ingredient label:** `Heat Store 01 survival heat store`
**Hook:** *A settlement's first need through a fourteen-day night isn't power. It's not freezing.*

**Shot A — Blueprint ignition** *(Frames to Video: blueprint → render)*
```
Vertical 9:16. Opens on a cyanotype blueprint sheet filling the frame — prussian-blue paper, fine white and cyan linework with amber accents marking heat flow, faint drafting grid, monospaced title block reading TB-1 HYPOCAUST. The camera pushes in on the vertical section, following the bold amber arrow from the concentrator dish at the surface down into the loose regolith jacket and the dense coursed core with its winding serpentine heat pipes. The linework glows and lifts off the page into three dimensions; the grid dissolves into a lunar late afternoon under a black sky, and the wireframe fills with real material — dark sintered regolith blocks laid in neat courses, copper-coloured heat-pipe manifolds in insulated conduit, a heaped jacket of pale loose regolith, a small tracking dish — becoming exactly the heat store in the final frame. One continuous move, no cut, and the finished hardware does not morph. Audio: paper rustle, drafting-pen scratch, a rising tone settling into near silence. No dialogue.
```

**Shot B — Hero action** *(Ingredients to Video)*
```
Vertical 9:16. Reference image is the exact heat store: match its block courses, copper manifolds, conduit, data-logger box, placard, excavator rover and dish precisely. Do not redesign, restyle, or add hardware that is not in the reference. The blade of a small excavator rover spills pale loose regolith over the exposed top of the dark block; the grains fly in short, flat ballistic arcs and fall straight back down without billowing. Copper manifolds glint against the dark masonry, and the small data-logger readout holds steady. The sun is very low on the horizon, throwing extremely long, sharp shadows. The camera holds a three-quarter angle and dollies slowly along the block face. Audio: structure-borne — the rover's motor hum conducted through the ground, soft grain ticks against the conduit. No dialogue.
```

**Shot C — Payoff / scale** *(Ingredients to Video, or Extend Shot B)*
```
Vertical 9:16. Same installation, matched exactly to the reference image. As the sun touches the horizon, the camera pulls back to show the jacket now a smooth mound beside the habitat, the concentrator dish dark, and the habitat's warm window lights glowing as the long shadows merge into night. Hold on the lit windows. Audio: the hum fades to nothing, then silence. No dialogue.
```

---

# Life Support & Agriculture

## 49 · The Urine-to-Water Cascade "Lethe"

**Upload:** `lethe_blueprint.png` · `lethe_render.png`
**Ingredient label:** `Brine crystalliser assembly UW-1 Phase A`
**Hook:** *Most machines are hard because physics is hard. This one is hard because people are.*

**Shot A — Blueprint ignition** *(Frames to Video: blueprint → render)*
```
Vertical 9:16. Opens on a cyanotype blueprint sheet filling the frame — prussian-blue paper, fine white and cyan linework, faint drafting grid, monospaced title block reading UW-1 LETHE. The camera pushes in along the descending staircase of six equipment boxes, past the long red dashed return line beneath them, and settles on the third box, the brine crystalliser. The linework glows and lifts off the page into three dimensions; the grid dissolves into the even light of a clean-room assembly bay, and the wireframe fills with real material — a white aluminium rack with its front panel removed, a shallow stainless-steel drying tray with a scraper blade inside a copper heat-exchange jacket, a small vacuum pump, white-labelled valves, tidy PTFE tubing — becoming exactly the module in the final frame. One continuous move, no cut, and the finished hardware does not morph. Audio: paper rustle, drafting-pen scratch, a rising tone settling into clean-room fan hum. No dialogue.
```

**Shot B — Hero action** *(Ingredients to Video)*
```
Vertical 9:16. Reference image is the exact module: match its rack, drying tray, scraper, copper jacket, pump, valves, tubing, front display and identification plate precisely. Do not redesign, restyle, or add hardware that is not in the reference. The crystalliser runs: the motorised scraper blade makes a slow pass across the stainless drying tray, lifting a pale grey-white crust into curled plates. The recovery percentage and mass figure on the front bezel display tick steadily upward, and a faint heat shimmer hangs over the copper jacket. The camera tracks slowly across the open rack at a three-quarter angle. Soft, even clean-room lighting. Audio: the motorised scraper's whir, a vacuum pump hum, a click of a solenoid valve. No dialogue.
```

**Shot C — Payoff / scale** *(Ingredients to Video, or Extend Shot B)*
```
Vertical 9:16. Same module, matched exactly to the reference image. The camera settles close on the open dish beside the rack, where the dried mineral cake lies cracked into plates like dried mud, blue-gloved fingertips resting at the edge of frame for scale, then pulls back to the whole rack with its display reading steadily. Hold. Audio: the pump winds down to quiet, one last valve click. No dialogue.
```

---

## 50 · The Mycelial Digestion Vat "Saprophyte"

**Upload:** `saprophyte_blueprint.png` · `saprophyte_render.png`
**Ingredient label:** `Colonisation rack Train A food stream`
**Hook:** *The water plant takes the liquid. This one takes what's left.*

**Shot A — Blueprint ignition** *(Frames to Video: blueprint → render)*
```
Vertical 9:16. Opens on a cyanotype blueprint sheet filling the frame — prussian-blue paper, fine white and cyan linework, faint drafting grid, monospaced title block reading MY-1 SAPROPHYTE. The camera pushes in across the two process trains inside the containment shell, passing over the bold red-hatched air-gap band, and settles on the dark colonisation rack in the upper train. The linework glows and lifts off the page into three dimensions; the grid dissolves into the cool even light of a sealed research facility, and the wireframe fills with real material — a stainless-steel rack holding twelve translucent gas-permeable sleeves on perforated shelves, packed with straw-coloured residue as white mycelium creeps through it — becoming exactly the rack in the final frame. One continuous move, no cut, and the finished hardware does not morph. Audio: paper rustle, drafting-pen scratch, a rising tone settling into the hum of a filtered air handler. No dialogue.
```

**Shot B — Hero action** *(Ingredients to Video)*
```
Vertical 9:16. Reference image is the exact rack: match its shelf layout, translucent sleeves, mycelium coverage, paper scale strips, batch cards, pressure gauge, filter housing and laminated sign precisely. Do not redesign, restyle, or add equipment that is not in the reference. The camera tracks slowly up the face of the rack, past sleeves that run from almost solid even white at the bottom to pale brown substrate with a creeping white front at the top, the printed scale strips and handwritten batch cards in frame. A gloved technician's hand — no face in frame — enters and rests lightly on one sleeve without opening it. On the wall behind, the differential pressure gauge hovers slightly below zero. Cool, even LED lighting, quiet and clinical. Audio: the hum of the filtered air handler, a faint rustle of a glove on a sleeve. No dialogue.
```

**Shot C — Payoff / scale** *(Ingredients to Video, or Extend Shot B)*
```
Vertical 9:16. Same rack, matched exactly to the reference image. The camera pulls back to show the whole room — the rack, the sealed epoxy floor, the filter housing at the ceiling line, the laminated sign on the rack end — then settles on the even white mat of the lowest sleeves. Hold. Audio: the air handler's hum fades to quiet room tone. No dialogue.
```

---

# Troubleshooting

| Problem | Fix |
|---|---|
| Veo invents a different machine | Your ingredient label and the prompt wording disagree. Re-label the ingredient with the exact name from the prompt, and shorten the prompt — the reference contract plus one action beat is enough. |
| The finished hardware morphs or melts in Shot A | Shot A is doing too much. Cut the middle of the prompt, keep first frame = blueprint and last frame = render, and keep the clause *"the finished hardware does not morph."* |
| Gibberish letters appear on panels | The negative prompt is missing. Paste the universal negative list, and delete any quoted stencil text from the prompt — let the reference image carry the markings. |
| Lunar or Martian dust billows like Earth dust | Add: *"dust rises in slow ballistic arcs and falls straight back, no billowing, no suspended cloud."* |
| Sound in vacuum feels wrong — whooshes, roars, explosions | Restate the structure-borne clause and add `no whoosh, no roar, no explosion` to the negative prompt. |
| The subject drifts out of the vertical safe area | Add: *"subject centred in the middle vertical third, headroom top and bottom."* |
| 9:16 unavailable for your model | Generate 16:9 and centre-crop — every prompt keeps critical detail centred. |
| Shots B and C don't match each other | Generate C by **extending** the winning B clip in Scenebuilder rather than from a fresh prompt. |

---

# Batch checklist

- [ ] Blueprint SVGs exported and padded to 1080 × 1920 PNGs
- [ ] Hero renders generated and named to match the ingredient labels
- [ ] Flow set to 9:16, audio on, 2–4 outputs per prompt
- [ ] Universal negative prompt saved in the negative field
- [ ] Shot A / B / C generated per concept, best takes kept
- [ ] Assembled A → B → C in Scenebuilder, hook text overlaid on A
- [ ] GitHub handle on the last second of C, link in the pinned first comment

---
**Author:** Wijerathne Arachchilage Sandun Priyankara Wijerathne
Email: sandunwijerathne51@gmail.com · [LinkedIn](https://www.linkedin.com/in/sandun-wijerathne/) · [GitHub](https://github.com/sandunwijerathne/)
*Concept studies — grounded in known physics. Contact me if you want to collaborate.*
