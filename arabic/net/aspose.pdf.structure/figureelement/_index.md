---
title: Class FigureElement
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Structure.FigureElement. فئة تمثل الشكل الهيكلي المنطقي
type: docs
weight: 10160
url: /ar/net/aspose.pdf.structure/figureelement/
---
## FigureElement class

فئة تمثل الشكل الهيكلي المنطقي.

```csharp
public class FigureElement : Element
```

## Properties

| Name | Description |
| --- | --- |
| virtual [ActualText](../../aspose.pdf.structure/element/actualtext/) { get; set; } | (اختياري؛ PDF 1.4) نص يمثل بديلاً دقيقًا لعنصر الهيكل وأطفاله. هذا النص البديل (الذي يجب أن ينطبق على أصغر قطعة ممكنة من المحتوى) مفيد عند استخراج محتويات الوثيقة لدعم إمكانية الوصول للمستخدمين ذوي الإعاقة أو لأغراض أخرى. |
| virtual [Alt](../../aspose.pdf.structure/element/alt/) { get; set; } | (اختياري) وصف بديل لعنصر الهيكل وأطفاله بصيغة قابلة للقراءة البشرية، وهو مفيد عند استخراج محتويات الوثيقة لدعم إمكانية الوصول للمستخدمين ذوي الإعاقة أو لأغراض أخرى. |
| [Children](../../aspose.pdf.structure/element/children/) { get; } | يحصل على مجموعة العناصر الفرعية. |
| virtual [E](../../aspose.pdf.structure/element/e/) { get; set; } | (اختياري؛ PDF 1.5) الشكل الموسع للاختصار. |
| [Image](../../aspose.pdf.structure/figureelement/image/) { get; } | يحصل على قيمة عنصر الشكل الهيكلي. |
| virtual [Lang](../../aspose.pdf.structure/element/lang/) { get; set; } | (اختياري؛ PDF 1.4) لغة تحدد اللغة الطبيعية لجميع النصوص في عنصر الهيكل باستثناء حيث يتم تجاوزها بمواصفات اللغة للعناصر الهيكلية المتداخلة أو المحتوى المعلم. |

## Methods

| Name | Description |
| --- | --- |
| [Remove](../../aspose.pdf.structure/element/remove/)() | إزالة العنصر. |

### See Also

* class [Element](../element/)
* namespace [Aspose.Pdf.Structure](../../aspose.pdf.structure/)
* assembly [Aspose.PDF](../../)