# Car Radio

KiCad 10 hardware project.

## Layout

Create the KiCad project in this folder (File > New Project, uncheck "Create a new folder for the project") so `Car Radio.kicad_pro`, `.kicad_sch` and `.kicad_pcb` sit at the repo root.

## Version control notes

- `.kicad_prl` (per-user UI state) and `.history/` (KiCad's local history) are ignored.
- Project-local symbol/footprint libraries and `sym-lib-table` / `fp-lib-table` are tracked.
- Gerbers and other generated output are tracked by default if placed in `fab/`; `build/` is ignored.
