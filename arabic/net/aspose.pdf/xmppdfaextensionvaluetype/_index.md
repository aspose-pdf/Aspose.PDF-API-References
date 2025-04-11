---
title: Class XmpPdfAExtensionValueType
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.XmpPdfAExtensionValueType. مخطط PDF/A ValueType مطلوب لجميع أنواع قيم الخصائص التي لم يتم تعريفها في مواصفة XMP 2004، أي لأنواع القيم خارج القائمة التالية: - أنواع المصفوفات (هذه هي أنواع الحاويات التي قد تحتوي على حقل واحد أو أكثر): Alt، Bag، Seq - أنواع القيم الأساسية: Boolean، (مفتوح ومغلق) Choice، Date، Dimensions، Integer، Lang Alt، Locale، MIMEType، ProperName، Real، Text، Thumbnail، URI، URL، XPath - أنواع قيم إدارة الوسائط: AgentName، RenditionClass، ResourceEvent، ResourceRef، Version - نوع قيمة الوظيفة/سير العمل الأساسية: Job - أنواع قيم مخطط EXIF: Flash، CFAPattern، DeviceSettings، GPSCoordinate، OECF/SFR، Rational Schema namespace URI: http://www.aiim.org/pdfa/ns/type# Required schema namespace prefix: pdfaType
type: docs
weight: 11490
url: /ar/net/aspose.pdf/xmppdfaextensionvaluetype/
---
## XmpPdfAExtensionValueType class

مخطط PDF/A ValueType مطلوب لجميع أنواع قيم الخصائص التي لم يتم تعريفها في مواصفة XMP 2004، أي لأنواع القيم خارج القائمة التالية: - أنواع المصفوفات (هذه هي أنواع الحاويات التي قد تحتوي على حقل واحد أو أكثر): Alt، Bag، Seq - أنواع القيم الأساسية: Boolean، (مفتوح ومغلق) Choice، Date، Dimensions، Integer، Lang Alt، Locale، MIMEType، ProperName، Real، Text، Thumbnail، URI، URL، XPath - أنواع قيم إدارة الوسائط: AgentName، RenditionClass، ResourceEvent، ResourceRef، Version - نوع قيمة الوظيفة/سير العمل الأساسية: Job - أنواع قيم مخطط EXIF: Flash، CFAPattern، DeviceSettings، GPSCoordinate، OECF/SFR، Rational Schema namespace URI: http://www.aiim.org/pdfa/ns/type# Required schema namespace prefix: pdfaType

```csharp
public sealed class XmpPdfAExtensionValueType : XmpPdfAExtensionObject
```

## Constructors

| Name | Description |
| --- | --- |
| [XmpPdfAExtensionValueType](xmppdfaextensionvaluetype/)(string, string, string, string) | يقوم بتهيئة كائن جديد. |

## Properties

| Name | Description |
| --- | --- |
| [Description](../../aspose.pdf/xmppdfaextensionobject/description/) { get; } | يحصل على الوصف. |
| [Fields](../../aspose.pdf/xmppdfaextensionvaluetype/fields/) { get; } | يحصل على قائمة الحقول. |
| [NamespaceUri](../../aspose.pdf/xmppdfaextensionvaluetype/namespaceuri/) { get; } | يحصل على URI الخاص بالمساحة الاسمية. |
| [Prefix](../../aspose.pdf/xmppdfaextensionvaluetype/prefix/) { get; } | يحصل على البادئة. |
| [Type](../../aspose.pdf/xmppdfaextensionvaluetype/type/) { get; } | يحصل على نوع القيمة. |
| [Value](../../aspose.pdf/xmppdfaextensionobject/value/) { get; set; } | يحصل على القيمة أو يحددها. |

## Methods

| Name | Description |
| --- | --- |
| [Add](../../aspose.pdf/xmppdfaextensionvaluetype/add/)(XmpPdfAExtensionField) | إضافة حقل جديد. |
| [AddRange](../../aspose.pdf/xmppdfaextensionvaluetype/addrange/)(XmpPdfAExtensionField[]) | يضيف مجموعة من الحقول. |
| [Clear](../../aspose.pdf/xmppdfaextensionvaluetype/clear/)() | يمسح جميع الحقول. |
| override [GetXml](../../aspose.pdf/xmppdfaextensionvaluetype/getxml/)(XmlDocument) | يعيد قائمة عناصر XML التي تمثل نوع القيمة في شجرة XML. |
| [Remove](../../aspose.pdf/xmppdfaextensionvaluetype/remove/)(XmpPdfAExtensionField) | يزيل الحقل من قائمة الحقول. |

### See Also

* class [XmpPdfAExtensionObject](../xmppdfaextensionobject/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)