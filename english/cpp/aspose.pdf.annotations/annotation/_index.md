---
title: Aspose::Pdf::Annotations::Annotation class
linktitle: Annotation
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::Annotation class. Class representing annotation object in C++.'
type: docs
weight: 200
url: /cpp/aspose.pdf.annotations/annotation/
---
## Annotation class


Class representing annotation object.

```cpp
class Annotation : public Aspose::Pdf::BaseParagraph
```

## Methods

| Method | Description |
| --- | --- |
| virtual [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) | Accepts visitor for annotation processing. |
| [BaseParagraph](../../aspose.pdf/baseparagraph/baseparagraph/)() |  |
| virtual [ChangeAfterResize](./changeafterresize/)(System::SharedPtr\<Matrix\>) | Update parameters and appearance, according to the matrix transform. |
| [Clone](../../aspose.pdf/baseparagraph/clone/)() override | Clones this instance. Virtual method. Always return null. |
| [Flatten](./flatten/)() | Places annotation contents directly on the page, annotation object will be removed. |
| [get_Actions](./get_actions/)() | Gets list of annotatation actions. |
| virtual [get_ActiveState](./get_activestate/)() | Gets current annotation appearance state. |
| [get_Alignment](./get_alignment/)() | [Annotation](./) alignment. This property is obsolete. Use HorizontalAligment instead. |
| virtual [get_AnnotationType](./get_annotationtype/)() | Gets type of annotation. |
| [get_Appearance](./get_appearance/)() | Gets appearance dictionary of the annotation. |
| [get_Border](./get_border/)() const | Gets annotation border characteristics. [Border](../border/) |
| [get_Characteristics](./get_characteristics/)() | Gets annotation characteristics. |
| [get_Color](./get_color/)() | Gets annotation color. |
| [get_Contents](./get_contents/)() | Gets annotation text. |
| [get_Flags](./get_flags/)() | Flags of the annotation. |
| [get_FullName](./get_fullname/)() | Gets full qualified name of the annotation. |
| virtual [get_Height](./get_height/)() | Gets height of the annotation. |
| [get_HorizontalAlignment](./get_horizontalalignment/)() override | Gets text alignment for annotation. |
| virtual [get_Hyperlink](../../aspose.pdf/baseparagraph/get_hyperlink/)() | Gets the fragment hyperlink(for pdf generator). |
| [get_IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/get_isfirstparagraphincolumn/)() const | Gets a bool value that indicates whether this paragraph will be at next column. Default is false.(for pdf generation) |
| [get_IsInLineParagraph](../../aspose.pdf/baseparagraph/get_isinlineparagraph/)() const | Gets a paragraph is inline. Default is false.(for pdf generation) |
| [get_IsInNewPage](../../aspose.pdf/baseparagraph/get_isinnewpage/)() const | Gets a bool value that force this paragraph generates at new page. Default is false.(for pdf generation) |
| [get_IsKeptWithNext](../../aspose.pdf/baseparagraph/get_iskeptwithnext/)() const | Gets a bool value that indicates whether current paragraph remains in the same page along with next paragraph. Default is false.(for pdf generation) |
| [get_Margin](../../aspose.pdf/baseparagraph/get_margin/)() | Gets a outer margin for paragraph (for pdf generation) |
| [get_Modified](./get_modified/)() | Gets date and time when annotation was recently modified. |
| [get_Name](./get_name/)() | Gets annotation name on the page. |
| virtual [get_PageIndex](./get_pageindex/)() | Gets index of page which contains annotation. |
| virtual [get_Rect](./get_rect/)() | Gets annotation rectangle. |
| [get_States](./get_states/)() | Gets appearance dictionary of annotation. |
| [get_TextHorizontalAlignment](./get_texthorizontalalignment/)() | Gets text alignment for annotation. |
| static [get_UpdateAppearanceOnConvert](./get_updateappearanceonconvert/)() | If true, annotation appearance will be updated before converting PF document into image. This allows convert fields correctly but probably demand more time. |
| static [get_UseFontSubset](./get_usefontsubset/)() | If this property set to true, fonts will be added to document as subsets. Default value is true. |
| virtual [get_VerticalAlignment](../../aspose.pdf/baseparagraph/get_verticalalignment/)() | Gets a vertical alignment of paragraph. |
| virtual [get_Width](./get_width/)() | Gets width of the annotation. |
| [get_ZIndex](../../aspose.pdf/baseparagraph/get_zindex/)() const | Gets a int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page. |
| [GetRectangle](./getrectangle/)(bool) | Returns rectangle of annotation taking into consideration page rotation. |
| virtual [set_ActiveState](./set_activestate/)(System::String) | Sets current annotation appearance state. |
| [set_Alignment](./set_alignment/)(TextAlignment) | [Annotation](./) alignment. This property is obsolete. Use HorizontalAligment instead. |
| [set_Border](./set_border/)(System::SharedPtr\<Aspose::Pdf::Annotations::Border\>) | Sets annotation border characteristics. [Border](../border/) |
| [set_Color](./set_color/)(System::SharedPtr\<Aspose::Pdf::Color\>) | Sets annotation color. |
| [set_Contents](./set_contents/)(System::String) | Sets annotation text. |
| [set_Flags](./set_flags/)(AnnotationFlags) | Flags of the annotation. |
| virtual [set_Height](./set_height/)(double) | Sets height of the annotation. |
| [set_HorizontalAlignment](./set_horizontalalignment/)(Aspose::Pdf::HorizontalAlignment) override | Sets text alignment for annotation. |
| virtual [set_Hyperlink](../../aspose.pdf/baseparagraph/set_hyperlink/)(System::SharedPtr\<Aspose::Pdf::Hyperlink\>) | Sets the fragment hyperlink(for pdf generator). |
| [set_IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/set_isfirstparagraphincolumn/)(bool) | Sets a bool value that indicates whether this paragraph will be at next column. Default is false.(for pdf generation) |
| [set_IsInLineParagraph](../../aspose.pdf/baseparagraph/set_isinlineparagraph/)(bool) | Sets a paragraph is inline. Default is false.(for pdf generation) |
| [set_IsInNewPage](../../aspose.pdf/baseparagraph/set_isinnewpage/)(bool) | Sets a bool value that force this paragraph generates at new page. Default is false.(for pdf generation) |
| [set_IsKeptWithNext](../../aspose.pdf/baseparagraph/set_iskeptwithnext/)(bool) | Sets a bool value that indicates whether current paragraph remains in the same page along with next paragraph. Default is false.(for pdf generation) |
| [set_Margin](../../aspose.pdf/baseparagraph/set_margin/)(System::SharedPtr\<MarginInfo\>) | Sets a outer margin for paragraph (for pdf generation) |
| [set_Modified](./set_modified/)(System::DateTime) | Sets date and time when annotation was recently modified. |
| [set_Name](./set_name/)(System::String) | Sets annotation name on the page. |
| virtual [set_Rect](./set_rect/)(System::SharedPtr\<Rectangle\>) | Sets annotation rectangle. |
| [set_TextHorizontalAlignment](./set_texthorizontalalignment/)(Aspose::Pdf::HorizontalAlignment) | Sets text alignment for annotation. |
| static [set_UpdateAppearanceOnConvert](./set_updateappearanceonconvert/)(bool) | If true, annotation appearance will be updated before converting PF document into image. This allows convert fields correctly but probably demand more time. |
| static [set_UseFontSubset](./set_usefontsubset/)(bool) | If this property set to true, fonts will be added to document as subsets. Default value is true. |
| virtual [set_VerticalAlignment](../../aspose.pdf/baseparagraph/set_verticalalignment/)(Aspose::Pdf::VerticalAlignment) | Sets a vertical alignment of paragraph. |
| virtual [set_Width](./set_width/)(double) | Sets width of the annotation. |
| [set_ZIndex](../../aspose.pdf/baseparagraph/set_zindex/)(int32_t) | Sets a int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page. |
## See Also

* Class [BaseParagraph](../../aspose.pdf/baseparagraph/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
