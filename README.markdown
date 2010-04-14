# TeX to text

This in an experimental package trying to provide a way to produce a normal text file from a LaTeX document.

It’s rather simplistic: Instead of writing the text to a pdf file, every character is \written to a given textfile. To keep the markup, things like \section{#1} are redefined to produce ”empty line – indent – section title – empty line” so you get a section even in text format.

This is work in pre-pre-a-alpha status. It will most probably /not/ work the way it is now!
