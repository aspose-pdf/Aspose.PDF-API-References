---
title: "RedactionAnnotation Class"
linktitle: "RedactionAnnotation"
articleTitle: "RedactionAnnotation"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Annotations.RedactionAnnotation class. Represents Redact annotation."
type: docs
weight: 1020
url: "/net/aspose.pdf.annotations/redactionannotation/"
keywords: "RedactionAnnotation, Aspose.Pdf.Annotations, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## RedactionAnnotation class

Represents Redact annotation.

```csharp
public sealed class RedactionAnnotation : MarkupAnnotation
```

## Constructors

| Name | Description |
| --- | --- |
| [RedactionAnnotation](./redactionannotation/#constructor)(*[Document](../../aspose.pdf/document/)*) | Constructor for RedactionAnnotation. For using in Generator. |
| [RedactionAnnotation](./redactionannotation/#constructor_1)(*[Page](../../aspose.pdf/page/), [Rectangle](../../aspose.pdf.drawing/rectangle/)*) | Constructor for RedactAnnotation. |

## Properties

| Name | Description |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Gets list of annotatation actions. *(Inherited from Annotation)* |
| [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Gets or sets current annotation appearance state. *(Inherited from Annotation)* |
| [Alignment](../../aspose.pdf.annotations/annotation/alignment/) { get; set; } | Annotation alignment. This property is obsolete. Use HorizontalAligment instead. *(Inherited from Annotation)* |
| [AnnotationType](./annotationtype/) { get; } | Gets type of annotation. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Gets appearance dictionary of the annotation. *(Inherited from Annotation)* |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Gets or sets annotation border characteristics. `Border`. *(Inherited from Annotation)* |
| [BorderColor](./bordercolor/) { get; set; } | Gets or sets color of border which is drawn when redaction is not active. |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Gets annotation characteristics. *(Inherited from Annotation)* |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Gets or sets annotation color. *(Inherited from Annotation)* |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Gets or sets annotation text. *(Inherited from Annotation)* |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate/) { get; set; } | Gets date and time when annotation was created. *(Inherited from MarkupAnnotation)* |
| [DefaultAppearance](./defaultappearance/) { get; set; } | Gets or sets the default appearance string to be used in formatting the text. |
| [FillColor](./fillcolor/) { get; set; } | Gets or sets color to fill annotation. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Flags of the annotation. *(Inherited from Annotation)* |
| [FontSize](./fontsize/) { get; set; } | Gets or sets font size for OverlayText. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Gets full qualified name of the annotation. *(Inherited from Annotation)* |
| [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Gets or sets height of the annotation. *(Inherited from Annotation)* |
| [HorizontalAlignment](../../aspose.pdf.annotations/annotation/horizontalalignment/) { get; set; } | Gets or sets text alignment for annotation. *(Inherited from Annotation)* |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto/) { get; set; } | A reference to the annotation that this annotation is "in reply to". *(Inherited from MarkupAnnotation)* |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Gets or sets date and time when annotation was recently modified. *(Inherited from Annotation)* |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Gets or sets annotation name on the page. *(Inherited from Annotation)* |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity/) { get; set; } | Gets or sets the constant opacity value to be used in painting the annotation. *(Inherited from MarkupAnnotation)* |
| [OverlayText](./overlaytext/) { get; set; } | Gets or sets text to print on redact annotation. |
| [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Gets index of page which contains annotation. *(Inherited from Annotation)* |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup/) { get; set; } | Pop-up annotation for entering or editing the text associated with this annotation. *(Inherited from MarkupAnnotation)* |
| [QuadPoint](./quadpoint/) { get; set; } | An array of 8xN numbers specifying the coordinates of content region that is intended to be removed. |
| [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Gets or sets annotation rectangle. *(Inherited from Annotation)* |
| [Repeat](./repeat/) { get; set; } | If true overlay text will be repated on the annotation. |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype/) { get; set; } | A string specifying the relationship (the "reply type") between this annotation. *(Inherited from MarkupAnnotation)* |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext/) { get; set; } | Gets or sets a rich text string to be displayed in the pop-up window when the annotation is opened. *(Inherited from MarkupAnnotation)* |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Gets appearance dictionary of annotation. *(Inherited from Annotation)* |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject/) { get; set; } | Gets text representing desciption of the object. *(Inherited from MarkupAnnotation)* |
| [TextAlignment](./textalignment/) { get; set; } | Gets or sets. Alignment of Overlay Text. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Gets or sets text alignment for annotation. *(Inherited from Annotation)* |
| [Title](../../aspose.pdf.annotations/markupannotation/title/) { get; set; } | Gets or sets a text label that shall be displayed in the title bar of the annotation�s popup window when open and active. *(Inherited from MarkupAnnotation)* |
| [UpdateAppearanceOnConvert](../../aspose.pdf.annotations/annotation/updateappearanceonconvert/) { get; set; } | If true, annotation appearance will be updated before converting PF document into image. This allows convert fields correctly but probably demand more time. *(Inherited from Annotation)* |
| [UseFontSubset](../../aspose.pdf.annotations/annotation/usefontsubset/) { get; set; } | If this property set to true, fonts will be added to document as subsets. Default value is true. *(Inherited from Annotation)* |
| [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Gets or sets width of the annotation. *(Inherited from Annotation)* |

## Methods

| Name | Description |
| --- | --- |
| [Accept](./accept/)(*AnnotationSelector*) | Accepts visitor object to process the annotation. |
| [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(*Matrix*) | Update parameters and appearance, according to the matrix transform. *(Inherited from Annotation)* |
| [ClearState](../../aspose.pdf.annotations/markupannotation/clearstate/) | Clears state and state model for the annotation. *(Inherited from MarkupAnnotation)* |
| [Flatten](./flatten/) | Flattens annotation i.e. removes annotation and adds its. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(*bool*) | Returns rectangle of annotation taking into consideration page rotation. *(Inherited from Annotation)* |
| [GetState](../../aspose.pdf.annotations/markupannotation/getstate/) | Gets the state of the annotation. *(Inherited from MarkupAnnotation)* |
| [GetStateModel](../../aspose.pdf.annotations/markupannotation/getstatemodel/) | Gets the state model of the annotation. *(Inherited from MarkupAnnotation)* |
| [Redact](./redact/) | Flattens annotation and redacts page contents (i.e. removes text and image under redacted annotation). |
| [SetMarkedState](../../aspose.pdf.annotations/markupannotation/setmarkedstate/)(*bool*) | Sets Marked and Unmarked state for the annotation. *(Inherited from MarkupAnnotation)* |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(*AnnotationState*) | Sets the review state for an annotation. Marked and Unmarked states are ignored as they do not belong to the Review StateModel. *(Inherited from MarkupAnnotation)* |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(*AnnotationState, string*) | Sets the review state for an annotation. Marked and Unmarked states are ignored as they do not belong to the Review StateModel. *(Inherited from MarkupAnnotation)* |

### See Also

* class [MarkupAnnotation](../markupannotation/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)

