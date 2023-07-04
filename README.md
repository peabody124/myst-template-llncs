# llncs (Springer Computer Science proceedings)

Template for LLNCS formatted submissions

Modified from arXiv template to closely follow the template from Overleaf:
    https://www.overleaf.com/latex/templates/springer-lecture-notes-in-computer-science/kzwwpvhwnvfj

One challenge was adding support for natbib references. This was accomplished using
the work from http://phaseportrait.blogspot.com/2011/02/natbib-compatible-bibtex-style-bst-file.html
and replacing splncs04.bst with splncsnat.bst.

Two things that aren't perfectly fixed are:
- using Last name et al in the running head. Currently pulls in whole first author name
- emails in the institution block, which happen at ill structured ordered. I'm working
  around this by using a letter header with an href but this would probably need a 
  modification in the final tex to be fully compliant

I also used an image for orcid with a href, which also might not be supported
and the ugly large string block is in the template with an option.


![](./thumbnail.png)

- Author: [R. James Cotton](https://github.com/peabody124)
- License: MIT
- [Source Repository](https://github.com/peabody124/myst-template-llncs)
