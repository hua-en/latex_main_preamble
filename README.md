# Main Preamble

My main preamble for LaTeX. Contains a few packages that comprise my entire preamble.  

- `mypreambleessentials.sty`: Contains all basic packages required for a document.  
- `mybasicboxes.sty`: Contains some basic boxes defined with `tcolorbox`.  
- `myminimaltheorems.sty`: Contains minimal definitions for all theorem types with `amsthm`.
- `mygreyscaletheorems.sty`: Contains minimal greyscale boxes for all theorem types with `amsthm` and `tcolorbox`.  
- `mymdftheorems.sty`: Contains coloured theorems defined with `mdframed`, copied from Castel's preamble.  
- `mytcbtheorems.sty`: Contains coloured boxes defined with `tcolorbox`, adapted from Castel's preamble.  

## Usage

Copy `main.tex` and `mypreambleessentials.sty` to your working directory, and make changes to `mypreambleessentials.sty` depending on which packages you want in your document.  

If you want to include theorems, copy over one of the following:  

- `myminimaltheorems.sty`  
- `mygreyscaletheorems.sty`  
- `mymdftheorems.sty`  
- `mytcbtheorems.sty`  

Any of the 4 packages will provide definitions for all the basic theorem environments.  

## Credits

Credits to Gilles Castel for his MDFramed theorem definitions and sleepymalc's extended MDFramed theorem definitions! Most of their definitions were used in `mymdftheorems.sty` and adapted for `tcolorbox` in `mytcbtheorems.sty`.  
