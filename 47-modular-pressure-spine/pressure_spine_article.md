# The Modular Pressure Spine

### Pressure vessels don't fail in the middle of a wall. They fail where the wall stops being a wall.

It's tempting to think a pressurised habitat's strength lives in its walls — how thick, what
material, how well made.

That's half the story, and the less dangerous half.

A smooth, continuous shell under internal pressure carries its load evenly and predictably. You
can design it with confidence. The danger is wherever continuity breaks: a door cut, a window
fitted, a pipe passed through, two sections bolted together. Each one is a discontinuity, and
**discontinuities are where structures actually fail**.

Now look at a settlement built from modules. From a structural point of view, it's *mostly*
discontinuities. Every module connects to its neighbours, and each connection is a hole in two
pressure vessels at once, joined by a seal and a clamp.

If every module designer invents their own connection, a fifty-module settlement contains dozens of
distinct joint designs — each novel, each needing its own analysis and qualification, each a place
where an error in somebody's assumptions becomes a breach.

The walls aren't the risk. The joints are, and there are too many kinds of them.

## One spine, one port

The MP-1 "Vertebra" is a central pressurised corridor — a spine — built from identical segments,
each carrying the same standardised port on its flanks.

Every functional module — lab, quarters, greenhouse vault, airlock, workshop — connects through that
one port geometry and nothing else. **Modules never connect to each other.** They connect to the
spine, which carries people, air, power, water, and data between them. Growth is additive: extend
the spine another segment, plug another module into a free port.

The spine is deliberately the most conservative, most over-built structure in the settlement,
because everything depends on it:

- **Bulkheads with pressure doors** between segments, so a breach isolates rather than depressurises
  the whole
- **Every port reinforced** to one qualified standard
- **Utilities in protected runs**, so modules can be added, removed, or replaced without disturbing
  anything else

The payoff: the functional modules can then be comparatively light, specialised, even experimental —
because they no longer carry the burden of inventing a safe way to join the rest of the habitat.
The innovation goes where it can be afforded, and the risk goes where it can be controlled.

## Why a hole is three times worse

In a thin-walled cylinder under internal pressure, the wall gets stretched two ways. The stress
around the circumference — the *hoop stress* — is proportional to pressure and radius, inversely
proportional to wall thickness, and **twice** the stress running along the cylinder's length.

That's why an over-pressured cylinder splits lengthwise instead of breaking into rings. So far, the
wall is behaving well.

Now cut a hole in it.

A circular hole in a plate under tension doesn't just remove material — it forces the load to flow
*around* the opening, and the stress at the hole's rim climbs to roughly **three times** the stress
far away. That's the classical result from Kirsch's 1898 elastic analysis. And sharp corners make it
far worse, because the concentration grows as the corner radius shrinks.

So every port in a pressure vessel is a local hotspot carrying several times the nominal stress,
and has to be compensated with reinforcement around its rim. A settlement full of bespoke joints has
a full set of bespoke hotspots, each reinforced according to somebody's separate calculation.

The spine replaces them with one.

## The lesson written at the corners of windows

Stress concentration turns lethal when you add *repetition*.

A structure that survives a load once may not survive it thousands of times. Cyclic loading grows
microscopic cracks at exactly the places where stress concentrates, until one reaches critical size
and the structure fails suddenly — at a load it had previously carried without trouble. That's
fatigue, and pressurised structures meet it every time they're pressurised and depressurised.

The defining lesson came from the **de Havilland Comet**, the world's first jet airliner. In 1954,
two broke up in flight.

The investigators did something that became the template for everything after: they put a complete
fuselage in a water tank and pressurised it, over and over, until it failed. The fatigue cracking
started at the **corners of openings in the pressurised skin** — the exact stress concentrations
Kirsch had described half a century earlier, cycled until they cracked through.

Two practices followed and have governed pressurised design ever since:

1. **Round the corners of every opening.**
2. **Qualify a structure by cycling a real example until it breaks** — don't trust the calculation.

The spine embodies both. Its single port is rounded and reinforced, and a full-scale spine segment
gets cycled to destruction *once*, so the joint every module depends on has been broken on purpose,
in a tank, rather than by surprise in service.

## The honest difficulties

**A standard freezes a decision.** This is the central cost. Once every module plugs into one port
geometry, changing it means changing everything. A port chosen too small, too weak, or too narrow for
a need nobody foresaw becomes a permanent constraint on growth. The history of incompatible docking
standards in human spaceflight shows how easily this happens — and how long it takes to undo.

**The spine is a single point of dependence.** Bulkheads isolate a breach, but a fault in the spine
itself affects everything attached. That's why it has to be the most conservative structure in the
settlement, not just a corridor.

**A qualified joint built badly is an unqualified joint.** Destructive testing only means something
if production joints match the tested one. So manufacturing quality control — possibly off-world,
possibly from local materials — becomes as important as the design.

**Layout gets constrained.** A linear or branching spine can put distant modules a long walk apart.

And **everyone has to agree to the standard before building to it** — an institutional achievement,
not an engineering one. Which is exactly why the spine is the first thing the Standards Bureau
(#60) exists to protect.

None of this is a barrier of physics. Stress concentration and pressure-cycling fatigue are among
the best-understood problems in structural engineering. The difficulty is choosing well, once, and
then living with the choice.

## Why it matters

Every element here is established practice. Pressure vessel design has codified rules for
reinforcing openings. Stress around holes has been understood for over a century. Full-scale fatigue
qualification became standard after the Comet. Modular stations built around standardised
berthing interfaces have flown for decades.

The near-term step is the qualification article — built and broken on Earth before any settlement
exists. And the most valuable thing about doing it *early* is that it forces the port specification
to be written, argued over, and fixed while changing it is still cheap.

The spine is a structure. Its port is a standard. Of the two, the standard is the part that matters
longest.

Pressurised structures have a long, costly habit of failing at their openings. It's far better that
a settlement's one joint has already been destroyed deliberately than that one of fifty improvised
joints is discovered, in service, to have been the wrong shape.

---

*Concept study — grounded in known physics. Contact me if you want to collaborate.*

**Wijerathne Arachchilage Sandun Priyankara Wijerathne**
sandunwijerathne51@gmail.com · [LinkedIn](https://www.linkedin.com/in/sandun-wijerathne/) · [GitHub](https://github.com/sandunwijerathne/)
