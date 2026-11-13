# courses-pdfs

PDF files for [sercankulcu.github.io](https://sercankulcu.github.io/): course slide
PDFs, the *Programming with C* book, papers, presentations and the CV.

They are served with GitHub Pages at `https://sercankulcu.github.io/courses-pdfs/`
and linked from the main site. The folder layout mirrors the old `files/`
folder of the main site, so `files/algorithms/pdf/X.pdf` lives here as
`algorithms/pdf/X.pdf`.

Slide PDFs are generated from the HTML decks in the main repository with
`tools/make_slide_pdf.py`, and the C book with `tools/make_book.py`. Both write
into this repository when it is cloned next to the main one
(`GitHub/courses-pdfs` beside `GitHub/sercankulcu.github.io`).

`.nojekyll` turns off the Jekyll build, so files are published as they are.
