# IFJ_beamer_presentation_template
Templates for IFJ presentation in beamer

Keep all files in the folder where you will keep ```presentation.tex```. 

### Language selection
You can select the language of your presentation by changing the argument of the command ```\IFJlanguage``` in the preamble of the .tex file. The possible choices are ```english``` or ```polish```. This will reflect the logo and some typographical settings (quotation marks is not typed directly as ```"```, but using ```\enquote{}```, etc.).

### Compliler selection
**You can use either PDFLaTeX or XeTeX to compile the .tex file**. This will change the **font**, with **Carlito** used in **PDFLaTeX**, and **Calibri** used in **XeLaTeX**.
Note that while Calibri is the font suggested in the guidelines, and it's widely supported by microsoft, XeLaTeX is a worse compiler compared to PDFLaTeX.
If Carlito is not installed on your system, install it from the official Google page https://fonts.google.com/specimen/Carlito

### Additional information
The font size is currently set to the maximum of the two indicate values (e.g. for the title it's 36 out of the choice 30/36).

Author, placeAndDate, and department have **short form** that appears in the footer. These are specified **before** the long form in the ```.tex``` file. If not given, the presentation uses the long forms instead.

### Contact 
For any issue connected to the template, contact davide.borchia@ifj.edu.pl

Templates for PowerPoint can be found at [the section szablon prezentacji](https://www.ifj.edu.pl/dla-pracownikow/formularze/).
The IFJ logo is available, in all its variant, [at this webpage](https://press.ifj.edu.pl/en/logo/)
