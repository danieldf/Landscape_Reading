Landscape_Reading
=================

Advocating for a Landscape Reading Format.

The original motivation came from "[*Advocating two-column landscape format for scholarly online articles*](http://scholardox.wordpress.com/2013/05/29/two-column-landscape-should-be-the-standard-format-of-scholarly-online-articles/)".
    
However, because of typographical issues, among some other, I personally prefer
to use the [KOMA-scripts](http://www.ctan.org/pkg/koma-script). Thus, I
just wrote a LaTeX template that suited me better.

To compile this file you just need to run `pdflatex` on it as many
times as necessary. Also, note that the order of some of the packages is
important, for example, `hyperref` should be loaded before
`bookmark`. Lastly, in order to access and make use of the multimedia
file embedded, you need to use the [Adobe Acrobat Reader](http://get.adobe.com/reader/),
for it seems to be the only one that implemented such features.
