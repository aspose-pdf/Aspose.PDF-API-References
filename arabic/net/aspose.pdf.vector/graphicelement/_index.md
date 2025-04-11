---
title: Class GraphicElement
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Vector.GraphicElement. تمثل الفئة الأساسية لكائنات الرسوميات على الصفحة
type: docs
weight: 11180
url: /ar/net/aspose.pdf.vector/graphicelement/
---
## GraphicElement class

تمثل الفئة الأساسية لكائنات الرسوميات على الصفحة.

```csharp
public abstract class GraphicElement : IDisposable
```

## Properties

| Name | Description |
| --- | --- |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | يحصل على مصفوفة عنصر الرسوميات. يتم تعيين المصفوفة عند إنشاء العنصر. تتغير عند استدعاء SetPosition(). |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | يحصل على مجموعة من العمليات التي تمثل العنصر. |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; } | يحصل على [`XFormPlacement`](../xformplacement/) الحالي الذي يقع فيه العنصر. |
| virtual [Position](../../aspose.pdf.vector/graphicelement/position/) { get; set; } | يحصل أو يحدد الموضع في مساحة الإحداثيات الحالية. إذا كان [`Parent`](./parent/) ليس !:null فإن العنصر لديه مساحة إحداثيات xForm. |
| abstract [Rectangle](../../aspose.pdf.vector/graphicelement/rectangle/) { get; } | يحصل على المستطيل المحيط بـ `GraphicElement`. |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | يحصل على الصفحة التي تم استخراج عنصر الرسوميات منها. |

## Methods

| Name | Description |
| --- | --- |
| virtual [AddOnPage](../../aspose.pdf.vector/graphicelement/addonpage/)(Page) | يضيف العنصر الحالي على الصفحة. إذا كان هناك العديد من العناصر للإضافة، من الأفضل استخدام [`AddGraphics`](../../aspose.pdf/page/addgraphics/). |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/)() | يحرر جميع الموارد المستخدمة بواسطة فئة `GraphicElement`. |
| [Remove](../../aspose.pdf.vector/graphicelement/remove/)() | يزيل العنصر الحالي من الصفحة. إذا كان هناك العديد من العناصر للإزالة، من الأفضل استخدام [`DeleteGraphics`](../../aspose.pdf/page/deletegraphics/). |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/#savetosvg)() | يحول العنصر إلى صورة SVG واحدة. |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/#savetosvg_1)(string) | يحول العنصر إلى ملف صورة SVG واحدة. |

### See Also

* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)