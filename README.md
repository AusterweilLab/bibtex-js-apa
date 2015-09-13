# bibtex-js-apa
Bibtex parser that automatically populates a div with citations in (approx.) APA format. Note that APA format is not perfect, but pretty close. Also, I am planning to add automatic show/hide toggling functionality for the abstract of each reference (if the abstract field of the bibtex citation is filled in).

To use it, put your bibtex references in the "bibtex_input" div within template.html. 

If you want to load your bibtex references from a file on your server, edit the "bibtex_js_draw" function within "bibtex_js.js". Commented out is the dynamic load call through jQuery that I use on my lab website. Comment out or remove the two lines that currently are run in that function and uncomment out the previous line. Change the url within the .load call to where the .bib file is on your server.

This project extends bibtex-js (https://code.google.com/p/bibtex-js/) uses priority-queue-js (https://github.com/adamhooper/js-priority-queue), jQuery (https://jquery.com), and Bootstrap 3.0 (http://getbootstrap.com/).

Feel free to email me at Joseph.Austerweil@gmail.com if you have any questions!
