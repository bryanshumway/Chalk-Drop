To generate pdf select typeset > pdfLaTeX+MakeIndex+BibTeX then press the button with an arrow.

If you wish for text to appear in default paragraph style no format specifiers are needed.(except for certain symbols)
to include % use \%.
to include < use \textless
to include > use \textgreater
to include pi symbol use \pi between $ ($ switches to math mode)
specify seperate paragraphs by leaving an empty line between.

For citations add \cite{(citation name)}
For new entries add a bibtex entry to dis.bib				*current naming convention is first authors last name and year

To add comments start a line with %.					*no midline commenting

Start a file for each chapter. Use \chapter{(chapter name)} to give the chapter a name.
To specify sections use \section{(section name)}
To specify subsections use \subsection{(subsection name)}
To specify subsubsections use \subsubsection{(subsubsection name)}	*lowest order and not included in table of contents

If you are going to include images in a file designate the path as graphicspath{.\images\(source folder)\}
For figures use:
\figure[H]{
   \centering
   \includegraphics[(optional width = \linewidth)]{(source image)}	*linewidth is just recommended for wide images
   \caption{(figure caption)}
}
For tables use above except replace figure with table
For italics use \textit{(italic text)}