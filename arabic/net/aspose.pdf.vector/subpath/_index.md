---
title: Class SubPath
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Vector.SubPath. تمثل كائن الرسومات المتجهة على الصفحة. بشكل أساسي، يتم تمثيل كائنات الرسومات المتجهة بواسطة مجموعتين من SubPaths. واحدة منها ممثلة بمجموعة من الخطوط والمنحنيات. الأخرى مقدمة كمستطيلات ويمكن أحيانًا الخلط بينها. عادةً ما تكون منطقة مستطيلة لها لون، ولكن غالبًا ما يتم وضع هذا المستطيل في بداية الصفحة ويحدد المساحة الكاملة للصفحة باللون الأبيض. لذا تحصل على SubPath، ولكن بصريًا ترى فقط النص على الصفحة.
type: docs
weight: 11220
url: /ar/net/aspose.pdf.vector/subpath/
---
## SubPath class

تمثل كائن الرسومات المتجهة على الصفحة. بشكل أساسي، يتم تمثيل كائنات الرسومات المتجهة بواسطة مجموعتين من SubPaths. واحدة منها ممثلة بمجموعة من الخطوط والمنحنيات. الأخرى مقدمة كمستطيلات ويمكن أحيانًا الخلط بينها. عادةً ما تكون منطقة مستطيلة لها لون، ولكن غالبًا ما يتم وضع هذا المستطيل في بداية الصفحة ويحدد المساحة الكاملة للصفحة باللون الأبيض. لذا تحصل على SubPath، ولكن بصريًا ترى فقط النص على الصفحة.

```csharp
public sealed class SubPath : GraphicElement
```

## Properties

| Name | Description |
| --- | --- |
| [Matrix](../../aspose.pdf.vector/graphicelement/matrix/) { get; } | يحصل على مصفوفة العنصر الرسومي. يتم تعيين المصفوفة عند إنشاء العنصر. تتغير عند استدعاء SetPosition(). |
| [Operators](../../aspose.pdf.vector/graphicelement/operators/) { get; } | يحصل على مجموعة من العمليات التي تمثل العنصر. |
| [Parent](../../aspose.pdf.vector/graphicelement/parent/) { get; } | يحصل على [`XFormPlacement`](../xformplacement/) الحالي الذي يقع فيه العنصر. |
| virtual [Position](../../aspose.pdf.vector/graphicelement/position/) { get; set; } | يحصل على أو يحدد الموقع في مساحة الإحداثيات الحالية. إذا كان [`Parent`](../graphicelement/parent/) ليس !:null، فإن العنصر لديه مساحة إحداثيات xForm. |
| override [Rectangle](../../aspose.pdf.vector/subpath/rectangle/) { get; } |  |
| [SourcePage](../../aspose.pdf.vector/graphicelement/sourcepage/) { get; } | يحصل على الصفحة التي تم استخراج العنصر الرسومي منها. |

## Methods

| Name | Description |
| --- | --- |
| virtual [AddOnPage](../../aspose.pdf.vector/graphicelement/addonpage/)(Page) | يضيف العنصر الحالي على الصفحة. إذا كان هناك العديد من العناصر للإضافة، من الأفضل استخدام [`AddGraphics`](../../aspose.pdf/page/addgraphics/). |
| [Dispose](../../aspose.pdf.vector/graphicelement/dispose/)() | يحرر جميع الموارد المستخدمة بواسطة فئة [`GraphicElement`](../graphicelement/). |
| [Remove](../../aspose.pdf.vector/graphicelement/remove/)() | يزيل العنصر الحالي من الصفحة. إذا كان هناك العديد من العناصر للإزالة، من الأفضل استخدام [`DeleteGraphics`](../../aspose.pdf/page/deletegraphics/). |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)() | يحول العنصر إلى صورة SVG واحدة. |
| [SaveToSvg](../../aspose.pdf.vector/graphicelement/savetosvg/)(string) | يحول العنصر إلى ملف صورة SVG واحدة. |

### See Also

* class [GraphicElement](../graphicelement/)
* namespace [Aspose.Pdf.Vector](../../aspose.pdf.vector/)
* assembly [Aspose.PDF](../../)