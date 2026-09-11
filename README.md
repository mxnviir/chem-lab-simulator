# ChemLab — Qualitative Salt Analysis

A drag-and-drop chemistry lab simulator for the qualitative analysis of a simple
salt, following the CBSE Class XI practical scheme. Identify the anion and the
cation of an unknown salt by doing the tests, not by reading the answer.

**One file, no build step, no dependencies.** Open `index.html` in a browser.

## What it does

- **37 salts** across 12 cations (NH₄⁺, Pb²⁺, Cu²⁺, Al³⁺, Zn²⁺, Mn²⁺, Co²⁺, Ni²⁺,
  Ba²⁺, Sr²⁺, Ca²⁺, Mg²⁺) and 5 anions (CO₃²⁻, Cl⁻, NO₃⁻, CH₃COO⁻, SO₄²⁻).
- **A rule engine, not a lookup table.** Reagents combine in the vessel, so the
  result depends on everything in it — order, excess, and whether it was heated.
  Excess NH₄OH on a copper salt gives the deep blue complex; one drop gives the
  pale blue precipitate.
- **The full procedure**: physical examination, flame and ash tests, preliminary
  and confirmatory anion tests, cation group separation I–VI, and confirmatory
  cation tests.
- **Drag and drop** reagents onto the test tube or beaker, the tube onto the
  burner to heat it, or into the sink to wash it. Works with mouse and touch.
- **Notebook** recording experiment, observation and inference, printable as a
  lab record.

## Teaching options

- **Inferences toggle** (off by default) hides what each observation means, so
  students deduce it themselves. A per-test reveal is available, and printing
  leaves the inference column blank to be filled in by hand.
- **Random pool** lets you restrict the unknown to the salts your class has
  covered. Searchable by name, formula, ion or group.
- **SFX toggle** (off by default) for pouring, effervescence and the burner.

A fresh unknown is drawn on every page load, never repeating the previous one.
Only your settings persist.

## Credits

Built from the CBSE Class XI qualitative inorganic analysis scheme.
