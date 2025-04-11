---
title: Class XFormPlacement
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Vector.XFormPlacement. تمثل موضع XForm. إذا تم عرض XForm على الصفحة أكثر من مرة واحدة، فستحتوي جميع مواضع XForm المرتبطة بهذا XForm على عناصر رسومية مشتركة ولكن حالات رسومية مختلفة
type: docs
weight: 11260
url: /ar/net/aspose.pdf.vector/xformplacement/
---
## XFormPlacement class

تمثل موضع XForm. إذا تم عرض XForm على الصفحة أكثر من مرة واحدة، فستحتوي جميع مواضع XForm المرتبطة بهذا XForm على عناصر رسومية مشتركة، ولكن حالات رسومية مختلفة.

```csharp
public sealed class XFormPlacement : GraphicElement
```

## Properties

| Name | Description |
| --- | --- |
| [Elements](../../aspose.pdf.vector/xformplacement/elements/) { get; } | يحصل على العناصر الرسومية داخل هذا XForm. |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | يحصل على مصفوفة العنصر الرسومي. يتم تعيين المصفوفة عند إنشاء العنصر. تتغير عند استدعاء SetPosition(). |
| [Name](../../aspose.pdf.vector/xformplacement/name/) { get; } | يحصل على اسم XForm. |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | يحصل على مجموعة من المشغلين الذين يمثلون العنصر. |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; } | يحصل على `XFormPlacement` الحالي الذي يقع فيه العنصر. |
| override [Position](../../aspose.pdf.vector/xformplacement/position/) { set; } |  |
| override [Rectangle](../../aspose.pdf.vector/xformplacement/rectangle/) { get; } |  |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | يحصل على الصفحة التي تم استخراج العنصر الرسومي منها. |
| [XForm](../../aspose.pdf.vector/xformplacement/xform/) { get; } | يحصل على XForm المرتبط بهذا XFormPlacement. |

## Methods

| Name | Description |
| --- | --- |
| override [AddOnPage](../../aspose.pdf.vector/xformplacement/addonpage/)(Page) | يضيف العنصر الحالي على الصفحة. إذا كان هناك العديد من العناصر للإضافة، من الأفضل استخدام [`AddGraphics`](../../aspose.pdf/page/addgraphics/). |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/)() | يحرر جميع الموارد المستخدمة بواسطة فئة [`GraphicElement`](../graphicelement/). |
| [Remove](../../aspose.pdf.vector/graphicelement/remove/)() | يزيل العنصر الحالي من الصفحة. إذا كان هناك العديد من العناصر للإزالة، من الأفضل استخدام [`DeleteGraphics`](../../aspose.pdf/page/deletegraphics/). |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)() | يحول العنصر إلى صورة SVG واحدة. |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)(string) | يحول العنصر إلى ملف صورة SVG واحدة. |

### See Also

* class [GraphicElement](../graphicelement/)
* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)