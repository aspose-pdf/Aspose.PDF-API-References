---
title: Aspose::Pdf::Annotations::PolygonAnnotation class
linktitle: PolygonAnnotation
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::PolygonAnnotation class. Class representing polygon annotation in C++.'
type: docs
weight: 8500
url: /cpp/aspose.pdf.annotations/polygonannotation/
---
## PolygonAnnotation class


Class representing polygon annotation.

```cpp
class PolygonAnnotation : public Aspose::Pdf::Annotations::PolyAnnotation
```

## Methods

| Method | Description |
| --- | --- |
| [Accept](./accept/)(System::SharedPtr\<AnnotationSelector\>) override | Accepts visitor object for annotation processing. |
| [BaseParagraph](../../aspose.pdf/baseparagraph/baseparagraph/)() |  |
| [ChangeAfterResize](../polyannotation/changeafterresize/)(System::SharedPtr\<Matrix\>) override | Updates the points in Vertices, according to the matrix transform. |
| [ClearState](../markupannotation/clearstate/)() | Clears state and state model for the annotation. For example, clears the review status for an annotation. [Note](../../aspose.pdf/note/), the state stored in other text annotation which has state and statemodel keys. |
| [Clone](../../aspose.pdf/baseparagraph/clone/)() override | Clones this instance. Virtual method. Always return null. |
| [Flatten](../annotation/flatten/)() | Places annotation contents directly on the page, annotation object will be removed. |
| [get_Actions](../annotation/get_actions/)() | Gets list of annotatation actions. |
| virtual [get_ActiveState](../annotation/get_activestate/)() | Gets current annotation appearance state. |
| [get_Alignment](../annotation/get_alignment/)() | [Annotation](../annotation/) alignment. This property is obsolete. Use HorizontalAligment instead. |
| [get_AnnotationType](./get_annotationtype/)() override | Gets type of annotation. |
| [get_Appearance](../annotation/get_appearance/)() | Gets appearance dictionary of the annotation. |
| [get_Border](../annotation/get_border/)() const | Gets annotation border characteristics. [Border](../border/) |
| [get_Characteristics](../annotation/get_characteristics/)() | Gets annotation characteristics. |
| [get_Color](../annotation/get_color/)() | Gets annotation color. |
| [get_Contents](../annotation/get_contents/)() | Gets annotation text. |
| [get_CreationDate](../markupannotation/get_creationdate/)() | Gets date and time when annotation was created. |
| [get_EndingStyle](../polyannotation/get_endingstyle/)() | Gets the style of second line ending. |
| [get_Flags](../annotation/get_flags/)() | Flags of the annotation. |
| [get_FullName](../annotation/get_fullname/)() | Gets full qualified name of the annotation. |
| virtual [get_Height](../annotation/get_height/)() | Gets height of the annotation. |
| [get_HorizontalAlignment](../annotation/get_horizontalalignment/)() override | Gets text alignment for annotation. |
| virtual [get_Hyperlink](../../aspose.pdf/baseparagraph/get_hyperlink/)() | Gets the fragment hyperlink(for pdf generator). |
| [get_InReplyTo](../markupannotation/get_inreplyto/)() | A reference to the annotation that this annotation is "in reply to". Both annotations must be on the same page of the document. |
| [get_Intent](../polyannotation/get_intent/)() | Gets the intent of the polygon or polyline annotation. |
| [get_InteriorColor](../polyannotation/get_interiorcolor/)() | Gets the interior color with which to fill the annotation's line endings. |
| [get_IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/get_isfirstparagraphincolumn/)() const | Gets a bool value that indicates whether this paragraph will be at next column. Default is false.(for pdf generation) |
| [get_IsInLineParagraph](../../aspose.pdf/baseparagraph/get_isinlineparagraph/)() const | Gets a paragraph is inline. Default is false.(for pdf generation) |
| [get_IsInNewPage](../../aspose.pdf/baseparagraph/get_isinnewpage/)() const | Gets a bool value that force this paragraph generates at new page. Default is false.(for pdf generation) |
| [get_IsKeptWithNext](../../aspose.pdf/baseparagraph/get_iskeptwithnext/)() const | Gets a bool value that indicates whether current paragraph remains in the same page along with next paragraph. Default is false.(for pdf generation) |
| [get_Margin](../../aspose.pdf/baseparagraph/get_margin/)() | Gets a outer margin for paragraph (for pdf generation) |
| [get_Measure](../polyannotation/get_measure/)() | [Measure](../measure/) units specifed for this annotation. |
| [get_Modified](../annotation/get_modified/)() | Gets date and time when annotation was recently modified. |
| [get_Name](../annotation/get_name/)() | Gets annotation name on the page. |
| [get_Opacity](../markupannotation/get_opacity/)() | Gets the constant opacity value to be used in painting the annotation. |
| virtual [get_PageIndex](../annotation/get_pageindex/)() | Gets index of page which contains annotation. |
| [get_Popup](../markupannotation/get_popup/)() | Pop-up annotation for entering or editing the text associated with this annotation. |
| virtual [get_Rect](../annotation/get_rect/)() | Gets annotation rectangle. |
| [get_ReplyType](../markupannotation/get_replytype/)() | A string specifying the relationship (the "reply type") between this annotation and one specified by InReplyTo. |
| [get_RichText](../markupannotation/get_richtext/)() | Gets a rich text string to be displayed in the pop-up window when the annotation is opened. |
| [get_StartingStyle](../polyannotation/get_startingstyle/)() | Gets the style of first line ending. |
| [get_States](../annotation/get_states/)() | Gets appearance dictionary of annotation. |
| [get_Subject](../markupannotation/get_subject/)() | Gets text representing desciption of the object. |
| [get_TextHorizontalAlignment](../annotation/get_texthorizontalalignment/)() | Gets text alignment for annotation. |
| [get_Title](../markupannotation/get_title/)() override | Gets a text that shall be displayed in title bar of annotation. |
| static [get_UpdateAppearanceOnConvert](../annotation/get_updateappearanceonconvert/)() | If true, annotation appearance will be updated before converting PF document into image. This allows convert fields correctly but probably demand more time. |
| static [get_UseFontSubset](../annotation/get_usefontsubset/)() | If this property set to true, fonts will be added to document as subsets. Default value is true. |
| virtual [get_VerticalAlignment](../../aspose.pdf/baseparagraph/get_verticalalignment/)() | Gets a vertical alignment of paragraph. |
| [get_Vertices](../polyannotation/get_vertices/)() | Gets an array of points representing the horizontal and vertical coordinates of each vertex. |
| virtual [get_Width](../annotation/get_width/)() | Gets width of the annotation. |
| [get_ZIndex](../../aspose.pdf/baseparagraph/get_zindex/)() const | Gets a int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page. |
| [GetRectangle](../annotation/getrectangle/)(bool) | Returns rectangle of annotation taking into consideration page rotation. |
| [GetState](../markupannotation/getstate/)() | Gets the state of the annotation. [Note](../../aspose.pdf/note/), the state stored in other text annotation which has state and statemodel keys. |
| [GetStateModel](../markupannotation/getstatemodel/)() | Gets the state model of the annotation. [Note](../../aspose.pdf/note/), the state stored in other text annotation which has state and statemodel keys. |
| [MarkupAnnotation](../markupannotation/markupannotation/)(System::SharedPtr\<Document\>) | Constructor for markup annotation. |
| [PolygonAnnotation](./polygonannotation/)(System::SharedPtr\<Document\>, System::ArrayPtr\<System::SharedPtr\<Point\>\>) | Constructor for using with Generator. |
| [PolygonAnnotation](./polygonannotation/)(System::SharedPtr\<Aspose::Pdf::Page\>, System::SharedPtr\<Rectangle\>, System::ArrayPtr\<System::SharedPtr\<Point\>\>) | Creates new Polygon annotation on the specified page. |
| virtual [set_ActiveState](../annotation/set_activestate/)(System::String) | Sets current annotation appearance state. |
| [set_Alignment](../annotation/set_alignment/)(TextAlignment) | [Annotation](../annotation/) alignment. This property is obsolete. Use HorizontalAligment instead. |
| [set_Border](../annotation/set_border/)(System::SharedPtr\<Aspose::Pdf::Annotations::Border\>) | Sets annotation border characteristics. [Border](../border/) |
| [set_Color](../annotation/set_color/)(System::SharedPtr\<Aspose::Pdf::Color\>) | Sets annotation color. |
| [set_Contents](../annotation/set_contents/)(System::String) | Sets annotation text. |
| [set_EndingStyle](../polyannotation/set_endingstyle/)(LineEnding) | Sets the style of second line ending. |
| [set_Flags](../annotation/set_flags/)(AnnotationFlags) | Flags of the annotation. |
| virtual [set_Height](../annotation/set_height/)(double) | Sets height of the annotation. |
| [set_HorizontalAlignment](../annotation/set_horizontalalignment/)(Aspose::Pdf::HorizontalAlignment) override | Sets text alignment for annotation. |
| virtual [set_Hyperlink](../../aspose.pdf/baseparagraph/set_hyperlink/)(System::SharedPtr\<Aspose::Pdf::Hyperlink\>) | Sets the fragment hyperlink(for pdf generator). |
| [set_InReplyTo](../markupannotation/set_inreplyto/)(System::SharedPtr\<Annotation\>) | A reference to the annotation that this annotation is "in reply to". Both annotations must be on the same page of the document. |
| [set_Intent](../polyannotation/set_intent/)(PolyIntent) | Sets the intent of the polygon or polyline annotation. |
| [set_InteriorColor](../polyannotation/set_interiorcolor/)(System::SharedPtr\<Aspose::Pdf::Color\>) | Sets the interior color with which to fill the annotation's line endings. |
| [set_IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/set_isfirstparagraphincolumn/)(bool) | Sets a bool value that indicates whether this paragraph will be at next column. Default is false.(for pdf generation) |
| [set_IsInLineParagraph](../../aspose.pdf/baseparagraph/set_isinlineparagraph/)(bool) | Sets a paragraph is inline. Default is false.(for pdf generation) |
| [set_IsInNewPage](../../aspose.pdf/baseparagraph/set_isinnewpage/)(bool) | Sets a bool value that force this paragraph generates at new page. Default is false.(for pdf generation) |
| [set_IsKeptWithNext](../../aspose.pdf/baseparagraph/set_iskeptwithnext/)(bool) | Sets a bool value that indicates whether current paragraph remains in the same page along with next paragraph. Default is false.(for pdf generation) |
| [set_Margin](../../aspose.pdf/baseparagraph/set_margin/)(System::SharedPtr\<MarginInfo\>) | Sets a outer margin for paragraph (for pdf generation) |
| [set_Measure](../polyannotation/set_measure/)(System::SharedPtr\<Aspose::Pdf::Annotations::Measure\>) | [Measure](../measure/) units specifed for this annotation. |
| [set_Modified](../annotation/set_modified/)(System::DateTime) | Sets date and time when annotation was recently modified. |
| [set_Name](../annotation/set_name/)(System::String) | Sets annotation name on the page. |
| [set_Opacity](../markupannotation/set_opacity/)(double) | Sets the constant opacity value to be used in painting the annotation. |
| [set_Popup](../markupannotation/set_popup/)(System::SharedPtr\<PopupAnnotation\>) | Pop-up annotation for entering or editing the text associated with this annotation. |
| virtual [set_Rect](../annotation/set_rect/)(System::SharedPtr\<Rectangle\>) | Sets annotation rectangle. |
| [set_ReplyType](../markupannotation/set_replytype/)(Aspose::Pdf::Annotations::ReplyType) | A string specifying the relationship (the "reply type") between this annotation and one specified by InReplyTo. |
| [set_RichText](../markupannotation/set_richtext/)(System::String) | Sets a rich text string to be displayed in the pop-up window when the annotation is opened. |
| [set_StartingStyle](../polyannotation/set_startingstyle/)(LineEnding) | Sets the style of first line ending. |
| [set_Subject](../markupannotation/set_subject/)(System::String) | Gets text representing desciption of the object. |
| [set_TextHorizontalAlignment](../annotation/set_texthorizontalalignment/)(Aspose::Pdf::HorizontalAlignment) | Sets text alignment for annotation. |
| [set_Title](../markupannotation/set_title/)(System::String) override | Sets a text that shall be displayed in title bar of annotation. |
| static [set_UpdateAppearanceOnConvert](../annotation/set_updateappearanceonconvert/)(bool) | If true, annotation appearance will be updated before converting PF document into image. This allows convert fields correctly but probably demand more time. |
| static [set_UseFontSubset](../annotation/set_usefontsubset/)(bool) | If this property set to true, fonts will be added to document as subsets. Default value is true. |
| virtual [set_VerticalAlignment](../../aspose.pdf/baseparagraph/set_verticalalignment/)(Aspose::Pdf::VerticalAlignment) | Sets a vertical alignment of paragraph. |
| [set_Vertices](../polyannotation/set_vertices/)(System::ArrayPtr\<System::SharedPtr\<Point\>\>) | Sets an array of points representing the horizontal and vertical coordinates of each vertex. |
| virtual [set_Width](../annotation/set_width/)(double) | Sets width of the annotation. |
| [set_ZIndex](../../aspose.pdf/baseparagraph/set_zindex/)(int32_t) | Sets a int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page. |
| [SetMarkedState](../markupannotation/setmarkedstate/)(bool) | Sets Marked and Unmarked state for the annotation. [Note](../../aspose.pdf/note/), the state stored in other text annotation which has state and statemodel keys. |
| [SetReviewState](../markupannotation/setreviewstate/)(AnnotationState, System::String) | Sets the review state for an annotation. Marked and Unmarked states are ignored as they do not belong to the Review StateModel. [Note](../../aspose.pdf/note/), the state stored in other text annotation which has state and statemodel keys. |
| [SetReviewState](../markupannotation/setreviewstate/)(AnnotationState) | Sets the review state for an annotation. Marked and Unmarked states are ignored as they do not belong to the Review StateModel. The state is set by the user who created the target annotation. The value is taken from the Title property of the target annotation. [Note](../../aspose.pdf/note/), the state stored in other text annotation which has state and statemodel keys. |
## See Also

* Class [PolyAnnotation](../polyannotation/)
* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
