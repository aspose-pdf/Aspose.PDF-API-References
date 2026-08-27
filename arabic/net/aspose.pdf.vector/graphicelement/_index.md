---
title: "الفئة GraphicElement"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Vector.GraphicElement. تمثل الفئة الأساسية لكائن الرسومات على الصفحة."
type: docs
weight: 11370
url: /ar/net/aspose.pdf.vector/graphicelement/
---
## GraphicElement class

يمثل الفئة الأساسية لكائن الرسومات على الصفحة.

```csharp
public abstract class GraphicElement : IDisposable
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | يحصل على مصفوفة العنصر الرسومي. تُحدد المصفوفة عند إنشاء العنصر. تتغير عندما يتم استدعاء SetPosition(). |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | يحصل على مجموعة من المشغلات التي تمثل العنصر. |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; } | يحصل على الـ [`XFormPlacement`](../xformplacement/) الحالي الذي يقع فيه العنصر. |
| virtual [Position](../../aspose.pdf.vector/graphicelement/position/) { get; set; } | يحصل أو يعيّن الموضع في مساحة الإحداثيات الحالية. إذا كان [`Parent`](./parent/) ليس !:null فإن العنصر يمتلك مساحة إحداثيات xForm. |
| abstract [Rectangle](../../aspose.pdf.vector/graphicelement/rectangle/) { get; } | يحصل على المستطيل المحيط بـ `GraphicElement`. |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | يحصل على الصفحة التي تم استخراج العنصر الرسومي منها. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| virtual [AddOnPage](../../aspose.pdf.vector/graphicelement/addonpage/)(Page) | يضيف العنصر الحالي إلى الصفحة. إذا كان هناك العديد من العناصر لإضافتها، من الأفضل استخدام [`AddGraphics`](../../aspose.pdf/page/addgraphics/). |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/)() | يطلق جميع الموارد المستخدمة بواسطة الفئة `GraphicElement`. |
| [Remove](../../aspose.pdf.vector/graphicelement/remove/)() | يزيل العنصر الحالي من الصفحة. إذا كان هناك العديد من العناصر لإزالتها، من الأفضل استخدام [`DeleteGraphics`](../../aspose.pdf/page/deletegraphics/). |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/#savetosvg)() | يحوّل العنصر إلى صورة SVG واحدة. |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/#savetosvg_1)(string) | يحوّل العنصر إلى ملف صورة SVG واحد. |

### انظر أيضًا

* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)


