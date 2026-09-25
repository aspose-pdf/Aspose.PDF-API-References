---
title: "LineAnnotation Class"
linktitle: "LineAnnotation"
articleTitle: "LineAnnotation"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Annotations.LineAnnotation class. Class representing line annotation."
type: docs
weight: 600
url: "/net/aspose.pdf.annotations/lineannotation/"
keywords: "LineAnnotation, Aspose.Pdf.Annotations, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## LineAnnotation class

Class representing line annotation.

```csharp
public sealed class LineAnnotation : MarkupAnnotation
```

## Constructors

| Name | Description |
| --- | --- |
| [LineAnnotation](./lineannotation/#constructor)(*[Document](../../aspose.pdf/document/), [Point](../../aspose.pdf/point/), [Point](../../aspose.pdf/point/)*) | Constructor for using with Generator. |
| [LineAnnotation](./lineannotation/#constructor_1)(*[Page](../../aspose.pdf/page/), [Rectangle](../../aspose.pdf.drawing/rectangle/), [Point](../../aspose.pdf/point/), [Point](../../aspose.pdf/point/)*) | Creates new Line annotation on the specified page. |

## Properties

| Name | Description |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Gets list of annotatation actions. *(Inherited from Annotation)* |
| [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Gets or sets current annotation appearance state. *(Inherited from Annotation)* |
| [Alignment](../../aspose.pdf.annotations/annotation/alignment/) { get; set; } | Annotation alignment. This property is obsolete. Use HorizontalAligment instead. *(Inherited from Annotation)* |
| [AnnotationType](./annotationtype/) { get; } | Gets type of annotation. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Gets appearance dictionary of the annotation. *(Inherited from Annotation)* |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Gets or sets annotation border characteristics. `Border`. *(Inherited from Annotation)* |
| [CaptionOffset](./captionoffset/) { get; set; } | Gets or sets caption text offset from its normal position. |
| [CaptionPosition](./captionposition/) { get; set; } | Gets or sets annotation caption position. |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Gets annotation characteristics. *(Inherited from Annotation)* |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Gets or sets annotation color. *(Inherited from Annotation)* |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Gets or sets annotation text. *(Inherited from Annotation)* |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate/) { get; set; } | Gets date and time when annotation was created. *(Inherited from MarkupAnnotation)* |
| [Ending](./ending/) { get; set; } | Gets or sets line ending point. |
| [EndingStyle](./endingstyle/) { get; set; } | Gets or sets ending style for end point of line. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Flags of the annotation. *(Inherited from Annotation)* |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Gets full qualified name of the annotation. *(Inherited from Annotation)* |
| [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Gets or sets height of the annotation. *(Inherited from Annotation)* |
| [HorizontalAlignment](../../aspose.pdf.annotations/annotation/horizontalalignment/) { get; set; } | Gets or sets text alignment for annotation. *(Inherited from Annotation)* |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto/) { get; set; } | A reference to the annotation that this annotation is "in reply to". *(Inherited from MarkupAnnotation)* |
| [Intent](./intent/) { get; set; } | Gets or sets the intent of the line annotation. |
| [InteriorColor](./interiorcolor/) { get; set; } | Gets or sets interior color of the annotation. |
| [LeaderLine](./leaderline/) { get; set; } | Gets or sets leader line length. |
| [LeaderLineExtension](./leaderlineextension/) { get; set; } | Gets or sets length of leader line extension. |
| [LeaderLineOffset](./leaderlineoffset/) { get; set; } | Gets or sets leader line offset. |
| [Measure](./measure/) { get; set; } | Measure units specifed for this annotation. |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Gets or sets date and time when annotation was recently modified. *(Inherited from Annotation)* |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Gets or sets annotation name on the page. *(Inherited from Annotation)* |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity/) { get; set; } | Gets or sets the constant opacity value to be used in painting the annotation. *(Inherited from MarkupAnnotation)* |
| [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Gets index of page which contains annotation. *(Inherited from Annotation)* |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup/) { get; set; } | Pop-up annotation for entering or editing the text associated with this annotation. *(Inherited from MarkupAnnotation)* |
| [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Gets or sets annotation rectangle. *(Inherited from Annotation)* |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype/) { get; set; } | A string specifying the relationship (the "reply type") between this annotation. *(Inherited from MarkupAnnotation)* |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext/) { get; set; } | Gets or sets a rich text string to be displayed in the pop-up window when the annotation is opened. *(Inherited from MarkupAnnotation)* |
| [ShowCaption](./showcaption/) { get; set; } | Gets or sets boolean flag which determinies is contents must be shown as caption. |
| [Starting](./starting/) { get; set; } | Gets or sets starting point of line. |
| [StartingStyle](./startingstyle/) { get; set; } | Gets or sets line ending style for line starting point. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Gets appearance dictionary of annotation. *(Inherited from Annotation)* |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject/) { get; set; } | Gets text representing desciption of the object. *(Inherited from MarkupAnnotation)* |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Gets or sets text alignment for annotation. *(Inherited from Annotation)* |
| [Title](../../aspose.pdf.annotations/markupannotation/title/) { get; set; } | Gets or sets a text label that shall be displayed in the title bar of the annotation�s popup window when open and active. *(Inherited from MarkupAnnotation)* |
| [UpdateAppearanceOnConvert](../../aspose.pdf.annotations/annotation/updateappearanceonconvert/) { get; set; } | If true, annotation appearance will be updated before converting PF document into image. This allows convert fields correctly but probably demand more time. *(Inherited from Annotation)* |
| [UseFontSubset](../../aspose.pdf.annotations/annotation/usefontsubset/) { get; set; } | If this property set to true, fonts will be added to document as subsets. Default value is true. *(Inherited from Annotation)* |
| [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Gets or sets width of the annotation. *(Inherited from Annotation)* |

## Methods

| Name | Description |
| --- | --- |
| [Accept](./accept/)(*AnnotationSelector*) | Accepts visitor to annotation processing. |
| [ChangeAfterResize](./changeafterresize/)(*Matrix*) | Updates the Starting and Ending points, according to the matrix transform. |
| [ClearState](../../aspose.pdf.annotations/markupannotation/clearstate/) | Clears state and state model for the annotation. *(Inherited from MarkupAnnotation)* |
| [Flatten](../../aspose.pdf.annotations/annotation/flatten/) | Places annotation contents directly on the page,. *(Inherited from Annotation)* |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(*bool*) | Returns rectangle of annotation taking into consideration page rotation. *(Inherited from Annotation)* |
| [GetState](../../aspose.pdf.annotations/markupannotation/getstate/) | Gets the state of the annotation. *(Inherited from MarkupAnnotation)* |
| [GetStateModel](../../aspose.pdf.annotations/markupannotation/getstatemodel/) | Gets the state model of the annotation. *(Inherited from MarkupAnnotation)* |
| [SetMarkedState](../../aspose.pdf.annotations/markupannotation/setmarkedstate/)(*bool*) | Sets Marked and Unmarked state for the annotation. *(Inherited from MarkupAnnotation)* |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(*AnnotationState*) | Sets the review state for an annotation. Marked and Unmarked states are ignored as they do not belong to the Review StateModel. *(Inherited from MarkupAnnotation)* |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(*AnnotationState, string*) | Sets the review state for an annotation. Marked and Unmarked states are ignored as they do not belong to the Review StateModel. *(Inherited from MarkupAnnotation)* |

### See Also

* class [MarkupAnnotation](../markupannotation/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)

