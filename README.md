# mobile-first-RWD-template

Starter files for any mobile first responsive web design project, using a css preprocessor for scss files.

Different screen sizes (small, medium and large) are divided into partial scss files, and then imported one after another 
from smaller sizes to larger (Progressive enhancement) into the `styles.scss`. 

`styles.scss` is the only file being preprocessed, and the output is ejected to `styles.css` in the css folder.

Note that partial files are marked with "_" in their name.

`index.html` comes with a semantic structure of a standard webpage, and uses `"width=device-width, initial-scale=1.0, maximum-scale=1"` 
to make sure the web page appears in mobile devices using the exact device screen width and also doesn't allow zooming. 
