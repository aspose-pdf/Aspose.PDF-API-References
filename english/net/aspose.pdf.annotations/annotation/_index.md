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

## Properties

| Name | Description |
| --- | --- |
| [Actions](./actions/) { get; } | Gets list of annotatation actions. |
| virtual [ActiveState](./activestate/) { get; set; } | Gets or sets current annotation appearance state. |
| abstract [AnnotationType](./annotationtype/) { get; } | Gets type of annotation. |
| [Appearance](./appearance/) { get; } | Gets appearance dictionary of the annotation. |
| [Border](./border/) { get; set; } | Gets or sets annotation border characteristics. `Border` |
| [Characteristics](./characteristics/) { get; } | Gets annotation characteristics. |
| [Color](./color/) { get; set; } | Gets or sets annotation color. |
| [Contents](./contents/) { get; set; } | Gets or sets annotation text. |
| [Flags](./flags/) { get; set; } | Flags of the annotation. |
| [FullName](./fullname/) { get; } | Gets full qualified name of the annotation. |
| virtual [Height](./height/) { get; set; } | Gets or sets height of the annotation. |
| [Modified](./modified/) { get; set; } | Gets or sets date and time when annotation was recently modified. |
| [Name](./name/) { get; set; } | Gets or sets annotation name on the page. |
| virtual [PageIndex](./pageindex/) { get; } | Gets index of page which contains annotation. |
| virtual [Rect](./rect/) { get; set; } | Gets or sets annotation rectangle. |
| [States](./states/) { get; } | Gets appearance dictionary of annotation. |
| [TextHorizontalAlignment](./texthorizontalalignment/) { get; set; } | Gets or sets text alignment for annotation. |
| static [UpdateAppearanceOnConvert](./updateappearanceonconvert/) { get; set; } | If true, annotation appearance will be updated before converting PF document into image. This allows convert fields correctly but probably demand more time. |
| static [UseFontSubset](./usefontsubset/) { get; set; } | If this property set to true, fonts will be added to document as subsets. Default value is true. |
| virtual [Width](./width/) { get; set; } | Gets or sets width of the annotation. |

## Methods

| Name | Description |
| --- | --- |
| abstract [Accept](./accept/)(AnnotationSelector) | Accepts visitor for annotation processing. |
| virtual [ChangeAfterResize](./changeafterresize/)(Matrix) | Update parameters and appearance, according to the matrix transform. |
| virtual [Flatten](./flatten/)() | Places annotation contents directly on the page, annotation object will be removed. |
| [GetRectangle](./getrectangle/)(bool) | Returns rectangle of annotation taking into consideration page rotation. |

### See Also

* class [BaseParagraph](../../aspose.pdf/baseparagraph/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)

