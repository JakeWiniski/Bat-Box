# 3D-Printable Bat Box

A small modular bat-box design for FDM 3D printing. The model is divided into a main enclosure, a landing pad, and two roof variants so the parts can be printed separately and assembled after printing.

This is a personal design/prototyping project shared primarily as a printable object and portfolio example.

## Files

| File | Description | Mesh extents* |
|---|---|---:|
| `bat box.stl` | Main bat-box body / enclosure | 170 × 50 × 150 |
| `landing pad.stl` | Separate landing surface | 170 × 14 × 100 |
| `roof.stl` | Roof without modeled supports | 180 × 70 × 65 |
| `roof with supports.stl` | Alternate roof export with modeled support geometry | 180 × 70 × 65 |

\* STL files do not encode units. The dimensions above are taken directly from the model coordinates and are intended to be interpreted as millimeters.

## Printing

The parts are provided as STL meshes and can be imported into a standard FDM slicer.

No universal slicer settings are prescribed because appropriate orientation, support strategy, wall count, infill, and layer height will depend on the printer and filament being used.

For an outdoor installation, choose a filament appropriate for prolonged exposure to heat, moisture, and UV. PLA may be useful for test prints and prototypes, but a more temperature- and weather-resistant material is generally preferable for long-term exterior use.

The repository contains two roof variants. Print either `roof.stl` or `roof with supports.stl` as appropriate for your setup; both are not required for a single box.

## Assembly

1. Print the main box, landing pad, and one roof variant.
2. Remove any temporary support material and clean mating surfaces.
3. Dry-fit the components before permanently joining them.
4. Use an assembly and sealing method compatible with the filament and intended installation environment.

## Design Status

This design is shared as a personal experimental / maker project. It has not been presented here as a scientifically validated bat-habitat design or wildlife-management product.

Bat-house requirements can vary with species, climate, solar exposure, mounting location, chamber geometry, and other factors. Anyone installing the design for actual wildlife use should consult current regional bat-conservation guidance and adapt the design or installation as appropriate.

## Contributing

Remixes, print feedback, dimensional improvements, and other design iterations are welcome. If you modify the design, please document what you changed so future users can distinguish derivative versions from the original.

If editable CAD source files are added in the future, contributions through pull requests are welcome.

## License

This project is released under the **MIT License**.

See the `LICENSE` file for full terms.

## Author

**Jake Winiski**

