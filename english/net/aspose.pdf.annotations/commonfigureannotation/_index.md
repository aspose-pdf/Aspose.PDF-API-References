---
title: Class CommonFigureAnnotation
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.CommonFigureAnnotation class. Abstract class representing common figure annotation
type: docs
weight: 280
url: /net/aspose.pdf.annotations/commonfigureannotation/
---
## CommonFigureAnnotation class

Abstract class representing common figure annotation.

```csharp
public abstract class CommonFigureAnnotation : MarkupAnnotation
```

## Constructors

| Name | Description |
| --- | --- |
| [CommonFigureAnnotation](commonfigureannotation/)(Document) | Constructor for using in Generator. |

## Properties

| Name | Description |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Gets list of annotatation actions. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Gets or sets current annotation appearance state. |
| abstract [AnnotationType](../../aspose.pdf.annotations/annotation/annotationtype/) { get; } | Gets type of annotation. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Gets appearance dictionary of the annotation. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Gets or sets annotation border characteristics. [`Border`](../annotation/border/) |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Gets annotation characteristics. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Gets or sets annotation color. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Gets or sets annotation text. |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate/) { get; } | Gets date and time when annotation was created. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Flags of the annotation. |
| [Frame](../../aspose.pdf.annotations/commonfigureannotation/frame/) { get; set; } | The rectangle describing the numerical differences between two rectangles: the Rect entry of the annotation and the actual boundaries of the underlying square or circle. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Gets full qualified name of the annotation. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Gets or sets height of the annotation. |
| virtual [Hyperlink](../../aspose.pdf/baseparagraph/hyperlink/) { get; set; } | Gets or sets the fragment hyperlink(for pdf generator). |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto/) { get; set; } | A reference to the annotation that this annotation is "in reply to". Both annotations must be on the same page of the document. |
| [InteriorColor](../../aspose.pdf.annotations/commonfigureannotation/interiorcolor/) { get; set; } | Interior color with which to fill the annotation�s rectangle or ellipse. |
| [IsFirstParagraphInColumn](../../aspose.pdf/baseparagraph/isfirstparagraphincolumn/) { get; set; } | Gets or sets a bool value that indicates whether this paragraph will be at next column. Default is false.(for pdf generation) |
| [IsInLineParagraph](../../aspose.pdf/baseparagraph/isinlineparagraph/) { get; set; } | Gets or sets a paragraph is inline. Default is false.(for pdf generation) |
| [IsInNewPage](../../aspose.pdf/baseparagraph/isinnewpage/) { get; set; } | Gets or sets a bool value that force this paragraph generates at new page. Default is false.(for pdf generation) |
| [IsKeptWithNext](../../aspose.pdf/baseparagraph/iskeptwithnext/) { get; set; } | Gets or sets a bool value that indicates whether current paragraph remains in the same page along with next paragraph. Default is false.(for pdf generation) |
| [Margin](../../aspose.pdf/baseparagraph/margin/) { get; set; } | Gets or sets a outer margin for paragraph (for pdf generation) |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Gets or sets date and time when annotation was recently modified. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Gets or sets annotation name on the page. |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity/) { get; set; } | Gets or sets the constant opacity value to be used in painting the annotation. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Gets index of page which contains annotation. |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup/) { get; set; } | Pop-up annotation for entering or editing the text associated with this annotation. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Gets or sets annotation rectangle. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype/) { get; set; } | A string specifying the relationship (the "reply type") between this annotation and one specified by InReplyTo. |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext/) { get; set; } | Gets or sets a rich text string to be displayed in the pop-up window when the annotation is opened. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Gets appearance dictionary of annotation. |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject/) { get; set; } | Gets text representing desciption of the object. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Gets or sets text alignment for annotation. |
| [Title](../../aspose.pdf.annotations/markupannotation/title/) { get; set; } | Gets or sets a text that shall be displayed in title bar of annotation. |
| virtual [VerticalAlignment](../../aspose.pdf/baseparagraph/verticalalignment/) { get; set; } | Gets or sets a vertical alignment of paragraph |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Gets or sets width of the annotation. |
| [ZIndex](../../aspose.pdf/baseparagraph/zindex/) { get; set; } | Gets or sets a int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page. |

## Methods

| Name | Description |
| --- | --- |
| abstract [Accept](../../aspose.pdf.annotations/annotation/accept/)(AnnotationSelector) | Accepts visitor for annotation processing. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Update parameters and appearance, according to the matrix transform. |
| [ClearState](../../aspose.pdf.annotations/markupannotation/clearstate/)() | Clears state and state model for the annotation. For example, clears the review status for an annotation. Note, the state stored in other text annotation which has state and statemodel keys. |
| virtual [Clone](../../aspose.pdf/baseparagraph/clone/)() | Clones this instance. Virtual method. Always return null. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | Places annotation contents directly on the page, annotation object will be removed. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Returns rectangle of annotation taking into consideration page rotation. |
| [GetState](../../aspose.pdf.annotations/markupannotation/getstate/)() | Gets the state of the annotation. Note, the state stored in other text annotation which has state and statemodel keys. |
| [GetStateModel](../../aspose.pdf.annotations/markupannotation/getstatemodel/)() | Gets the state model of the annotation. Note, the state stored in other text annotation which has state and statemodel keys. |
| [SetMarkedState](../../aspose.pdf.annotations/markupannotation/setmarkedstate/)(bool) | Sets Marked и Unmarked state for the annotation. Note, the state stored in other text annotation which has state and statemodel keys. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState) | Sets the review state for an annotation. Marked and Unmarked states are ignored as they do not belong to the Review StateModel. The state is set by the user who created the target annotation. The value is taken from the Title property of the target annotation. Note, the state stored in other text annotation which has state and statemodel keys. |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(AnnotationState, string) | Sets the review state for an annotation. Marked and Unmarked states are ignored as they do not belong to the Review StateModel. Note, the state stored in other text annotation which has state and statemodel keys. |

### See Also

* class [MarkupAnnotation](../markupannotation/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


