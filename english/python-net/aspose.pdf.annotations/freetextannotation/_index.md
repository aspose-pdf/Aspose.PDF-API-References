---
title: FreeTextAnnotation
second_title: Aspose.PDF for Python via .NET API Reference
description: Represents a free text annotation that displays text directly on the page. Unlike an ordinary text annotation, a free text annotation has no open or closed state; instead of being displayed in a pop-up window, the text is always visible.
type: docs
weight: 260
url: /python-net/aspose.pdf.annotations/freetextannotation/
---

## FreeTextAnnotation class

Represents a free text annotation that displays text directly on the page. Unlike an ordinary text annotation, a free text annotation has no open or closed state; instead of being displayed in a pop-up window, the text is always visible.

The FreeTextAnnotation type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|FreeTextAnnotation(document, appearance)|Initializes a new instance of the FreeTextAnnotation class|
|FreeTextAnnotation(page, rect, appearance)|Initializes a new instance of the FreeTextAnnotation class|
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
|starting_style|Gets or sets line ending style for line ending point.<br/>            OThis property is obsolete, please use EndingStyle.|
|ending_style|Gets or sets line ending style for line ending point.|
|justification|Gets or set a code specifying the form of quadding (justification) to be used in displaying the annotation�s text.|
|default_appearance|Gets or sets the default appearance string to be used in formatting the text.|
|default_appearance_object|Object which represents default appearance of FreeText annotation.|
|intent|Gets or sets the intent of the free text annotation.|
|default_style|Gets or sets a default style string.|
|text_style|Gets or sets style of the text in appearance. when text style is changed, text appearance is updated.|
|rotate|Angle of annotation rotation.|
|callout|Array of point specifying callout line.|
|text_rectangle|Rectangle describing the numerical differences between two rectangles: the Rect entry of the annotation<br/>             and a rectangle contained within that rectangle. The inner rectangle is where the annotation�s text should be displayed.|
## Methods
| Name | Description |
| :- | :- |
|clone()|None|
|get_rectangle(consider_rotation)|Returns rectangle of annotation taking into consideration page rotation.|
|accept(visitor)|Accepts visitor object to process the annotation.|
|flatten()|Places annotation contents directly on the page,<br/>            annotation object will be removed.|
|change_after_resize(transform)|Update parameters and appearance, according to the matrix transform.|

### See Also

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

