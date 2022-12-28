---
title: RedactionAnnotation
second_title: Aspose.PDF for Python via .NET API Reference
description: Represents Redact annotation.
type: docs
weight: 680
url: /python-net/aspose.pdf.annotations/redactionannotation/
---

## RedactionAnnotation class

Represents Redact annotation.

The RedactionAnnotation type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|RedactionAnnotation(document)|Initializes a new instance of the RedactionAnnotation class|
|RedactionAnnotation(page, rect)|Initializes a new instance of the RedactionAnnotation class|
## Properties
| Name | Description |
| :- | :- |
|vertical_alignment|None|
|horizontal_alignment|Gets or sets text alignment for annotation.|
|margin|None|
|is_first_paragraph_in_column|None|
|is_kept_with_next|None|
|is_in_new_page|None|
|is_in_line_paragraph|None|
|hyperlink|None|
|z_index|None|
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
|title|Gets or sets a text that shall be displayed in title bar of annotation.|
|rich_text|Gets or sets a rich text string to be displayed in the pop-up window when the annotation is opened.|
|creation_date|Gets date and time when annotation was created.|
|subject|Gets text representing desciption of the object.|
|popup|Pop-up annotation for entering or editing the text associated with this annotation.|
|opacity|Gets or sets the constant opacity value to be used in painting the annotation.|
|in_reply_to|A reference to the annotation that this annotation is "in reply to".<br/>            Both annotations must be on the same page of the document.|
|reply_type|A string specifying the relationship (the "reply type") between this annotation<br/>            and one specified by InReplyTo.|
|quad_point|An array of 8xN numbers specifying the coordinates of content region that is intended to be removed.|
|default_appearance|Gets or sets the default appearance string to be used in formatting the text.|
|fill_color|Gets or sets color to fill annotation.|
|border_color|Gets or sets color of border which is drawn when redaction is not active.|
|overlay_text|Text to print on redact annotation.|
|repeat|If true overlay text will be repated on the annotation.|
|text_alignment|Gets or sets. Alignment of Overlay Text.|
## Methods
| Name | Description |
| :- | :- |
|clone()|None|
|get_rectangle(consider_rotation)|Returns rectangle of annotation taking into consideration page rotation.|
|accept(visitor)|Accepts visitor object to process the annotation.|
|flatten()|Flattens annotation i.e. removes annotation and adds its|
|change_after_resize(transform)|Update parameters and appearance, according to the matrix transform.|
|redact()|Flattens annotation and redacts page contents (i.e. removes text and image under redacted annotation)|

### See Also

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

