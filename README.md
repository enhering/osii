# Open Scientific Instrumentation Initiative (OSII)

> *Science should not be limited by the cost of its tools.*

---

A commercial dilution refrigerator costs upward of $500,000. A precision spectrometer, tens of thousands. A motorized positioning stage, thousands — for a component that moves a sample a few millimeters.

These are not exotic items. They are the everyday tools of experimental science. And for most researchers in the world — at smaller universities, in developing countries, in independent labs — they are simply out of reach.

This is not a technical problem. The physics is understood. The manufacturing methods exist. The barrier is economic, and it is artificial.

**OSII exists to remove it.**

---

## Why Now

For most of history, building precision scientific instruments required either expensive proprietary tooling or access to a well-equipped machine shop. That has changed.

Parametric CAD tools like OpenSCAD are free and run on any computer. 3D printing has made complex geometries accessible to anyone. Affordable CNC services and open PCB fabrication houses mean that a design shared online can be physically built almost anywhere in the world within days. The infrastructure for open hardware has quietly matured. What was impractical a decade ago is now straightforward.

The moment to build this exists. OSII is the attempt to use it.

---

## What We Do

We design, document, and share scientific instrumentation that anyone can build.

The model is borrowed from open-source software: release everything — CAD files, bills of materials, fabrication notes, supplier lists — under a free license. Let anyone build it, improve it, and share it back. The open-source movement democratized computing. We aim to do the same for the lab bench.

Every OSII project ships with:

- **Full documentation** — CAD files (OpenSCAD), BOM, fabrication notes, supplier lists, and a contributor log.
- **Stable interfaces** — Core module interfaces are versioned so that components from different contributors remain interchangeable.
- **A free license** — GNU GPL v3. Download, build, modify, redistribute. No strings.
- **Version control** — Everything lives in public repositories. History is preserved. Contributions are traceable.

---

## Projects

| Project | Status | Description |
|---|---|---|
| Low-temperature cryostat | 🔧 In development | Modular cryostat platform for millikelvin experiments |

*More projects will be added as the community grows. Have a design to contribute? Open an issue or start a discussion.*

---

## Where We Start

The first seed project targets **low-temperature equipment** — cryostats, thermal stages, and related hardware. This is one of the most expensive corners of experimental physics, and one where open designs could have the greatest impact.

The framework supports any kind of instrumentation. Low-temperature is where we start. It won't be where we stop.

---

## Technology

- **CAD:** [OpenSCAD](https://openscad.org/) — parametric, scriptable, version-control friendly. No proprietary formats.
- **Version control:** GitHub, GitLab, or Bitbucket.
- **Everything else:** Open standards throughout. No one should be locked out by software they can't afford.

---

## How to Contribute

1. Clone a project repository.
2. Build it. Improve it. Branch it.
3. Share your changes back.
4. Talk to the community on the forum.

Sometimes good engineering means closing a branch and starting fresh with better fundamentals. That's not failure — that's how the work moves forward.

---

## License

GNU General Public License v3. See `LICENSE`.

## Creator

Eduardo N. Hering — physicist, PhD.
enhering@gmail.com

---

*If this resonates with you, share it. The more people who know this exists, the faster it becomes real.*
