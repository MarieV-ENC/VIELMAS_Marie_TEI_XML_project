# Reflection notes - Assigment 2
XML-TEI modelling project (course by Katarzyna Kapitan - M2 TNAH ENC 2025

## Encoding with TEI-all
<p>For this second step, we propose encoding a sample source using the TEI-all encoding scheme (on the sample dated from 1875).</p>

<p>The TEI (Text Encoding Initiative) is a project to standardise encoding techniques through the use of a predefined markup format.</p>

<p>In our particular case of printed press, converting the DTD file (assignment 1) to TEI-all is complex because there is no schema adapted to the structure of this type of document in the TEI guidelines reference documentation.It is necessary to create your own custom schema based on the TEI model.</p>

<p>We considered several encoding methods we chose specific TEI scheme and tags:

- Use of the <table> tag: we could have used this tag to define different tabular spaces within the page. This scheme applies to any type of text displayed in table form with rows and columns (@row and @col). However, the irregularity of the formation of rows and columns in a printed press document makes the use of this tag complex.

- Use of the <div> tag: it is easier to make the structure of textual information visible in several sections or divisions to which the @type and @n attributes are associated.

- The TEI-all schema does not allow you to indicate whether an article continues over several columns (@overlap in the DTD). Here, we have chosen to use the attribute @ana (analysis) to indicate analyses and interpretations.

- TEI allows several other elements and formatting to be encoded and distinguished, such as terms in bold, terms in italics, short quotations <\q>, or content elements such as references to people or places.
</p>

<p>In the case of contemporary 21th-century press structured in the form of image blocks, we can use the <\zone> tag (for primary source encoding) to describe structural elements and block levels described with their characteristics and spatial location in the layout, or the <\figure> tag which struture graphic information such as illustrations or figures (which may be associated with text). This last solution is particularly interesting when the content of the caption or summary of the article is superimposed with an image. This attempt will be made as part of assignment 3.</p>

<p>No AI used for this part</p>



