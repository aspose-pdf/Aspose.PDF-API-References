---
title: Class ColorBarAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.ColorBarAnnotation class. Class representing ColorBarAnnotation annotation. Property Color ignored instead used ColorsOfCMYK color. On creation the ratio of width and height determines the orientation of the annotation  horizontal or vertical. Next it checks that the annotation rectangle is outside the TrimBox and if not then it is shifted to the nearest location outside the TrimBox taking into account the orientation of the annotation. It is possible to reduce the width height so that the annotation fits outside the TrimBox. If there is no space for the layout the width/height can be set to zero in this case the annotation is present on the page but not displayed
type: docs
weight: 260
url: /net/aspose.pdf.annotations/colorbarannotation/
---
## ColorBarAnnotation class

Class representing ColorBarAnnotation annotation. Property Color ignored, instead used ColorsOfCMYK color. On creation, the ratio of width and height determines the orientation of the annotation - horizontal or vertical. Next, it checks that the annotation rectangle is outside the TrimBox, and if not, then it is shifted to the nearest location outside the TrimBox, taking into account the orientation of the annotation. It is possible to reduce the width (height) so that the annotation fits outside the TrimBox. If there is no space for the layout, the width/height can be set to zero (in this case, the annotation is present on the page, but not displayed).

```csharp
public sealed class ColorBarAnnotation : PrinterMarkAnnotation
```

## Constructors

| Name | Description |
| --- | --- |
| [ColorBarAnnotation](colorbarannotation/)(Page, Rectangle, ColorsOfCMYK) | Creates new ColorBar annotation on the specified page. |

## Properties

| Name | Description |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Gets list of annotatation actions. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Gets or sets current annotation appearance state. |
| override [AnnotationType](../../aspose.pdf.annotations/colorbarannotation/annotationtype/) { get; } | Gets type of annotation. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Gets appearance dictionary of the annotation. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Gets or sets annotation border characteristics. [`Border`](../annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Gets annotation characteristics. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Gets or sets annotation color. |
| [ColorOfCMYK](../../aspose.pdf.annotations/colorbarannotation/colorofcmyk/) { get; set; } | Gets or sets color (one of cyan, magenta, yellow, black) for which the annotation is drawing. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Gets or sets annotation text. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Flags of the annotation. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Gets full qualified name of the annotation. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Gets or sets height of the annotation. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Gets or sets the fragment hyperlink(for pdf generator). |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Gets or sets a bool value that indicates whether this paragraph will be at next column. Default is false.(for pdf generation) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Gets or sets a paragraph is inline. Default is false.(for pdf generation) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Gets or sets a bool value that force this paragraph generates at new page. Default is false.(for pdf generation) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Gets or sets a bool value that indicates whether current paragraph remains in the same page along with next paragraph. Default is false.(for pdf generation) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Gets or sets a outer margin for paragraph (for pdf generation) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Gets or sets date and time when annotation was recently modified. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Gets or sets annotation name on the page. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Gets index of page which contains annotation. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Gets or sets annotation rectangle. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Gets appearance dictionary of annotation. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Gets or sets text alignment for annotation. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Gets or sets a vertical alignment of paragraph |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Gets or sets width of the annotation. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Gets or sets a int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page. |

## Methods

| Name | Description |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/colorbarannotation/accept/)(AnnotationSelector) | Accepts visitor object to process the annotation. |
| override [ChangeAfterResize](../../aspose.pdf.annotations/colorbarannotation/changeafterresize/)(Matrix) | Update parameters and appearance, according to the matrix transform and moving outside of TrimBox if nesseary. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Clones this instance. Virtual method. Always return null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | Places annotation contents directly on the page, annotation object will be removed. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Returns rectangle of annotation taking into consideration page rotation. |

### See Also

* class [PrinterMarkAnnotation](../printermarkannotation/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


