# Soft Skills for Work

The people skills that move careers: listening, writing and speaking clearly, feedback, conflict, negotiation, time and focus, decisions and leading others, built on proven frameworks you can use tomorrow.

Part of the [Yaaddi](https://github.com/yaaddi-courses) course catalog: a spaced-repetition flashcard course, ready to build and validate with the standard Yaaddi course tooling.

## Sources and accuracy

Built on well-known frameworks (Tuckman's stages, SBI feedback, the Thomas-Kilmann conflict modes, BATNA, the Eisenhower matrix, the Pomodoro technique, GROW, STAR and others). Each term in the glossary links to a reference page. Specific numbers (such as the 25-minute Pomodoro) follow the usual definition of the technique.

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
