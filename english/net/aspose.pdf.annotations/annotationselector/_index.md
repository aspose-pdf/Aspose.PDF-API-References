---
title: "AnnotationSelector Class"
linktitle: "AnnotationSelector"
articleTitle: "AnnotationSelector"
second_title: "Aspose.PDF for .NET"
description: "This class is used for selecting annotations using Visitor template idea."
type: docs
weight: 70
url: "/net/aspose.pdf.annotations/annotationselector/"
keywords: "AnnotationSelector, Aspose.Pdf.Annotations, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## AnnotationSelector class

This class is used for selecting annotations using Visitor template idea.

```csharp
public sealed class AnnotationSelector : IAnnotationVisitor
```

## Constructors

| Name | Description |
| --- | --- |
| [AnnotationSelector](./annotationselector/#constructor) | Initializes new instance of the AnnotationSelector class. |
| [AnnotationSelector](./annotationselector/#constructor_1)(*[Annotation](../../aspose.pdf.annotations/annotation/)*) | Initializes new [`AnnotationSelector`](../../aspose.pdf.annotations/annotationselector/) object. |

## Properties

| Name | Description |
| --- | --- |
| [Selected](./selected/) { get; } | The list of selected objects. |

## Methods

| Name | Description |
| --- | --- |
| [Visit](./visit/)(*LinkAnnotation*) | Select link annotation if AnnotationSelector was initialized with LinkAnnotation object. |
| [Visit](./visit/)(*FileAttachmentAnnotation*) | Select attachment annotation if AnnotationSelector was initialized with FileAttachmentAnnotation object. |
| [Visit](./visit/)(*TextAnnotation*) | Select text annotation if AnnotationSelector was initialized with TextAnnotation object. |
| [Visit](./visit/)(*RedactionAnnotation*) | Select redact annotation if AnnotationSelector was initialized with RedactAnnotation object. |
| [Visit](./visit/)(*FreeTextAnnotation*) | Select freetext annotation if AnnotationSelector was initialized with FreeTextAnnotation object. |
| [Visit](./visit/)(*HighlightAnnotation*) | Select attachment annotation if AnnotationSelector was initialized with FreeTextAnnotation object. |
| [Visit](./visit/)(*UnderlineAnnotation*) | Select underline annotation if AnnotationSelector was initialized with UnderlineAnnotation object. |
| [Visit](./visit/)(*StrikeOutAnnotation*) | Select strikeOut annotation if AnnotationSelector was initialized with StrikeOutAnnotation object. |
| [Visit](./visit/)(*SquigglyAnnotation*) | Select squiggly annotation if AnnotationSelector was initialized with SquigglyAnnotation object. |
| [Visit](./visit/)(*PopupAnnotation*) | Select popup annotation if AnnotationSelector was initialized with PopupAnnotation object. |
| [Visit](./visit/)(*LineAnnotation*) | Select line annotation if AnnotationSelector was initialized with LineAnnotation object. |
| [Visit](./visit/)(*CircleAnnotation*) | Select circle annotation if AnnotationSelector was initialized with CircleAnnotation object. |
| [Visit](./visit/)(*SquareAnnotation*) | Select square annotation if AnnotationSelector was initialized with SquareAnnotation object. |
| [Visit](./visit/)(*InkAnnotation*) | Select ink annotation if AnnotationSelector was initialized with InkAnnotation object. |
| [Visit](./visit/)(*PolylineAnnotation*) | Select polyline annotation if AnnotationSelector was initialized with PolylineAnnotation object. |
| [Visit](./visit/)(*PolygonAnnotation*) | Select polygon annotation if AnnotationSelector was initialized with PolygonAnnotation object. |
| [Visit](./visit/)(*CaretAnnotation*) | Select caret annotation if AnnotationSelector was initialized with CaretAnnotation object. |
| [Visit](./visit/)(*StampAnnotation*) | Select stamp annotation if AnnotationSelector was initialized with StampAnnotation object. |
| [Visit](./visit/)(*WidgetAnnotation*) | Select widget annotation if AnnotationSelector was initialized with WidgetAnnotation object. |
| [Visit](./visit/)(*WatermarkAnnotation*) | Select watermark annotation if AnnotationSelector was initialized with WatermarkAnnotation object. |
| [Visit](./visit/)(*MovieAnnotation*) | Select movie annotation if AnnotationSelector was initialized with MovieAnnotation object. |
| [Visit](./visit/)(*RichMediaAnnotation*) | Select movie annotation if AnnotationSelector was initialized with RichMedia annotation object. |
| [Visit](./visit/)(*ScreenAnnotation*) | Select screen annotation if AnnotationSelector was initialized with ScreenAnnotation object. |
| [Visit](./visit/)(*PDF3DAnnotation*) | Select PDF3D annotation if AnnotationSelector was initialized with PDF3DAnnotation object. |
| [Visit](./visit/)(*ColorBarAnnotation*) | Select ColorBar annotation if AnnotationSelector was initialized with ColorBar object. |
| [Visit](./visit/)(*TrimMarkAnnotation*) | Selects the if the [`AnnotationSelector`](../../aspose.pdf.annotations/annotationselector/) was initialized with a [`TrimMarkAnnotation`](../../aspose.pdf.annotations/trimmarkannotation/) object. |
| [Visit](./visit/)(*BleedMarkAnnotation*) | Selects the if the [`AnnotationSelector`](../../aspose.pdf.annotations/annotationselector/) was initialized with a. |
| [Visit](./visit/)(*RegistrationMarkAnnotation*) | Selects the if the [`AnnotationSelector`](../../aspose.pdf.annotations/annotationselector/) was initialized with a. |
| [Visit](./visit/)(*PageInformationAnnotation*) | Selects the if the [`AnnotationSelector`](../../aspose.pdf.annotations/annotationselector/) was initialized with a. |

### See Also

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)

