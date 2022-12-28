---
title: MovieAnnotation
second_title: Aspose.PDF for Python via .NET API Reference
description: Represents a movie annotation that contains animated graphics and sound to be presented on the computer screen and through the speakers. When the annotation is activated, the movie is played.
type: docs
weight: 480
url: /python-net/aspose.pdf.annotations/movieannotation/
---

## MovieAnnotation class

Represents a movie annotation that contains animated graphics and sound to be presented on the computer screen and through the speakers. When the annotation is activated, the movie is played.

The MovieAnnotation type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|MovieAnnotation(document, movie_file)|Initializes a new instance of the MovieAnnotation class|
|MovieAnnotation(page, rect, movie_file)|Initializes a new instance of the MovieAnnotation class|
## Properties
| Name | Description |
| :- | :- |
|vertical_alignment|Gets or sets a vertical alignment of paragraph|
|horizontal_alignment|Gets or sets text alignment for annotation.|
|margin|Gets or sets a outer margin for paragraph (for pdf generation)|
|is_first_paragraph_in_column|Gets or sets a bool value that indicates whether this paragraph will be at next column.<br/>            Default is false.(for pdf generation)|
|is_kept_with_next|Gets or sets a bool value that indicates whether current paragraph remains in the same page along with next paragraph.<br/>            Default is false.(for pdf generation)|
|is_in_new_page|Gets or sets a bool value that force this paragraph generates at new page.<br/>            Default is false.(for pdf generation)|
|is_in_line_paragraph|Gets or sets a paragraph is inline.<br/>            Default is false.(for pdf generation)|
|hyperlink|Gets or sets the fragment hyperlink(for pdf generator).|
|z_index|Gets or sets a int value that indicates the Z-order of the graph. A graph with larger ZIndex <br/>            will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative <br/>            ZIndex will be placed behind the text in the page.|
|update_appearance_on_convert|If true, annotation appearance will be updated before converting PF document into image. This allows convert fields correctly but probably demand more time.|
|use_font_subset|If this property set to true, fonts will be added to document as subsets. Default value is true.|
|flags|Flags of the annotation.|
|annotation_type|Gets type of annotation.|
|width|Gets or sets width of the annotation.|
|actions|Gets list of annotatation actions.|
|height|Gets or sets height of the annotation.|
|rect|Gets or sets annotation rectangle.|
|contents|Gets or sets annotation text.|
|name|Gets or sets annotation name on the page.|
|modified|Gets or sets date and time when annotation was recently modified.|
|color|Gets or sets annotation color.|
|border|Gets or sets annotation border characteristics. [border](/pdf/python-net/aspose.pdf.annotations/annotation/)|
|active_state|Gets or sets current annotation appearance state.|
|characteristics|Gets annotation characteristics.|
|states|Gets appearance dictionary of annotation.|
|alignment|Annotation alignment. This property is obsolete. Use HorizontalAligment instead.|
|text_horizontal_alignment|Gets or sets text alignment for annotation.|
|full_name|Gets full qualified name of the annotation.|
|appearance|Gets appearance dictionary of the annotation.|
|page_index|Gets index of page which contains annotation.|
|title|Gets or sets the title of the movie annotation.|
|file|Gets or sets a file specification identifying a self-describing movie file.|
|poster|Gets or sets a flag or stream specifying whether and how a poster image representing the movie shall be displayed. If true, the poster image shall be retrieved from the movie file; if it is false, no poster shall be displayed.|
|aspect|Gets or sets the width and height of the movie�s bounding box, in pixels.|
|rotate|Gets or sets the number of degrees by which the movie shall be rotated clockwise relative to the page. The value shall be a multiple of 90.|
## Methods
| Name | Description |
| :- | :- |
|clone()|Clones this instance.<br/>            Virtual method. Always return null.|
|get_rectangle(consider_rotation)|Returns rectangle of annotation taking into consideration page rotation.|
|accept(visitor)|Accepts visitor object to process the annotation.|
|flatten()|Places annotation contents directly on the page,<br/>            annotation object will be removed.|
|change_after_resize(transform)|Update parameters and appearance, according to the matrix transform.|

### See Also

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

