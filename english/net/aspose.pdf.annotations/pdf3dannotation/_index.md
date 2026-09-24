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
| [PDF3DAnnotation](./pdf3dannotation/#constructor)(*[Page](../../aspose.pdf/page/), [Rectangle](../../aspose.pdf.drawing/rectangle/), [PDF3DArtwork](../../aspose.pdf.annotations/pdf3dartwork/)*) | Initializes a new instance of the [`PDF3DAnnotation`](../../aspose.pdf.annotations/pdf3dannotation/) class. |
| [PDF3DAnnotation](./pdf3dannotation/#constructor_1)(*[Page](../../aspose.pdf/page/), [Rectangle](../../aspose.pdf.drawing/rectangle/), [PDF3DArtwork](../../aspose.pdf.annotations/pdf3dartwork/), [PDF3DActivation](../../aspose.pdf.annotations/pdf3dactivation/)*) | Initializes a new instance of the [`PDF3DAnnotation`](../../aspose.pdf.annotations/pdf3dannotation/) class. |

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
| [Content](./content/) { get; set; } | Gets or sets the content. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Gets or sets annotation text. *(Inherited from Annotation)* |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Flags of the annotation. *(Inherited from Annotation)* |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Gets full qualified name of the annotation. *(Inherited from Annotation)* |
| [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Gets or sets height of the annotation. *(Inherited from Annotation)* |
| [HorizontalAlignment](../../aspose.pdf.annotations/annotation/horizontalalignment/) { get; set; } | Gets or sets text alignment for annotation. *(Inherited from Annotation)* |
| [InnerRect](../../aspose.pdf.annotations/annotation/innerrect/) { get; } | Returns internal rectnagle of annotation, i.e. rectangle recalculated according to RD entry of annotation. *(Inherited from Annotation)* |
| [LightingScheme](./lightingscheme/) { get; } | Gets the lighting scheme. |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Gets or sets date and time when annotation was recently modified. *(Inherited from Annotation)* |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Gets or sets annotation name on the page. *(Inherited from Annotation)* |
| [NormalAppearance](../../aspose.pdf.annotations/annotation/normalappearance/) { get; } | Gets normal appearance. *(Inherited from Annotation)* |
| [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Gets index of page which contains annotation. *(Inherited from Annotation)* |
| [Pdf3DArtwork](./pdf3dartwork/) { get; } | Gets the 3D Artwork. |
| [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Gets or sets annotation rectangle. *(Inherited from Annotation)* |
| [RenderMode](./rendermode/) { get; } | Gets the render mode. |
| [RotatedRect](../../aspose.pdf.annotations/annotation/rotatedrect/) { get; } | Gets rotated rectangle. *(Inherited from Annotation)* |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Gets appearance dictionary of annotation. *(Inherited from Annotation)* |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Gets or sets text alignment for annotation. *(Inherited from Annotation)* |
| [UpdateAppearanceOnConvert](../../aspose.pdf.annotations/annotation/updateappearanceonconvert/) { get; set; } | If true, annotation appearance will be updated before converting PF document into image. This allows convert fields correctly but probably demand more time. *(Inherited from Annotation)* |
| [UseFontSubset](../../aspose.pdf.annotations/annotation/usefontsubset/) { get; set; } | If this property set to true, fonts will be added to document as subsets. Default value is true. *(Inherited from Annotation)* |
| [ViewArray](./viewarray/) { get; } | Gets the view array. |
| [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Gets or sets width of the annotation. *(Inherited from Annotation)* |

## Methods

| Name | Description |
| --- | --- |
| [Accept](./accept/)(*AnnotationSelector*) | Accepts visitor for annotation processing. |
| [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(*Matrix*) | Update parameters and appearance, according to the matrix transform. *(Inherited from Annotation)* |
| [ClearImagePreview](./clearimagepreview/) | Clears the image preview. |
| [CreateExtGStateWithOpacity](../../aspose.pdf.annotations/annotation/createextgstatewithopacity/)(*XForm*) | *(Inherited from Annotation)* |
| [Flatten](../../aspose.pdf.annotations/annotation/flatten/) | Places annotation contents directly on the page,. *(Inherited from Annotation)* |
| [GetImagePreview](./getimagepreview/) | Gets the image preview. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(*bool*) | Returns rectangle of annotation taking into consideration page rotation. *(Inherited from Annotation)* |
| [Initialize](../../aspose.pdf.annotations/annotation/initialize/)(*Page, Rectangle*) | Initialize the annotation. *(Inherited from Annotation)* |
| [ReadXfdfAttributes](../../aspose.pdf.annotations/annotation/readxfdfattributes/)(*XmlReader*) | When overridden in a derived class, import annotation attributes from XFDF. *(Inherited from Annotation)* |
| [ReadXfdfElements](../../aspose.pdf.annotations/annotation/readxfdfelements/)(*Dictionary<string, string>*) | When overridden in a derived class, import annotation elements from XFDF. *(Inherited from Annotation)* |
| [SetDefaultViewIndex](./setdefaultviewindex/)(*int*) | Sets the index of the default view. |
| [SetImagePreview](./setimagepreview/)(*string*) | Sets the image preview. |
| [SetImagePreview](./setimagepreview/)(*Stream*) | Sets the image preview. |
| [ToImage](../../aspose.pdf.annotations/annotation/toimage/)(*ImageFormat*) | Converts annotation to image stream. *(Inherited from Annotation)* |
| [WriteXfdfAttributes](../../aspose.pdf.annotations/annotation/writexfdfattributes/)(*XmlWriter*) | When overridden in a derived class, exports annotation attributes into XFDF. *(Inherited from Annotation)* |
| [WriteXfdfElements](../../aspose.pdf.annotations/annotation/writexfdfelements/)(*XmlWriter*) | When overridden in a derived class, exports annotation elements into XFDF. *(Inherited from Annotation)* |

## Fields

| Name | Description |
| --- | --- |
| const [DefaultFontKey](../../aspose.pdf.annotations/annotation/defaultfontkey/) | *(Inherited from Annotation)* |
| const [DefaultFontName](../../aspose.pdf.annotations/annotation/defaultfontname/) | *(Inherited from Annotation)* |
| const [DefaultFontSize](../../aspose.pdf.annotations/annotation/defaultfontsize/) | *(Inherited from Annotation)* |
| [_states](../../aspose.pdf.annotations/annotation/_states/) | *(Inherited from Annotation)* |

### See Also

* [Annotation](../annotation/)
* class [Annotation](../annotation/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)

