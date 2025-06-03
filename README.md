# LiteraturePrivateBiblatex
A literature collection based on the biblatex file format.

## Infos
- [JabRef BibTeX and biblatex](https://docs.jabref.org/cite/bibtex-and-biblatex)
- [JabRef string editor](https://docs.jabref.org/setup/stringeditor)
- Cite organizations with spaces in name, see [stackexchange](https://tex.stackexchange.com/questions/149769/how-to-cite-organizations-name-with-space-between-words)
- Authors should be written as "Meyers, Scott" or "Pollatschek, Nele"
- Website entries: create PDF with Edge, background on
- Remove month from date
- File cleanup with normal search
  - Remove entry "keywords"
  - Remove entry "ppn_gvk"
  - Remove entry "pagetotal"
  - Replace "Springer International Publishing" with "Springer" (location: "Cham")
- File cleanup with regex or other search
  - Search for two empty lines without text: `^\s*\n\s*\n`
  - Search for lines that contain "date" and "-": `.*\ date.*-.*`
  - Search for: `﻿` (only visible in Notepad++)