---
title: "Annotation Class"
linktitle: "Annotation"
articleTitle: "Annotation"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Annotations.Annotation class. Class representing annotation object."
type: docs
weight: 30
url: "/net/aspose.pdf.annotations/annotation/"
keywords: "Annotation, Aspose.Pdf.Annotations, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## Annotation class

Class representing annotation object.

```csharp
public abstract class Annotation : BaseParagraph
```

## Constructors

| Name | Description |
| --- | --- |
| [Annotation](./annotation/#constructor)(*[Page](../../aspose.pdf/page/), [Rectangle](../../aspose.pdf.drawing/rectangle/)*) | Constructor. |
| [Annotation](./annotation/#constructor_1)(*[Document](../../aspose.pdf/document/), [Rectangle](../../aspose.pdf.drawing/rectangle/)*) | Constructor for Annotation. |

## Properties

| Name | Description |
| --- | --- |
| [Actions](./actions/) { get; } | Gets list of annotatation actions. |
| [ActiveState](./activestate/) { get; set; } | Gets or sets current annotation appearance state. |
| [Alignment](./alignment/) { get; set; } | Annotation alignment. This property is obsolete. Use HorizontalAligment instead. |
| [AnnotationType](./annotationtype/) { get; } | Gets type of annotation. |
| [Appearance](./appearance/) { get; } | Gets appearance dictionary of the annotation. |
| [Border](./border/) { get; set; } | Gets or sets annotation border characteristics. `Border`. |
| [Characteristics](./characteristics/) { get; } | Gets annotation characteristics. |
| [Color](./color/) { get; set; } | Gets or sets annotation color. |
| [Contents](./contents/) { get; set; } | Gets or sets annotation text. |
| [Flags](./flags/) { get; set; } | Flags of the annotation. |
| [FullName](./fullname/) { get; } | Gets full qualified name of the annotation. |
| [Height](./height/) { get; set; } | Gets or sets height of the annotation. |
| [HorizontalAlignment](./horizontalalignment/) { get; set; } | Gets or sets text alignment for annotation. |
| [InnerRect](./innerrect/) { get; } | Returns internal rectnagle of annotation, i.e. rectangle recalculated according to RD entry of annotation. |
| [Modified](./modified/) { get; set; } | Gets or sets date and time when annotation was recently modified. |
| [Name](./name/) { get; set; } | Gets or sets annotation name on the page. |
| [NormalAppearance](./normalappearance/) { get; } | Gets normal appearance. |
| [PageIndex](./pageindex/) { get; } | Gets index of page which contains annotation. |
| [Rect](./rect/) { get; set; } | Gets or sets annotation rectangle. |
| [RotatedRect](./rotatedrect/) { get; } | Gets rotated rectangle. |
| [States](./states/) { get; } | Gets appearance dictionary of annotation. |
| [TextHorizontalAlignment](./texthorizontalalignment/) { get; set; } | Gets or sets text alignment for annotation. |
| [UpdateAppearanceOnConvert](./updateappearanceonconvert/) { get; set; } | If true, annotation appearance will be updated before converting PF document into image. This allows convert fields correctly but probably demand more time. |
| [UseFontSubset](./usefontsubset/) { get; set; } | If this property set to true, fonts will be added to document as subsets. Default value is true. |
| [Width](./width/) { get; set; } | Gets or sets width of the annotation. |

## Methods

| Name | Description |
| --- | --- |
| [Accept](./accept/)(*AnnotationSelector*) | Accepts visitor for annotation processing. |
| [ChangeAfterResize](./changeafterresize/)(*Matrix*) | Update parameters and appearance, according to the matrix transform. |
| [CreateExtGStateWithOpacity](./createextgstatewithopacity/)(*XForm*) |  |
| [Flatten](./flatten/) | Places annotation contents directly on the page,. |
| [GetRectangle](./getrectangle/)(*bool*) | Returns rectangle of annotation taking into consideration page rotation. |
| [Initialize](./initialize/)(*Page, Rectangle*) | Initialize the annotation. |
| [Initialize](./initialize/)(*Document, Rectangle*) | Create annotation data structure. |
| [ReadXfdfAttributes](./readxfdfattributes/)(*XmlReader*) | When overridden in a derived class, import annotation attributes from XFDF. |
| [ReadXfdfElements](./readxfdfelements/)(*Dictionary<string, string>*) | When overridden in a derived class, import annotation elements from XFDF. |
| [ToImage](./toimage/)(*ImageFormat*) | Converts annotation to image stream. |
| [WriteXfdfAttributes](./writexfdfattributes/)(*XmlWriter*) | When overridden in a derived class, exports annotation attributes into XFDF. |
| [WriteXfdfElements](./writexfdfelements/)(*XmlWriter*) | When overridden in a derived class, exports annotation elements into XFDF. |

## Fields

| Name | Description |
| --- | --- |
| const [DefaultFontKey](./defaultfontkey/) |  |
| const [DefaultFontName](./defaultfontname/) |  |
| const [DefaultFontSize](./defaultfontsize/) |  |
| [_states](./_states/) |  |

### See Also

* class [BaseParagraph](../../aspose.pdf/baseparagraph/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)

