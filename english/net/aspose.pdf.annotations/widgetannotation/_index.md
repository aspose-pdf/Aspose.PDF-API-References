---
title: "WidgetAnnotation Class"
linktitle: "WidgetAnnotation"
articleTitle: "WidgetAnnotation"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Annotations.WidgetAnnotation class. Class representing widget annotation."
type: docs
weight: 1350
url: "/net/aspose.pdf.annotations/widgetannotation/"
keywords: "WidgetAnnotation, Aspose.Pdf.Annotations, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## WidgetAnnotation class

Class representing widget annotation.

```csharp
public class WidgetAnnotation : Annotation
```

## Constructors

| Name | Description |
| --- | --- |
| [WidgetAnnotation](./widgetannotation/)(Document) | Create annotation (used for Generator) |

## Properties

| Name | Description |
| --- | --- |
| [Actions](./actions/) { get; } | Gets the annotation actions. |
| virtual [ActiveState](../../aspose.pdf.annotations/annotation/activestate/) { get; set; } | Gets or sets current annotation appearance state. |
| override [AnnotationType](./annotationtype/) { get; } | Gets type of annotation. |
| [Appearance](../../aspose.pdf.annotations/annotation/appearance/) { get; } | Gets appearance dictionary of the annotation. |
| [Border](../../aspose.pdf.annotations/annotation/border/) { get; set; } | Gets or sets annotation border characteristics. `Border` |
| [Characteristics](../../aspose.pdf.annotations/annotation/characteristics/) { get; } | Gets annotation characteristics. |
| [Color](../../aspose.pdf.annotations/annotation/color/) { get; set; } | Gets or sets annotation color. |
| [Contents](../../aspose.pdf.annotations/annotation/contents/) { get; set; } | Gets or sets annotation text. |
| [DefaultAppearance](./defaultappearance/) { get; set; } | Gets or sets default appearance of the field. |
| [Exportable](./exportable/) { get; set; } | Gets or sets exportable flag of the field. |
| [Flags](../../aspose.pdf.annotations/annotation/flags/) { get; set; } | Flags of the annotation. |
| [FullName](../../aspose.pdf.annotations/annotation/fullname/) { get; } | Gets full qualified name of the annotation. |
| virtual [Height](../../aspose.pdf.annotations/annotation/height/) { get; set; } | Gets or sets height of the annotation. |
| [Highlighting](./highlighting/) { get; set; } | Annotation highlighting mode. |
| [Modified](../../aspose.pdf.annotations/annotation/modified/) { get; set; } | Gets or sets date and time when annotation was recently modified. |
| [Name](../../aspose.pdf.annotations/annotation/name/) { get; set; } | Gets or sets annotation name on the page. |
| [OnActivated](./onactivated/) { get; set; } | An action which shall be performed when the annotation is activated. |
| virtual [PageIndex](../../aspose.pdf.annotations/annotation/pageindex/) { get; } | Gets index of page which contains annotation. |
| [Parent](./parent/) { get; } | Gets annotation parent. |
| [ReadOnly](./readonly/) { get; set; } | Gets or sets read only status of the field. |
| virtual [Rect](../../aspose.pdf.annotations/annotation/rect/) { get; set; } | Gets or sets annotation rectangle. |
| [Required](./required/) { get; set; } | Gets or sets required status of the field. |
| [States](../../aspose.pdf.annotations/annotation/states/) { get; } | Gets appearance dictionary of annotation. |
| [TextHorizontalAlignment](../../aspose.pdf.annotations/annotation/texthorizontalalignment/) { get; set; } | Gets or sets text alignment for annotation. |
| static [UpdateAppearanceOnConvert](../../aspose.pdf.annotations/annotation/updateappearanceonconvert/) { get; set; } | If true, annotation appearance will be updated before converting PF document into image. This allows convert fields correctly but probably demand more time. |
| static [UseFontSubset](../../aspose.pdf.annotations/annotation/usefontsubset/) { get; set; } | If this property set to true, fonts will be added to document as subsets. Default value is true. |
| virtual [Width](../../aspose.pdf.annotations/annotation/width/) { get; set; } | Gets or sets width of the annotation. |

## Methods

| Name | Description |
| --- | --- |
| override [Accept](./accept/)(AnnotationSelector) | Accepts visitor. |
| virtual [ChangeAfterResize](../../aspose.pdf.annotations/annotation/changeafterresize/)(Matrix) | Update parameters and appearance, according to the matrix transform. |
| [ExportToJson](./exporttojson/)(Stream, ExportFieldsToJsonOptions) | Exports the specified PDF form field to JSON format and writes the result to the provided stream. |
| [ExportToJson](./exporttojson/)(string, ExportFieldsToJsonOptions) | Exports the specified PDF form field to JSON format and writes the result to the specified file. |
| virtual [Flatten](../../aspose.pdf.annotations/annotation/flatten/)() | Places annotation contents directly on the page, annotation object will be removed. |
| [GetCheckedStateName](./getcheckedstatename/)() | Returns name of "checked" state according to existing state names. |
| [GetRectangle](../../aspose.pdf.annotations/annotation/getrectangle/)(bool) | Returns rectangle of annotation taking into consideration page rotation. |

### See Also

* class [Annotation](../annotation/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)

