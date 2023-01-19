---
title: PopupAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Represents the pop-up annotation that displays text in a pop-up window for entry and editing.
type: docs
weight: 960
url: /net/aspose.pdf.annotations/popupannotation/
---
## PopupAnnotation class

Represents the pop-up annotation that displays text in a pop-up window for entry and editing.

```csharp
public sealed class PopupAnnotation : Annotation
```

## Constructors

| Name | Description |
| --- | --- |
| [PopupAnnotation](popupannotation#constructor)(Document) | Constructor. for using in Generator. |
| [PopupAnnotation](popupannotation#constructor_1)(Page, Rectangle) | Creates new Popup annotation on the specified page. |

## Properties

| Name | Description |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions) { get; } | Gets list of annotatation actions. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate) { get; set; } | Gets or sets current annotation appearance state. |
| override [AnnotationType](../../aspose.pdf.annotations/popupannotation/annotationtype) { get; } | Gets type of annotation. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance) { get; } | Gets appearance dictionary of the annotation. |
| [Border](../../aspose.pdf.annotations/annotation/border) { get; set; } | Gets or sets annotation border characteristics. [`Border`](../annotation/border) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics) { get; } | Gets annotation characteristics. |
| [Color](../../aspose.pdf.annotations/annotation/color) { get; set; } | Gets or sets annotation color. |
| [Contents](../../aspose.pdf.annotations/annotation/contents) { get; set; } | Gets or sets annotation text. |
| [Flags](../../aspose.pdf.annotations/annotation/flags) { get; set; } | Flags of the annotation. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname) { get; } | Gets full qualified name of the annotation. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height) { get; set; } | Gets or sets height of the annotation. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink) { get; set; } | Gets or sets the fragment hyperlink(for pdf generator). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn) { get; set; } | Gets or sets a bool value that indicates whether this paragraph will be at next column. Default is false.(for pdf generation) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph) { get; set; } | Gets or sets a paragraph is inline. Default is false.(for pdf generation) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage) { get; set; } | Gets or sets a bool value that force this paragraph generates at new page. Default is false.(for pdf generation) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext) { get; set; } | Gets or sets a bool value that indicates whether current paragraph remains in the same page along with next paragraph. Default is false.(for pdf generation) |
| [Margin](../../aspose.pdf/baseparagraph/margin) { get; set; } | Gets or sets a outer margin for paragraph (for pdf generation) |
| [Modified](../../aspose.pdf.annotations/annotation/modified) { get; set; } | Gets or sets date and time when annotation was recently modified. |
| [Name](../../aspose.pdf.annotations/annotation/name) { get; set; } | Gets or sets annotation name on the page. |
| [Open](../../aspose.pdf.annotations/popupannotation/open) { get; set; } | Gets or sets a flag specifying whether the pop-up annotation should initially be displayed open. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex) { get; } | Gets index of page which contains annotation. |
| [Parent](../../aspose.pdf.annotations/popupannotation/parent) { get; set; } | Gets or sets the parent annotation with which this pop-up annotation shall be associated. If this entry is present, the parent annotation�s Contents, M, C, and T entries shall override those of the pop-up annotation itself. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect) { get; set; } | Gets or sets annotation rectangle. |
| [States](../../aspose.pdf.annotations/annotation/states) { get; } | Gets appearance dictionary of annotation. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment) { get; set; } | Gets or sets text alignment for annotation. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment) { get; set; } | Gets or sets a vertical alignment of paragraph |
| virtual [Width](../../aspose.pdf.annotations/annotation/width) { get; set; } | Gets or sets width of the annotation. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex) { get; set; } | Gets or sets a int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page. |

## Methods

| Name | Description |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/popupannotation/accept)(AnnotationSelector) | Accepts visitor object to process the annotation. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize)(Matrix) | Update parameters and appearance, according to the matrix transform. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone)() | Clones this instance. Virtual method. Always return null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten)() | Places annotation contents directly on the page, annotation object will be removed. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle)(bool) | Returns rectangle of annotation taking into consideration page rotation. |

### See Also

* class [Annotation](../annotation)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations)
* assembly [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
