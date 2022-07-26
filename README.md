# Bidirectional Simple Resume

A template based on my previous resume. 
It has full support for both LTR and RTL languages.
Usage is permitted under the guidelines and requirements of LPPL 1.3c.
I've drastically changed my resume since and I plan to archive this repository soon.

## Resume Structure

### [1] main.tex

**Head**

- Metadata (hyperref)
- Language settings (bidi, inputenc)
- A macro to allow image links
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

### [2] sections-*language*.tex

- Title
- (Currently) unused option to link a recent online copy of the resume
- Link to the other language (e.g. "Click here for Hebrew")
- Abstract
- Basic information section
- Standard resume sections
- Sub-sections and alternative formatting

### [3] abstracteng.tex and abstractheb.tex

Brief self description.

### [4] ico

Various images, mainly for the contact info section.













## To Do

- [X] Template file

- [ ] Glossary

## Preview

![Template Preview](https://github.com/kiril-u/kiril-resume-2021/blob/main/ico/template-preview.png?raw=true)
