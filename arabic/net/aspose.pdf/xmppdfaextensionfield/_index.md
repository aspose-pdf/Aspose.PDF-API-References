---
title: Class XmpPdfAExtensionField
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.XmpPdfAExtensionField. يصف هذا المخطط حقلًا في نوع منظم. إنه مشابه جدًا لمخطط نوع قيمة خاصية PDF/A ولكنه يحدد حقلًا في هيكل بدلاً من خاصية. URI مساحة اسم المخطط http//www.aiim.org/pdfa/ns/field بادئة مساحة اسم المخطط المطلوبة pdfaField
type: docs
weight: 11440
url: /ar/net/aspose.pdf/xmppdfaextensionfield/
---
## XmpPdfAExtensionField class

يصف هذا المخطط حقلًا في نوع منظم. إنه مشابه جدًا لمخطط نوع قيمة خاصية PDF/A، ولكنه يحدد حقلًا في هيكل بدلاً من خاصية. URI مساحة اسم المخطط: http://www.aiim.org/pdfa/ns/field# بادئة مساحة اسم المخطط المطلوبة: pdfaField.

```csharp
public class XmpPdfAExtensionField : XmpPdfAExtensionObject
```

## Constructors

| Name | Description |
| --- | --- |
| [XmpPdfAExtensionField](xmppdfaextensionfield/)(string, string, string, string) | يقوم بتهيئة الكائن. |

## Properties

| Name | Description |
| --- | --- |
| [Description](../../aspose.pdf/xmppdfaextensionobject/description/) { get; } | يحصل على الوصف. |
| [Name](../../aspose.pdf/xmppdfaextensionfield/name/) { get; } | اسم الحقل. يجب أن تكون أسماء الحقول أسماء عناصر XML صالحة. |
| [Value](../../aspose.pdf/xmppdfaextensionobject/value/) { get; set; } | يحصل على القيمة أو يحددها. |
| [ValueType](../../aspose.pdf/xmppdfaextensionfield/valuetype/) { get; } | نوع قيمة الحقل، مأخوذ من مواصفة XMP 2004، أو مخطط نوع قيمة PDF/A مدمج. أسماء أنواع XMP المعرفة مسبقًا أو أسماء الأنواع المخصصة. |

## Methods

| Name | Description |
| --- | --- |
| override [GetXml](../../aspose.pdf/xmppdfaextensionfield/getxml/)(XmlDocument) | يعيد قائمة بعناصر XML التي تمثل الحقل في شجرة XML. |

### See Also

* class [XmpPdfAExtensionObject](../xmppdfaextensionobject/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)