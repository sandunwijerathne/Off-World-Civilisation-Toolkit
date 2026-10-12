# The Urine-to-Water Cascade

*Category: Life Support & Agriculture · Off-World Civilisation Toolkit · Concept 49*

Most machines in this catalogue are hard because physics is hard. This one is hard because people are.

Recovering drinking water from urine is not a frontier. It is flight hardware, and it has been running in orbit for years. So this study does something it hasn't done before: it concedes the main process at the start, and spends all four pages on the parts nobody solved.

**There are four of them. Three are chemical.**

**Urea.** It's the biggest single solute in urine — about two per cent by mass, more than all the salts put together. Harmless as urea. The trouble is that it doesn't stay urea: bacteria on every surface a crew touches carry the enzyme urease, which splits it into ammonia and carbon dioxide within hours. Ammonia is volatile, so it rides the steam straight into your product water; it's also alkaline, so it raises the pH, which converts more nitrogen into the gaseous form, which raises the pH further. The process feeds itself.

The escape is one number. Ammonia and ammonium are the same nitrogen either side of an acid–base equilibrium with a pKa near 9.2. Below pH 6 it's all ammonium — an *ion*, and ions cannot evaporate. Above pH 9 it's all ammonia, a gas that goes wherever the water goes. So pH isn't a water-quality reading in this machine. It's a switch that decides whether nitrogen is physically able to leave the liquid. Stage 1 holds the feed at pH 2 and the still simply has nothing volatile to carry.

**Small organics.** Distillation sorts by volatility, and plenty of organic molecules in a biological fluid are about as volatile as water. Distillation doesn't remove those. It does the opposite favour: it throws out the salts, which were never the danger, and hands you a product that looks pristine and *conducts* like pure water. Conductivity — the cheapest, most reassuring gauge on the panel — is blind to exactly this. The answer isn't separation, it's oxidation: oxygen over a platinum-group catalyst at 130 °C burns them to CO₂ and water.

**Gypsum.** Urine leaves the body already close to saturated in calcium sulfate. Concentrate it and gypsum crystallises out — not as sludge, but as hard scale on the hottest surface in the machine. That, not energy, is what caps recovery: the run has to stop while the brine is still pumpable, stranding roughly a quarter of the water in a tank of concentrate you then have to store or dump.

**The fourth problem is that a test result is not the same thing as being believed.**

## What UW-1 "Lethe" does about it

Six stages, descending:

1. **Intake and Lock** — acidify to pH 2, kill the urease. Nitrogen is now an ion and cannot board the steam.
2. **Vapour-compression still** — evaporate at low pressure, compress the vapour slightly so it condenses *hotter* than the brine boils, and condense it against the far side of the evaporator wall. The latent heat released by condensing is exactly the latent heat needed for evaporating, so it's handed straight back and used again. This turns ~630 Wh per litre into something nearer 150. It's a heat pump with water as the working fluid, and it's why the whole thing closes energetically.
3. **Brine crystalliser** — the stage conventional designs leave out, which is why they stall near three-quarters. Instead of banking concentrate, dry the brine all the way to a solid cake in a vacuum tray, using low-grade waste heat from the thermal mass battery wall (Concept 48), which has heat to spare and nothing better to do with the bottom of its temperature range. Recovery goes from ~75% to ~97%, and the brine tank disappears. What's left is a few hundred grams a day per person of gypsum, salt and phosphate — mineral the greenhouse would otherwise have imported.
4. **Ammonium bed** — a clinoptilolite column. This zeolite has a marked appetite for the ammonium ion, which is why terrestrial aquaculture and wastewater plants have used it for sixty years. It catches whatever nitrogen slipped past the pH lock, is regenerated with heat, and — the point — the recovered ammonia isn't waste. It goes to the root tower (Concept 26) as fertiliser. Nitrogen leaves the water loop by entering the food loop, which is where it was always headed.
5. **Catalytic polish** — burn the organics the still carried over, then ion-exchange and a silver residual.
6. **The Witness** — and this is the stage that matters.

## The stage that isn't chemistry

Rozin and colleagues found that rejection of recycled water isn't driven by risk estimates at all. It's contagion reasoning: for a large fraction of people, contact with a contaminant confers a property that no purification reverses. The water stays repellent *even when the person accepts it's chemically pure*. Testing clean and being believed clean are two different achievements, and engineering only delivers the first.

So Stage 6 contains no novel instrument. Total organic carbon, conductivity, an ammonia electrode, UV fluorescence, a bacterial assay — all ordinary, all deliberately ordinary. What's actually being designed is the *sightline*. The product tap is a glass carafe standing in the galley, refilled by the machine itself, with the last twenty-four hours of every channel displayed above it. Failures are logged and alarmed by name, not quietly recycled, because a record that only ever reports success isn't evidence of anything. And a vial from every batch goes into a freezer, so that when somebody asks an awkward question in year four there's something left to ask it of.

A crew of six, selected and trained and briefed, will drink this. A settlement of six thousand — not selected, including children nobody consulted, including people who argue with each other in public — is a different population, and the honest position is that nobody has data on it, because it has never existed.

## Why the name

In Hades, the dead drank from Lethe and forgot the life behind them. Water leaving this plant has to be, in every measurable and every *imaginable* sense, water without a history.

And the only way to persuade anyone it has forgotten is to remember everything.

The water forgets. The ledger must not.

**Status: Phase 1 — the distillation core is flight-proven; the crystalliser and zeolite stages are ordinary terrestrial chemistry awaiting integration; the assurance layer has never been tested on a population that wasn't hand-picked.** Full paper, blueprint, and image prompts in this folder.

---
**Author:** Wijerathne Arachchilage Sandun Priyankara Wijerathne
Email: sandunwijerathne51@gmail.com · [LinkedIn](https://www.linkedin.com/in/sandun-wijerathne/) · [GitHub](https://github.com/sandunwijerathne/)
*Concept study — grounded in known physics. Contact me if you want to collaborate.*
