# XeLaTeX Resume 2021
[(kiril-resume-2021-1)](https://github.com/kiril-u/kiril-resume-2021-1)

My actual resume, written in XeLaTeX, both in English and in Hebrew.

**See folder export-latest for the PDFs**

## main.tex

### Structure

**Head**

- Metadata (hyperref)
- Language settings (bidi, inputenc)
- A macro to allow image links in XeLaTeX
- Custom title
- Font settings
- Link images
- Aliases/shortcuts
- Custom section spacing and formatting
- No indentation
- Author name and date

**Body**

- Include English version
- Include Hebrew version

## kiril-resume-*language*.tex

- Title
- (Currently) unused option to link a recent online copy of the resume
- Link to the other language (e.g. "Click here for Hebrew")
- Abstract
- Basic information section
- Standard resume sections
- Sub-sections and alternativly formatted sections

## abstract.tex and abstracthebrew.tex

Brief self description.

## export-latest/

Compiled PDFs.

### ico

Graphics for the basic info section.

### To Do

- Template file

- Glossary
