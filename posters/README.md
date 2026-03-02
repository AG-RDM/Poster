# Posters

This directory contains all conference posters. Files are stored flat — no sub-folders — using a smart naming convention so every poster is easy to locate at a glance.

## Naming Convention

`YYYY_ConferenceAbbr_<type>.<ext>`

| Part              | Description                                            | Example         |
|-------------------|--------------------------------------------------------|-----------------|
| `YYYY`            | Four-digit year of the conference                      | `2024`          |
| `ConferenceAbbr`  | Short, recognizable abbreviation of the conference     | `SciPy`, `EAGE` |
| `<type>`          | File role: `poster` (PDF/source) or `abstract` (notes) | `poster`        |
| `<ext>`           | File extension matching the format                     | `pdf`, `pptx`   |

## File Layout

```
posters/
├── YYYY_ConferenceAbbr_poster.pdf      # Final poster (PDF)
├── YYYY_ConferenceAbbr_poster.<ext>    # Source file (e.g., .pptx, .tex, .ai)
└── YYYY_ConferenceAbbr_abstract.md     # Conference details and abstract
```

## Example `abstract.md`

Name the file `YYYY_ConferenceAbbr_abstract.md`, e.g. `2024_SciPy_abstract.md`:

```markdown
# <Poster Title>

**Conference:** <Full Conference Name> (<Abbreviation>)  
**Date:** <Month> <Year>  
**Location:** <City, Country>  
**Authors:** <Author 1>, <Author 2>, ...

## Abstract

<Short abstract of the poster content.>
```
