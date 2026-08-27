---
title: "الفئة SubPath"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.Vector.SubPath. تمثل كائن رسومات متجهة على الصفحة. أساسًا يتم تمثيل كائنات الرسومات المتجهة بواسطة مجموعتين من SubPaths. واحدة منها تمثل مجموعة من الخطوط والمنحنيات. الأخرى تُعرض ك rectangles وقد تُسبب ارتباكًا أحيانًا. عادةً ما تكون مساحة مستطيلة لها لون، لكن غالبًا ما يتم وضع هذا المستطيل في بداية الصفحة ويحدد كامل مساحة الصفحة باللون الأبيض. لذا تحصل على الـ SubPath لكن بصريًا لا ترى سوى النص على الصفحة."
type: docs
weight: 11410
url: /ar/net/aspose.pdf.vector/subpath/
---
## SubPath class

يمثل كائن رسومات متجهة على الصفحة. أساسًا، يتم تمثيل كائنات الرسومات المتجهة بمجموعتين من SubPaths. يتم تمثيل إحداهما بمجموعة من الخطوط والمنحنيات. تُعرض الأخرى كمستطيلات ويمكن أن تُختلط أحيانًا. عادةً ما تكون مساحة مستطيلة لها لون، لكن كثيرًا ما يتم وضع هذا المستطيل في بداية الصفحة ويحدد كامل مساحة الصفحة باللون الأبيض. لذا تحصل على SubPath، لكن بصريًا لا ترى سوى النص على الصفحة.

```csharp
public sealed class SubPath : GraphicElement
```

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | يحصل على مصفوفة العنصر الرسومي. تُحدد المصفوفة عند إنشاء العنصر. تتغير عندما يتم استدعاء SetPosition(). |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | يحصل على مجموعة من المشغلات التي تمثل العنصر. |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; } | يحصل على الـ [`XFormPlacement`](../xformplacement/) الحالي الذي يقع فيه العنصر. |
| virtual [Position](../../aspose.pdf.vector/graphicelement/position/) { get; set; } | يحصل أو يعيّن الموضع في مساحة الإحداثيات الحالية. إذا كان [`Parent`](../graphicelement/parent/) ليس !:null فإن العنصر يمتلك مساحة إحداثيات xForm. |
| override [Rectangle](../../aspose.pdf.vector/subpath/rectangle/) { get; } |  |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | يحصل على الصفحة التي تم استخراج العنصر الرسومي منها. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| virtual [AddOnPage](../../aspose.pdf.vector/graphicelement/addonpage/)(Page) | يضيف العنصر الحالي إلى الصفحة. إذا كان هناك العديد من العناصر لإضافتها، من الأفضل استخدام [`AddGraphics`](../../aspose.pdf/page/addgraphics/). |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/)() | يطلق جميع الموارد المستخدمة من قبل فئة [`GraphicElement`](../graphicelement/). |
| [Remove](../../aspose.pdf.vector/graphicelement/remove/)() | يزيل العنصر الحالي من الصفحة. إذا كان هناك العديد من العناصر لإزالتها، من الأفضل استخدام [`DeleteGraphics`](../../aspose.pdf/page/deletegraphics/). |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)() | يحوّل العنصر إلى صورة SVG واحدة. |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)(string) | يحوّل العنصر إلى ملف صورة SVG واحد. |

### انظر أيضًا

* class [GraphicElement](../graphicelement/)
* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)


