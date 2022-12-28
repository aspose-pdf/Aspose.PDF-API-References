---
title: PDF3DAnnotation
second_title: Aspose.PDF for Python via .NET API Reference
description: Class PDF3DAnnotation. This class cannot be inherited.
type: docs
weight: 510
url: /python-net/aspose.pdf.annotations/pdf3dannotation/
---

## PDF3DAnnotation class

Class PDF3DAnnotation. This class cannot be inherited.

The PDF3DAnnotation type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|PDF3DAnnotation(page, rect, pdf_3d_artwork)|Initializes a new instance of the PDF3DAnnotation class|
|PDF3DAnnotation(page, rect, pdf_3d_artwork, activation)|Initializes a new instance of the PDF3DAnnotation class|
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
|pdf_3d_artwork|Gets the 3D Artwork.|
|lighting_scheme|Gets the lighting scheme.|
|content|Gets or sets the content.|
|render_mode|Gets the render mode.|
|view_array|Gets the view array.|
## Methods
| Name | Description |
| :- | :- |
|set_image_preview(filename)|Sets the image preview.|
|set_image_preview(image)|Sets the image preview.|
|clone()|Clones this instance.<br/>            Virtual method. Always return null.|
|get_rectangle(consider_rotation)|Returns rectangle of annotation taking into consideration page rotation.|
|accept(visitor)|Accepts visitor for annotation processing.|
|flatten()|Places annotation contents directly on the page,<br/>            annotation object will be removed.|
|change_after_resize(transform)|Update parameters and appearance, according to the matrix transform.|
|set_default_view_index(index)|Sets the index of the default view.|
|clear_image_preview()|Clears the image preview.|
|get_image_preview()|Gets the image preview.|

### See Also

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

