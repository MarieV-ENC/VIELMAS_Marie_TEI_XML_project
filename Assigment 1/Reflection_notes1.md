# Reflection notes - Assigment 1
XML-TEI modelling project (course by Katarzyna Kapitan - M2 TNAH ENC 2025

## Encoding with XML and DTD
<p>For this first step, we propose a reflection on the logical structure of an old and contemporary press document.</p>

<p>The front page of a printed newspaper can be structured and laid out according to several elements:
- a title banner containing various publication information (title, date, year, issue number, place of publication, etc.)
- the body of the text structured into several columns, each column divided into several articles with a title and an author.</p>

<p>One of the difficulties in encoding this type of document is the plurality of locations for textual information fields. Articles in particular can continue across several columns. In this case we use in the DTD file the <\overlap> and <\columnattachment></p>

<p>XML can be useful for structuring and organising textual data in the form of tags that differentiate several sections:
- a header section, composed of several elements such as presstitle, date, pressnumber, etc., referring to the elements included in the title banner,
- a text section, for the textual informations in the body of the page, divided into columns and articles.</p>

<p>For the sample published in 2025, the layout differs from 19th and 20th century practices. The information is no longer structured in columns but rather in blocks that can be associated with images.
In this case, the encoding will have to adapt to the layout and location of these blocks in the overall page layout.</p>

<p>The encoding of a DTD file allows sufficient freedom in the naming and structuring of elements, making the encoding easily adaptable for this type of document.</p>

<p>No AI used for this part</p>

