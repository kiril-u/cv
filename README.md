# Resume
[(kiril-resume-2021-1)](https://github.com/kiril-u/kiril-resume-2021-1)

My actual resume, written in XeLaTeX, both in English and in Hebrew.

**See folder export-latest for the PDFs**

## Structure

### main.tex

**"head area"**

- Metadata (hyperref)
- English settings (bidi, inputenc)
- Macro to allow image links in XeLaTeX
- Custom title command
- Font settings
- Link images
- Unnecessary shortcuts (it's for the general template)
- Custom section spacing and formatting
- No indentation
- Author name and date
**begin document**
- Adding english version
- Adding hebrew version

**end**

### kiril-resume-*language*.tex

- Title (there is a small difference between the english and hebrew version in formatting the title)
- Commented out option to link a recent online copy of the resume
- Link to the other language (e.g. "Click here for Hebrew")
- adding abstract
- Basic info section (this one can be edited as you wish)
- Regular section (x4)
- A sub section title (only on the first one)
- There are some sections which use the same format but are applied differently, e.g. langauges.

### abstract.tex and abstracthebrew.tex

Just the brief self description that's customary to add to resumes. There's no particular reason why it is its own file. An idea I had was to divide all sections into their own files, but that would be both unnecessary and also cause various problems with bidirectionality.

### export-latest

A pair of PDFs (the finished, compiled versions of your resume that you're going to send to employers). This might not be part of the future template repo.

### ico

A folder for the various graphics used throughout the document

### references

This folder contains three appendices to the resume that don't have to be part of this repo anymore since i link to the files directly on a hosted server. These files are kept here just as a backup.


Big thanks to https://github.com/lukesmithxyz for teaching me the basics and making me want to continue learning how to use LaTeX on my own.
