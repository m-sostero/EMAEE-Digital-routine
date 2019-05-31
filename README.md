# beamer-theme-INAPP

This repository provides a `LaTeX` theme implementation for the `beamer` 'documentclass' adequately consistent with the **INAPP** official graphical design.

## Usage

In order to use the **INAPP** theme, the following files should be included within the same directory where the main `*.tex` file resides:
 * `beamercolorthemeINAPP.sty`
 * `beamerinnerthemeINAPP.sty`
 * `beamerouterthemeINAPP.sty`
 * `beamerthemeINAPP.sty`
 * `frame_background.png`
 * `lastframe_background.png`
 * `titlepage_background.png`
 
The **INAPP** theme should be explicitly included in the *preamble* of the main `*.tex` file with the folliwing command:

```TeX
\usetheme{INAPP}
```

In order to correctly render the last frame, please compile **twice** with your favourite `LaTeX` engine.
 
