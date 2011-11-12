ReadMe
------
Files used in the creation of a visual instruction guide for the [Prusa Mendel](https://github.com/prusajr/PrusaMendel), a [RepRap](http://reprap.org) 3D Printer.

This project contains:
	
*   src/Prusa_Mendel_Visual_Instructions.tex: Document source in Latex format
*   src/models/Prusa Mendel.skp: Google Sketchup 8 Model of Prusa Mendel
*   src/graphics/*.png: Graphics for the document

Requirements
------------
*   LaTeX: works well with texlive
*   pstricks: pstricks is a LaTeX extension, used here for text outlines
*   pdflatex: to build

Building
--------
To build, enter the src directory in a terminal window and type:

    pdflatex -shell-escape Prusa_Mendel_Visual_Instructions.tex

Licensing
----------
*   Prusa Mendel: [GPL](http://reprap.org/wiki/GPL)
*   This Document: [GFDL](http://www.gnu.org/licenses/fdl.html)
