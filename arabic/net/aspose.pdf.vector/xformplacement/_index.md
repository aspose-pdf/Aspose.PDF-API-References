---
title: "الفئة XFormPlacement"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Vector.XFormPlacement. تمثّل موضع XForm. إذا تم عرض XForm على الصفحة أكثر من مرة، فإن جميع XformPlacements المرتبطة بهذا XForm ستحتوي على عناصر رسومية مشتركة ولكن بحالات رسومية مختلفة."
type: docs
weight: 11450
url: /ar/net/aspose.pdf.vector/xformplacement/
---
## XFormPlacement class

يمثل وضع XForm. إذا تم عرض XForm على الصفحة أكثر من مرة واحدة، فإن جميع XformPlacements المرتبطة بهذا XForm ستشارك عناصر رسومية مشتركة، لكن بحالات رسومية مختلفة.

```csharp
public sealed class XFormPlacement : GraphicElement
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Elements](../../aspose.pdf.vector/xformplacement/elements/) { get; } | يحصل على العناصر الرسومية داخل هذا XForm. |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | يحصل على مصفوفة العنصر الرسومي. تُحدد المصفوفة عند إنشاء العنصر. تتغير عندما يتم استدعاء SetPosition(). |
| [Name](../../aspose.pdf.vector/xformplacement/name/) { get; } | يحصل على اسم XForm. |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | يحصل على مجموعة من المشغلات التي تمثل العنصر. |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; } | يحصل على `XFormPlacement` الحالي الذي يقع فيه العنصر. |
| override [Position](../../aspose.pdf.vector/xformplacement/position/) { set; } |  |
| override [Rectangle](../../aspose.pdf.vector/xformplacement/rectangle/) { get; } |  |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | يحصل على الصفحة التي تم استخراج العنصر الرسومي منها. |
| [XForm](../../aspose.pdf.vector/xformplacement/xform/) { get; } | يحصل على XForm المرتبط بهذا XFormPlacement. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [AddOnPage](../../aspose.pdf.vector/xformplacement/addonpage/)(Page) | يضيف العنصر الحالي إلى الصفحة. إذا كان هناك العديد من العناصر لإضافتها، من الأفضل استخدام [`AddGraphics`](../../aspose.pdf/page/addgraphics/). |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/)() | يطلق جميع الموارد المستخدمة من قبل فئة [`GraphicElement`](../graphicelement/). |
| [Remove](../../aspose.pdf.vector/graphicelement/remove/)() | يزيل العنصر الحالي من الصفحة. إذا كان هناك العديد من العناصر لإزالتها، من الأفضل استخدام [`DeleteGraphics`](../../aspose.pdf/page/deletegraphics/). |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)() | يحوّل العنصر إلى صورة SVG واحدة. |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)(string) | يحوّل العنصر إلى ملف صورة SVG واحد. |

### انظر أيضًا

* class [GraphicElement](../graphicelement/)
* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)


