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
| [LineAnnotation](./lineannotation/#constructor)(Document, Point, Point) | Constructor for using with Generator. |
| [LineAnnotation](./lineannotation/#constructor_1)(Page, Rectangle, Point, Point) | Creates new Line annotation on the specified page. |

## Properties

| Name | Description |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Gets list of annotatation actions. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Gets or sets current annotation appearance state. |
| override [AnnotationType](./annotationtype/) { get; } | Gets type of annotation. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Gets appearance dictionary of the annotation. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Gets or sets annotation border characteristics. `Border` |
| [CaptionOffset](./captionoffset/) { get; set; } | Gets or sets caption text offset from its normal position. |
| [CaptionPosition](./captionposition/) { get; set; } | Gets or sets annotation caption position. |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Gets annotation characteristics. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Gets or sets annotation color. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Gets or sets annotation text. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate/) { get; set; } | Gets date and time when annotation was created. |
| [Ending](./ending/) { get; set; } | Gets or sets line ending point. |
| [EndingStyle](./endingstyle/) { get; set; } | Gets or sets ending style for end point of line. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Flags of the annotation. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Gets full qualified name of the annotation. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Gets or sets height of the annotation. |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto/) { get; set; } | A reference to the annotation that this annotation is "in reply to". Both annotations must be on the same page of the document. |
| [Intent](./intent/) { get; set; } | Gets or sets the intent of the line annotation. |
| [InteriorColor](./interiorcolor/) { get; set; } | Gets or sets interior color of the annotation. |
| [LeaderLine](./leaderline/) { get; set; } | Gets or sets leader line length. |
| [LeaderLineExtension](./leaderlineextension/) { get; set; } | Gets or sets length of leader line extension. |
| [LeaderLineOffset](./leaderlineoffset/) { get; set; } | Gets or sets leader line offset. |
| [Measure](./measure/) { get; set; } | Measure units specifed for this annotation. |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Gets or sets date and time when annotation was recently modified. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Gets or sets annotation name on the page. |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity/) { get; set; } | Gets or sets the constant opacity value to be used in painting the annotation. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Gets index of page which contains annotation. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup/) { get; set; } | Pop-up annotation for entering or editing the text associated with this annotation. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Gets or sets annotation rectangle. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype/) { get; set; } | A string specifying the relationship (the "reply type") between this annotation and one specified by InReplyTo. |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext/) { get; set; } | Gets or sets a rich text string to be displayed in the pop-up window when the annotation is opened. |
| [ShowCaption](./showcaption/) { get; set; } | Gets or sets boolean flag which determinies is contents must be shown as caption. |
| [Starting](./starting/) { get; set; } | Gets or sets starting point of line. |
| [StartingStyle](./startingstyle/) { get; set; } | Gets or sets line ending style for line starting point. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Gets appearance dictionary of annotation. |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject/) { get; set; } | Gets text representing desciption of the object. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Gets or sets text alignment for annotation. |
| [Title](../../aspose.pdf.annotations/markupannotation/title/) { get; set; } | Gets or sets a text label that shall be displayed in the title bar of the annotation�s popup window when open and active. This entry shall identify the user who added the annotation. |
| static [UpdateAppearanceOnConvert](../../aspose.pdf.annotations/annotation/updateappearanceonconvert/) { get; set; } | If true, annotation appearance will be updated before converting PF document into image. This allows convert fields correctly but probably demand more time. |
| static [UseFontSubset](../../aspose.pdf.annotations/annotation/usefontsubset/) { get; set; } | If this property set to true, fonts will be added to document as subsets. Default value is true. |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Gets or sets width of the annotation. |

## Methods

| Name | Description |
| --- | --- |
| override [Accept](./accept/)(AnnotationSelector) | Accepts visitor to annotation processing. |
| override [ChangeAfterResize](./changeafterresize/)(Matrix) | Updates the Starting and Ending points, according to the matrix transform. |
| [ClearState](../../aspose.pdf.annotations/markupannotation/clearstate/)() | Clears state and state model for the annotation. For example, clears the review status for an annotation. Note, the state stored in other text annotation which has state and statemodel keys. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | Places annotation contents directly on the page, annotation object will be removed. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Returns rectangle of annotation taking into consideration page rotation. |
| [GetState](../../aspose.pdf.annotations/markupannotation/getstate/)() | Gets the state of the annotation. Note, the state stored in other text annotation which has state and statemodel keys. |
| [GetStateModel](../../aspose.pdf.annotations/markupannotation/getstatemodel/)() | Gets the state model of the annotation. Note, the state stored in other text annotation which has state and statemodel keys. |
| [SetMarkedState](../../aspose.pdf.annotations/markupannotation/setmarkedstate/)(bool) | Sets Marked and Unmarked state for the annotation. Note, the state stored in other text annotation which has state and statemodel keys. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState) | Sets the review state for an annotation. Marked and Unmarked states are ignored as they do not belong to the Review StateModel. The state is set by the user who created the target annotation. The value is taken from the Title property of the target annotation. Note, the state stored in other text annotation which has state and statemodel keys. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState, string) | Sets the review state for an annotation. Marked and Unmarked states are ignored as they do not belong to the Review StateModel. Note, the state stored in other text annotation which has state and statemodel keys. |

### See Also

* class [MarkupAnnotation](../markupannotation/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)

