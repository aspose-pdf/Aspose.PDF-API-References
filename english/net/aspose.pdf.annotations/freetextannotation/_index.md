---
title: FreeTextAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Represents a free text annotation that displays text directly on the page. Unlike an ordinary text annotation a free text annotation has no open or closed state instead of being displayed in a pop-up window the text is always visible.
type: docs
weight: 380
url: /net/aspose.pdf.annotations/freetextannotation/
---
## FreeTextAnnotation class

Represents a free text annotation that displays text directly on the page. Unlike an ordinary text annotation, a free text annotation has no open or closed state; instead of being displayed in a pop-up window, the text is always visible.

```csharp
public sealed class FreeTextAnnotation : MarkupAnnotation
```

## Constructors

| Name | Description |
| --- | --- |
| [FreeTextAnnotation](freetextannotation#constructor)(Document, DefaultAppearance) | Constructor to use with Generator. |
| [FreeTextAnnotation](freetextannotation#constructor_1)(Page, Rectangle, DefaultAppearance) | Creates new FreeText annotation on the specified page. |

## Properties

| Name | Description |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions) { get; } | Gets list of annotatation actions. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate) { get; set; } | Gets or sets current annotation appearance state. |
| override [AnnotationType](../../aspose.pdf.annotations/freetextannotation/annotationtype) { get; } | Gets type of annotation. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance) { get; } | Gets appearance dictionary of the annotation. |
| [Border](../../aspose.pdf.annotations/annotation/border) { get; set; } | Gets or sets annotation border characteristics. [`Border`](../annotation/border) |
| [Callout](../../aspose.pdf.annotations/freetextannotation/callout) { get; set; } | Array of point specifying callout line. |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics) { get; } | Gets annotation characteristics. |
| [Color](../../aspose.pdf.annotations/annotation/color) { get; set; } | Gets or sets annotation color. |
| [Contents](../../aspose.pdf.annotations/annotation/contents) { get; set; } | Gets or sets annotation text. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate) { get; } | Gets date and time when annotation was created. |
| [DefaultAppearance](../../aspose.pdf.annotations/freetextannotation/defaultappearance) { get; set; } | Gets or sets the default appearance string to be used in formatting the text. |
| [DefaultAppearanceObject](../../aspose.pdf.annotations/freetextannotation/defaultappearanceobject) { get; } | Object which represents default appearance of FreeText annotation. |
| [DefaultStyle](../../aspose.pdf.annotations/freetextannotation/defaultstyle) { get; set; } | Gets or sets a default style string. |
| [EndingStyle](../../aspose.pdf.annotations/freetextannotation/endingstyle) { get; set; } | Gets or sets line ending style for line ending point. |
| [Flags](../../aspose.pdf.annotations/annotation/flags) { get; set; } | Flags of the annotation. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname) { get; } | Gets full qualified name of the annotation. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height) { get; set; } | Gets or sets height of the annotation. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } | Gets or sets the fragment hyperlink(for pdf generator). |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto) { get; set; } | A reference to the annotation that this annotation is "in reply to". Both annotations must be on the same page of the document. |
| [Intent](../../aspose.pdf.annotations/freetextannotation/intent) { get; set; } | Gets or sets the intent of the free text annotation. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Gets or sets a bool value that indicates whether this paragraph will be at next column. Default is false.(for pdf generation) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Gets or sets a paragraph is inline. Default is false.(for pdf generation) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Gets or sets a bool value that force this paragraph generates at new page. Default is false.(for pdf generation) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Gets or sets a bool value that indicates whether current paragraph remains in the same page along with next paragraph. Default is false.(for pdf generation) |
| [Justification](../../aspose.pdf.annotations/freetextannotation/justification) { get; set; } | Gets or set a code specifying the form of quadding (justification) to be used in displaying the annotation�s text. |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Gets or sets a outer margin for paragraph (for pdf generation) |
| [Modified](../../aspose.pdf.annotations/annotation/modified) { get; set; } | Gets or sets date and time when annotation was recently modified. |
| [Name](../../aspose.pdf.annotations/annotation/name) { get; set; } | Gets or sets annotation name on the page. |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity) { get; set; } | Gets or sets the constant opacity value to be used in painting the annotation. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex) { get; } | Gets index of page which contains annotation. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup) { get; set; } | Pop-up annotation for entering or editing the text associated with this annotation. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect) { get; set; } | Gets or sets annotation rectangle. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype) { get; set; } | A string specifying the relationship (the "reply type") between this annotation and one specified by InReplyTo. |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext) { get; set; } | Gets or sets a rich text string to be displayed in the pop-up window when the annotation is opened. |
| [Rotate](../../aspose.pdf.annotations/freetextannotation/rotate) { get; set; } | Angle of annotation rotation. |
| [StartingStyle](../../aspose.pdf.annotations/freetextannotation/startingstyle) { get; set; } | Gets or sets line ending style for line ending point. OThis property is obsolete, please use EndingStyle. |
| [States](../../aspose.pdf.annotations/annotation/states) { get; } | Gets appearance dictionary of annotation. |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject) { get; set; } | Gets text representing desciption of the object. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment) { get; set; } | Gets or sets text alignment for annotation. |
| [TextRectangle](../../aspose.pdf.annotations/freetextannotation/textrectangle) { get; set; } | Rectangle describing the numerical differences between two rectangles: the Rect entry of the annotation and a rectangle contained within that rectangle. The inner rectangle is where the annotation�s text should be displayed. |
| [TextStyle](../../aspose.pdf.annotations/freetextannotation/textstyle) { get; set; } | Gets or sets style of the text in appearance. when text style is changed, text appearance is updated. |
| [Title](../../aspose.pdf.annotations/markupannotation/title) { get; set; } | Gets or sets a text that shall be displayed in title bar of annotation. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | Gets or sets a vertical alignment of paragraph |
| virtual [Width](../../aspose.pdf.annotations/annotation/width) { get; set; } | Gets or sets width of the annotation. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Gets or sets a int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page. |

## Methods

| Name | Description |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/freetextannotation/accept)(AnnotationSelector) | Accepts visitor object to process the annotation. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize)(Matrix) | Update parameters and appearance, according to the matrix transform. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone)() | Clones this instance. Virtual method. Always return null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten)() | Places annotation contents directly on the page, annotation object will be removed. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle)(bool) | Returns rectangle of annotation taking into consideration page rotation. |

### See Also

* class [MarkupAnnotation](../markupannotation)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations)
* assembly [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
