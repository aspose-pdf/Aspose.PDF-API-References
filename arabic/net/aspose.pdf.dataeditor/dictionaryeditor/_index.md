---
title: "الفئة DictionaryEditor"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.DataEditor.DictionaryEditor. فئة للوصول إلى شجرة المستندات والقاموس ومستند القاموس وصفحة القاموس وموارد القاموس."
type: docs
weight: 3590
url: /ar/net/aspose.pdf.dataeditor/dictionaryeditor/
---
## DictionaryEditor class

فئة للوصول إلى شجرة القاموس الخاصة بالمستند (قاموس المستند، قاموس الصفحة، قاموس الموارد)

```csharp
public class DictionaryEditor : IDictionary<string, ICosPdfPrimitive>
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [DictionaryEditor](dictionaryeditor/#constructor)(Document) |  |
| [DictionaryEditor](dictionaryeditor/#constructor_1)(Page) |  |
| [DictionaryEditor](dictionaryeditor/#constructor_2)(Resources) |  |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AllKeys](../../aspose.pdf.dataeditor/dictionaryeditor/allkeys/) { get; } | مجموعة كاملة من المفاتيح. تحتوي على مفاتيح قابلة للتحرير وغير قابلة للتحرير. |
| [Count](../../aspose.pdf.dataeditor/dictionaryeditor/count/) { get; } | يحصل على عدد العناصر الموجودة في `DictionaryEditor`. |
| [IsReadOnly](../../aspose.pdf.dataeditor/dictionaryeditor/isreadonly/) { get; } | يحصل على قيمة تشير إلى ما إذا كان `DictionaryEditor` للقراءة فقط. |
| [Item](../../aspose.pdf.dataeditor/dictionaryeditor/item/) { get; set; } | يحصل أو يضبط العنصر بالمفتاح المحدد. |
| [Keys](../../aspose.pdf.dataeditor/dictionaryeditor/keys/) { get; } | مجموعة من المفاتيح القابلة للتحرير. |
| [Values](../../aspose.pdf.dataeditor/dictionaryeditor/values/) { get; } | يحصل على ICollection يحتوي على القيم في `DictionaryEditor`. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Add](../../aspose.pdf.dataeditor/dictionaryeditor/add/#add)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | عيّن [`ICosPdfPrimitive`](../icospdfprimitive/) إلى القاموس. |
| [Add](../../aspose.pdf.dataeditor/dictionaryeditor/add/#add_1)(string, ICosPdfPrimitive) | عيّن [`ICosPdfPrimitive`](../icospdfprimitive/) إلى القاموس. |
| [Clear](../../aspose.pdf.dataeditor/dictionaryeditor/clear/)() | يزيل جميع العناصر من `DictionaryEditor`. |
| [Contains](../../aspose.pdf.dataeditor/dictionaryeditor/contains/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | يحدد ما إذا كان `DictionaryEditor` يحتوي على قيمة محددة. |
| [ContainsKey](../../aspose.pdf.dataeditor/dictionaryeditor/containskey/)(string) | يحدد ما إذا كان `DictionaryEditor` يحتوي على عنصر بالمفتاح المحدد. |
| [CopyTo](../../aspose.pdf.dataeditor/dictionaryeditor/copyto/)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;[], int) |  |
| [GetEnumerator](../../aspose.pdf.dataeditor/dictionaryeditor/getenumerator/)() | يرجع عدّادًا يتنقل عبر المجموعة. |
| [Remove](../../aspose.pdf.dataeditor/dictionaryeditor/remove/#remove)(KeyValuePair&lt;string, ICosPdfPrimitive&gt;) | يزيل أول ظهور لكائن محدد من `DictionaryEditor`. |
| [Remove](../../aspose.pdf.dataeditor/dictionaryeditor/remove/#remove_1)(string) | يزيل العنصر بالمفتاح المحدد من `DictionaryEditor`. |
| [TryGetValue](../../aspose.pdf.dataeditor/dictionaryeditor/trygetvalue/)(string, out ICosPdfPrimitive) | للوصول إلى أنواع البيانات البسيطة مثل السلسلة، الاسم، bool، الرقم. يرجع null للأنواع الأخرى. |

### انظر أيضًا

* interface [ICosPdfPrimitive](../icospdfprimitive/)
* namespace [Aspose.Pdf.DataEditor](../../aspose.pdf.dataeditor/)
* assembly [Aspose.PDF](../../)


