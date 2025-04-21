---
title: Class DictionaryEditor
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.DataEditor.DictionaryEditor. فئة للوصول إلى قاموس شجرة المستندات.
type: docs
weight: 3470
url: /ar/net/aspose.pdf.dataeditor/dictionaryeditor/
---
## DictionaryEditor class

فئة للوصول إلى قاموس شجرة المستند (قاموس المستند، قاموس الصفحة، قاموس الموارد).

```csharp
public class DictionaryEditor : IDictionary<string, ICosPdfPrimitive>
```

## Constructors

| Name | Description |
| --- | --- |
| [DictionaryEditor](dictionaryeditor/#constructor)(Document) |  |
| [DictionaryEditor](dictionaryeditor/#constructor_1)(Page) |  |
| [DictionaryEditor](dictionaryeditor/#constructor_2)(Resources) |  |

## Properties

| Name | Description |
| --- | --- |
| [AllKeys](../../aspose.pdf.dataeditor/dictionaryeditor/allkeys/) { get; } | مجموعة كاملة من المفاتيح. تحتوي على مفاتيح قابلة للتعديل وغير قابلة للتعديل. |
| [Count](../../aspose.pdf.dataeditor/dictionaryeditor/count/) { get; } | يحصل على عدد العناصر الموجودة في `DictionaryEditor`. |
| [IsReadOnly](../../aspose.pdf.dataeditor/dictionaryeditor/isreadonly/) { get; } | يحصل على قيمة تشير إلى ما إذا كانت `DictionaryEditor` للقراءة فقط. |
| [Item](../../aspose.pdf.dataeditor/dictionaryeditor/item/) { get; set; } | يحصل أو يحدد العنصر بالمفتاح المحدد. |
| [Keys](../../aspose.pdf.dataeditor/dictionaryeditor/keys/) { get; } | مجموعة من المفاتيح القابلة للتعديل. |
| [Values](../../aspose.pdf.dataeditor/dictionaryeditor/values/) { get; } | يحصل على ICollection تحتوي على القيم في `DictionaryEditor`. |

## Methods

| Name | Description |
| --- | --- |
| [Add](../../aspose.pdf.dataeditor/dictionaryeditor/add/#add)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | تعيين [`ICosPdfPrimitive`](../icospdfprimitive/) إلى القاموس. |
| [Add](../../aspose.pdf.dataeditor/dictionaryeditor/add/#add_1)(string, ICosPdfPrimitive) | تعيين [`ICosPdfPrimitive`](../icospdfprimitive/) إلى القاموس. |
| [Clear](../../aspose.pdf.dataeditor/dictionaryeditor/clear/)() | يزيل جميع العناصر من `DictionaryEditor`. |
| [Contains](../../aspose.pdf.dataeditor/dictionaryeditor/contains/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | يحدد ما إذا كانت `DictionaryEditor` تحتوي على قيمة معينة. |
| [ContainsKey](../../aspose.pdf.dataeditor/dictionaryeditor/containskey/)(string) | يحدد ما إذا كانت `DictionaryEditor` تحتوي على عنصر بالمفتاح المحدد. |
| [CopyTo](../../aspose.pdf.dataeditor/dictionaryeditor/copyto/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf.dataeditor/dictionaryeditor/getenumerator/)() | يعيد عدادًا يتكرر عبر المجموعة. |
| [Remove](../../aspose.pdf.dataeditor/dictionaryeditor/remove/#remove)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | يزيل أول ظهور لكائن معين من `DictionaryEditor`. |
| [Remove](../../aspose.pdf.dataeditor/dictionaryeditor/remove/#remove_1)(string) | يزيل العنصر بالمفتاح المحدد من `DictionaryEditor`. |
| [TryGetValue](../../aspose.pdf.dataeditor/dictionaryeditor/trygetvalue/)(string, out ICosPdfPrimitive) | للوصول إلى نوع البيانات البسيطة مثل السلسلة، الاسم، البوليان، الرقم. يعيد null للأنواع الأخرى. |

### See Also

* interface [ICosPdfPrimitive](../icospdfprimitive/)
* namespace [Aspose.Pdf.DataEditor](../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../)