---
title: "PDF3DAnnotation Class"
linktitle: "PDF3DAnnotation"
articleTitle: "PDF3DAnnotation"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Annotations.PDF3DAnnotation class. Class PDF3DAnnotation. This class cannot be inherited."
type: docs
weight: 770
url: "/net/aspose.pdf.annotations/pdf3dannotation/"
keywords: "PDF3DAnnotation, Aspose.Pdf.Annotations, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## PDF3DAnnotation class

Class PDF3DAnnotation. This class cannot be inherited.

```csharp
public sealed class PDF3DAnnotation : Annotation
```

## Constructors

| Name | Description |
| --- | --- |
| [PDF3DAnnotation](./pdf3dannotation/#constructor)(Page, Rectangle, PDF3DArtwork) | Initializes a new instance of the [`PDF3DAnnotation`](../../aspose.pdf.annotations/pdf3dannotation/) class. |
| [PDF3DAnnotation](./pdf3dannotation/#constructor_1)(Page, Rectangle, PDF3DArtwork, PDF3DActivation) | Initializes a new instance of the [`PDF3DAnnotation`](../../aspose.pdf.annotations/pdf3dannotation/) class. |

## Properties

| Name | Description |
| --- | --- |
| [Actions](../../aspose.pdf.annotations/annotation/actions/) { get; } | Gets list of annotatation actions. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Gets or sets current annotation appearance state. |
| override [AnnotationType](./annotationtype/) { get; } | Gets type of annotation. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Gets appearance dictionary of the annotation. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Gets or sets annotation border characteristics. `Border` |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Gets annotation characteristics. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Gets or sets annotation color. |
| [Content](./content/) { get; set; } | Gets or sets the content. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Gets or sets annotation text. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Flags of the annotation. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Gets full qualified name of the annotation. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Gets or sets height of the annotation. |
| [LightingScheme](./lightingscheme/) { get; } | Gets the lighting scheme. |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Gets or sets date and time when annotation was recently modified. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Gets or sets annotation name on the page. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Gets index of page which contains annotation. |
| [Pdf3DArtwork](./pdf3dartwork/) { get; } | Gets the 3D Artwork. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Gets or sets annotation rectangle. |
| [RenderMode](./rendermode/) { get; } | Gets the render mode. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Gets appearance dictionary of annotation. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Gets or sets text alignment for annotation. |
| static [UpdateAppearanceOnConvert](../../aspose.pdf.annotations/annotation/updateappearanceonconvert/) { get; set; } | If true, annotation appearance will be updated before converting PF document into image. This allows convert fields correctly but probably demand more time. |
| static [UseFontSubset](../../aspose.pdf.annotations/annotation/usefontsubset/) { get; set; } | If this property set to true, fonts will be added to document as subsets. Default value is true. |
| [ViewArray](./viewarray/) { get; } | Gets the view array. |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Gets or sets width of the annotation. |

## Methods

| Name | Description |
| --- | --- |
| override [Accept](./accept/)(AnnotationSelector) | Accepts visitor for annotation processing. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Update parameters and appearance, according to the matrix transform. |
| [ClearImagePreview](./clearimagepreview/)() | Clears the image preview. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | Places annotation contents directly on the page, annotation object will be removed. |
| [GetImagePreview](./getimagepreview/)() | Gets the image preview. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Returns rectangle of annotation taking into consideration page rotation. |
| [SetDefaultViewIndex](./setdefaultviewindex/)(int) | Sets the index of the default view. |
| [SetImagePreview](./setimagepreview/)(Stream) | Sets the image preview. |
| [SetImagePreview](./setimagepreview/)(string) | Sets the image preview. |

### See Also

* [Annotation](../annotation/)
* class [Annotation](../annotation/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)

