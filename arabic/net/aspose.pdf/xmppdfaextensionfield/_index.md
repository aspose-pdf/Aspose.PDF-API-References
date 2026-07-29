---
title: "الفئة XmpPdfAExtensionField"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.XmpPdfAExtensionField. يصف هذا المخطط حقلًا في نوع مُنظم. هو مشابه جدًا لمخطط نوع قيمة خاصية PDF/A ولكنه يحدد حقلًا في بنية بدلاً من خاصية. مساحة اسم المخطط URI http//www.aiim.org/pdfa/ns/field. بادئة مساحة اسم المخطط المطلوبة pdfaField."
type: docs
weight: 11630
url: /ar/net/aspose.pdf/xmppdfaextensionfield/
---
## XmpPdfAExtensionField class

هذا المخطط يصف حقلًا في نوع مُنظم. إنه مشابه جدًا لمخطط نوع قيمة خاصية PDF/A، لكنه يعرّف حقلًا في بنية بدلاً من خاصية. URI مساحة اسم المخطط: http://www.aiim.org/pdfa/ns/field# البادئة المطلوبة لمساحة اسم المخطط: pdfaField.

```csharp
public class XmpPdfAExtensionField : XmpPdfAExtensionObject
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [XmpPdfAExtensionField](xmppdfaextensionfield/)(string, string, string, string) | يُنشئ الكائن. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Description](../../aspose.pdf/xmppdfaextensionobject/description/) { get; } | يحصل على الوصف. |
| [Name](../../aspose.pdf/xmppdfaextensionfield/name/) { get; } | اسم الحقل. يجب أن تكون أسماء الحقول صالحة كأسماء عناصر XML. |
| [Value](../../aspose.pdf/xmppdfaextensionobject/value/) { get; set; } | يحصل أو يعيّن القيمة. |
| [ValueType](../../aspose.pdf/xmppdfaextensionfield/valuetype/) { get; } | نوع قيمة الحقل، مأخوذ من مواصفة XMP 2004، أو من مخطط امتداد نوع قيمة PDF/A مدمج. أسماء نوع XMP معرفة مسبقًا أو أسماء الأنواع المخصصة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| override [GetXml](../../aspose.pdf/xmppdfaextensionfield/getxml/)(XmlDocument) | يعيد قائمة عناصر XML التي تمثل الحقل في شجرة XML. |

### انظر أيضًا

* class [XmpPdfAExtensionObject](../xmppdfaextensionobject/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


