# World Geography

Learn the world: continents and oceans, how to read a map, every UN member country with its capital and flag, and the planet's great rivers, lakes, mountains, deserts and seas.

Part of the [Yaaddi](https://github.com/yaaddi-courses) course catalog: a spaced-repetition flashcard course, ready to build and validate with the standard Yaaddi course tooling.

## Sources and accuracy

- Countries: the 193 member states of the United Nations. Territories and states with limited recognition (for example Taiwan, Kosovo, Palestine) and the Holy See are not covered.
- Capitals were cross-checked against an open country dataset and written to avoid disputed claims: where a country has several capitals or a disputed one (Bolivia, South Africa, Sri Lanka, Eswatini, Nauru, Israel) the card says which capital it means, or asks a different fact.
- The flag of Afghanistan is not shown because the flag in use there is not recognised by every government.
- Flags come from Wikimedia Commons (public domain except Oman, OGL); see `ATTRIBUTIONS.md`.

This course is study help, not professional advice. See the [Terms of use](https://courses.yaaddi.com/terms/).

## Structure

- `meta.json`: course metadata (title, description, cover image, version)
- `source/`: authoring source (`meta.csv`, `units.csv`, `cards.csv`, `glossary.csv`, images)
- `plan.csv`: table of contents (not shipped in the zip)
- the built `.zip`: generated from `source/` via `build_course_zip.py`

## Editing this course

```bash
python validate_course.py . --source
python build_course_zip.py .
```
