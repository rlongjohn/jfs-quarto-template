# Quarto Template for Rendering Word Documents for the Journal of Forensic Sciences

This is a template for creating Microsoft Word documents in the style required by the Journal of Forensic Sciences.
The author guidelines for the journal can be found here [https://onlinelibrary.wiley.com/page/journal/15564029/homepage/forauthors.html](https://onlinelibrary.wiley.com/page/journal/15564029/homepage/forauthors.html).

This template should be helpful for preparing submissions when there are a lot of equations that need to be included (rather than having to type them out in the Word document directly).

The CSL file was modified from Zotero's Vancouver citation style available [here](http://www.zotero.org/styles/vancouver). Note that the original style file from Zotero is licensed under the CC BY-SA 3.0 ([license link](https://creativecommons.org/licenses/by-sa/3.0/)), which requires that the derivative CSL file used here also use the same license.

## Using the template

This template uses Quarto, so please make sure you have that installed first: [https://quarto.org/](https://quarto.org/).

The `article.qmd` file lays out the article formatting and shows examples of tables, figures, references, and equations. It also includes of examples of cross-referencing each of these things. This file renders into the Microsoft Word document, `article.docx`.

You can replace the text in `article.qmd` with your own text or make a copy of it and work with the copy instead, so that you can still reference the examples when needed.

The template also uses the `references.bib` file to store the bibliographic information and the `jfs-vancouver.csl` file to format the citations. You can customize this file with your own entries, or create your own. If you make your own .bib file, make sure to update the name of the file in the header of your article's qmd file.