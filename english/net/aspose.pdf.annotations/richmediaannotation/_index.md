---
title: Class RichMediaAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.RichMediaAnnotation class. Class describes RichMediaAnnotation which allows embed video/audio data into PDF document
type: docs
weight: 1130
url: /net/aspose.pdf.annotations/richmediaannotation/
---
## RichMediaAnnotation class

Class describes RichMediaAnnotation which allows embed video/audio data into PDF document.

```csharp
public class RichMediaAnnotation : Annotation
```

## Constructors

| Name | Description |
| --- | --- |
| [RichMediaAnnotation](richmediaannotation/)(Page, Rectangle) | Initializes RichMediaAnnotation. |

## Properties

| Name | Description |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Gets list of annotatation actions. |
| [ActivateOn](../../aspose.pdf.annotations/richmediaannotation/activateon/) { get; set; } | Event which activates application. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Gets or sets current annotation appearance state. |
| override [AnnotationType](../../aspose.pdf.annotations/richmediaannotation/annotationtype/) { get; } | Gets type of annotation. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Gets appearance dictionary of the annotation. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Gets or sets annotation border characteristics. [`Border`](../annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Gets annotation characteristics. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Gets or sets annotation color. |
| [Content](../../aspose.pdf.annotations/richmediaannotation/content/) { get; } | Data of the Rich Media content. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Gets or sets annotation text. |
| [CustomFlashVariables](../../aspose.pdf.annotations/richmediaannotation/customflashvariables/) { get; set; } | Sets or gets flash variables which passed to player. |
| [CustomPlayer](../../aspose.pdf.annotations/richmediaannotation/customplayer/) { get; set; } | Sets or gets custom flash player to play video/audio data. |
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
| [Type](../../aspose.pdf.annotations/richmediaannotation/type/) { get; set; } | Gets or sets type of content. Possible values: Audio, Video. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Gets or sets a vertical alignment of paragraph |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Gets or sets width of the annotation. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Gets or sets a int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page. |

## Methods

| Name | Description |
| --- | --- |
| override [Accept](../../aspose.pdf.annotations/richmediaannotation/accept/)(AnnotationSelector) | Accepts visitor for this annotation. |
| [AddCustomData](../../aspose.pdf.annotations/richmediaannotation/addcustomdata/)(string, Stream) | Add custom named data (for example required for flash script). |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Update parameters and appearance, according to the matrix transform. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Clones this instance. Virtual method. Always return null. |
| [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | Places annotation contents directly on the page, annotation object will be removed. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Returns rectangle of annotation taking into consideration page rotation. |
| [SetContent](../../aspose.pdf.annotations/richmediaannotation/setcontent/)(string, Stream) | Set content stream. |
| [SetPoster](../../aspose.pdf.annotations/richmediaannotation/setposter/)(Stream) | Set poster of the annotation. |
| [Update](../../aspose.pdf.annotations/richmediaannotation/update/)() | Updates data with specified parameters. |

## Other Members

| Name | Description |
| --- | --- |
| enum [ActivationEvent](../../aspose.pdf.annotations/richmediaannotation.activationevent) | Event which activates annotation. |
| enum [ContentType](../../aspose.pdf.annotations/richmediaannotation.contenttype) | Type of the multimedia. |

### See Also

* class [Annotation](../annotation/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


