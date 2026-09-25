---
title: "PolylineAnnotation Class"
linktitle: "PolylineAnnotation"
articleTitle: "PolylineAnnotation"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Annotations.PolylineAnnotation class. Represents polyline annotation that is similar to polygon, except that the first and last vertex are not imp..."
type: docs
weight: 940
url: "/net/aspose.pdf.annotations/polylineannotation/"
keywords: "PolylineAnnotation, Aspose.Pdf.Annotations, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## PolylineAnnotation class

Represents polyline annotation that is similar to polygon, except that the first and last vertex are not implicitly connected.

```csharp
public sealed class PolylineAnnotation : PolyAnnotation
```

## Constructors

| Name | Description |
| --- | --- |
| [PolylineAnnotation](./polylineannotation/#constructor)(*[Page](../../aspose.pdf/page/), [Rectangle](../../aspose.pdf.drawing/rectangle/), Point[]*) | Creates new Polyline annotation on the specified page. |

## Properties

| Name | Description |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Gets list of annotatation actions. *(Inherited from Annotation)* |
| [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Gets or sets current annotation appearance state. *(Inherited from Annotation)* |
| [Alignment](../../aspose.pdf.annotations/annotation/alignment/) { get; set; } | Annotation alignment. This property is obsolete. Use HorizontalAligment instead. *(Inherited from Annotation)* |
| [AnnotationType](./annotationtype/) { get; } | Gets type of annotation. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Gets appearance dictionary of the annotation. *(Inherited from Annotation)* |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Gets or sets annotation border characteristics. `Border`. *(Inherited from Annotation)* |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Gets annotation characteristics. *(Inherited from Annotation)* |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Gets or sets annotation color. *(Inherited from Annotation)* |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Gets or sets annotation text. *(Inherited from Annotation)* |
| [CreationDate](../../aspose.pdf.annotations/markupannotation/creationdate/) { get; set; } | Gets date and time when annotation was created. *(Inherited from MarkupAnnotation)* |
| [EndingStyle](../../aspose.pdf.annotations/polyannotation/endingstyle/) { get; set; } | Gets or sets the style of second line ending. *(Inherited from PolyAnnotation)* |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Flags of the annotation. *(Inherited from Annotation)* |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Gets full qualified name of the annotation. *(Inherited from Annotation)* |
| [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Gets or sets height of the annotation. *(Inherited from Annotation)* |
| [HorizontalAlignment](../../aspose.pdf.annotations/annotation/horizontalalignment/) { get; set; } | Gets or sets text alignment for annotation. *(Inherited from Annotation)* |
| [InReplyTo](../../aspose.pdf.annotations/markupannotation/inreplyto/) { get; set; } | A reference to the annotation that this annotation is "in reply to". *(Inherited from MarkupAnnotation)* |
| [Intent](../../aspose.pdf.annotations/polyannotation/intent/) { get; set; } | Gets or sets the intent of the polygon or polyline annotation. *(Inherited from PolyAnnotation)* |
| [InteriorColor](../../aspose.pdf.annotations/polyannotation/interiorcolor/) { get; set; } | Gets or sets the interior color with which to fill the annotation's line endings. *(Inherited from PolyAnnotation)* |
| [Measure](../../aspose.pdf.annotations/polyannotation/measure/) { get; set; } | Measure units specifed for this annotation. *(Inherited from PolyAnnotation)* |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Gets or sets date and time when annotation was recently modified. *(Inherited from Annotation)* |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Gets or sets annotation name on the page. *(Inherited from Annotation)* |
| [Opacity](../../aspose.pdf.annotations/markupannotation/opacity/) { get; set; } | Gets or sets the constant opacity value to be used in painting the annotation. *(Inherited from MarkupAnnotation)* |
| [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Gets index of page which contains annotation. *(Inherited from Annotation)* |
| [Popup](../../aspose.pdf.annotations/markupannotation/popup/) { get; set; } | Pop-up annotation for entering or editing the text associated with this annotation. *(Inherited from MarkupAnnotation)* |
| [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Gets or sets annotation rectangle. *(Inherited from Annotation)* |
| [ReplyType](../../aspose.pdf.annotations/markupannotation/replytype/) { get; set; } | A string specifying the relationship (the "reply type") between this annotation. *(Inherited from MarkupAnnotation)* |
| [RichText](../../aspose.pdf.annotations/markupannotation/richtext/) { get; set; } | Gets or sets a rich text string to be displayed in the pop-up window when the annotation is opened. *(Inherited from MarkupAnnotation)* |
| [StartingStyle](../../aspose.pdf.annotations/polyannotation/startingstyle/) { get; set; } | Gets or sets the style of first line ending. *(Inherited from PolyAnnotation)* |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Gets appearance dictionary of annotation. *(Inherited from Annotation)* |
| [Subject](../../aspose.pdf.annotations/markupannotation/subject/) { get; set; } | Gets text representing desciption of the object. *(Inherited from MarkupAnnotation)* |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Gets or sets text alignment for annotation. *(Inherited from Annotation)* |
| [Title](../../aspose.pdf.annotations/markupannotation/title/) { get; set; } | Gets or sets a text label that shall be displayed in the title bar of the annotation�s popup window when open and active. *(Inherited from MarkupAnnotation)* |
| [UpdateAppearanceOnConvert](../../aspose.pdf.annotations/annotation/updateappearanceonconvert/) { get; set; } | If true, annotation appearance will be updated before converting PF document into image. This allows convert fields correctly but probably demand more time. *(Inherited from Annotation)* |
| [UseFontSubset](../../aspose.pdf.annotations/annotation/usefontsubset/) { get; set; } | If this property set to true, fonts will be added to document as subsets. Default value is true. *(Inherited from Annotation)* |
| [Vertices](../../aspose.pdf.annotations/polyannotation/vertices/) { get; set; } | Gets or sets an array of points representing the horizontal and vertical coordinates of each vertex. *(Inherited from PolyAnnotation)* |
| [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Gets or sets width of the annotation. *(Inherited from Annotation)* |

## Methods

| Name | Description |
| --- | --- |
| [Accept](./accept/)(*AnnotationSelector*) | Accepts visitor object to process the annotation. |
| [ChangeAfterResize](../../aspose.pdf.annotations/polyannotation/changeafterresize/)(*Matrix*) | Updates the points in Vertices, according to the matrix transform. *(Inherited from PolyAnnotation)* |
| [ClearState](../../aspose.pdf.annotations/markupannotation/clearstate/) | Clears state and state model for the annotation. *(Inherited from MarkupAnnotation)* |
| [Flatten](../../aspose.pdf.annotations/annotation/flatten/) | Places annotation contents directly on the page,. *(Inherited from Annotation)* |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(*bool*) | Returns rectangle of annotation taking into consideration page rotation. *(Inherited from Annotation)* |
| [GetState](../../aspose.pdf.annotations/markupannotation/getstate/) | Gets the state of the annotation. *(Inherited from MarkupAnnotation)* |
| [GetStateModel](../../aspose.pdf.annotations/markupannotation/getstatemodel/) | Gets the state model of the annotation. *(Inherited from MarkupAnnotation)* |
| [SetMarkedState](../../aspose.pdf.annotations/markupannotation/setmarkedstate/)(*bool*) | Sets Marked and Unmarked state for the annotation. *(Inherited from MarkupAnnotation)* |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(*AnnotationState*) | Sets the review state for an annotation. Marked and Unmarked states are ignored as they do not belong to the Review StateModel. *(Inherited from MarkupAnnotation)* |
| [SetReviewState](../../aspose.pdf.annotations/markupannotation/setreviewstate/)(*AnnotationState, string*) | Sets the review state for an annotation. Marked and Unmarked states are ignored as they do not belong to the Review StateModel. *(Inherited from MarkupAnnotation)* |

### See Also

* class [PolyAnnotation](../polyannotation/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)

