---
title: "الفئة XmpPdfAExtensionValueType"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "الفئة Aspose.Pdf.XmpPdfAExtensionValueType. مخطط قيمة PDF/A ValueType مطلوب لجميع أنواع قيم الخصائص التي لم تُعرّف في مواصفة XMP 2004 أي لأنواع القيم خارج القائمة التالية: أنواع المصفوفة التي هي أنواع حاوية قد تحتوي على حقل أو أكثر Alt Bag Seq الأنواع الأساسية Boolean open and closed Choice Date Dimensions Integer Lang Alt Locale MIMEType ProperName Real Text Thumbnail URI URL XPath أنواع قيمة إدارة الوسائط AgentName RenditionClass ResourceEvent ResourceRef Version الأنواع الأساسية للوظيفة/سير العمل Job مخططات EXIF أنواع قيمة Flash CFAPattern DeviceSettings GPSCoordinate OECF/SFR Rational مساحة اسم المخطط URI http//www.aiim.org/pdfa/ns/type مساحة الاسم المطلوبة بادئة المخطط pdfaType"
type: docs
weight: 11680
url: /ar/net/aspose.pdf/xmppdfaextensionvaluetype/
---
## XmpPdfAExtensionValueType class

مخطط PDF/A ValueType مطلوب لجميع أنواع قيم الخصائص التي لم تُعرّف في مواصفة XMP 2004، أي لأنواع القيم خارج القائمة التالية: - أنواع المصفوفات (هذه أنواع حاوية قد تحتوي على حقل أو أكثر): Alt, Bag, Seq - أنواع القيم الأساسية: Boolean, (open and closed) Choice, Date, Dimensions, Integer, Lang Alt, Locale, MIMEType, ProperName, Real, Text, Thumbnail, URI, URL, XPath - أنواع قيم إدارة الوسائط: AgentName, RenditionClass, ResourceEvent, ResourceRef, Version - نوع قيمة أساسي للوظيفة/سير العمل: Job - أنواع قيم مخطط EXIF: Flash, CFAPattern, DeviceSettings, GPSCoordinate, OECF/SFR, Rational URI مساحة اسم المخطط: http://www.aiim.org/pdfa/ns/type# البادئة المطلوبة لمساحة اسم المخطط: pdfaType

```csharp
public sealed class XmpPdfAExtensionValueType : XmpPdfAExtensionObject
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [XmpPdfAExtensionValueType](xmppdfaextensionvaluetype/)(string, string, string, string) | يُهيئ كائنًا جديدًا. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Description](../../aspose.pdf/xmppdfaextensionobject/description/) { get; } | يحصل على الوصف. |
| [Fields](../../aspose.pdf/xmppdfaextensionvaluetype/fields/) { get; } | يحصل على قائمة الحقول. |
| [NamespaceUri](../../aspose.pdf/xmppdfaextensionvaluetype/namespaceuri/) { get; } | الحصول على مساحة الاسم URI. |
| [Prefix](../../aspose.pdf/xmppdfaextensionvaluetype/prefix/) { get; } | الحصول على البادئة. |
| [Type](../../aspose.pdf/xmppdfaextensionvaluetype/type/) { get; } | يحصل على نوع القيمة. |
| [Value](../../aspose.pdf/xmppdfaextensionobject/value/) { get; set; } | يحصل أو يعيّن القيمة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Add](../../aspose.pdf/xmppdfaextensionvaluetype/add/)(XmpPdfAExtensionField) | إضافة حقل جديد. |
| [AddRange](../../aspose.pdf/xmppdfaextensionvaluetype/addrange/)(XmpPdfAExtensionField[]) | إضافة نطاق الحقول. |
| [Clear](../../aspose.pdf/xmppdfaextensionvaluetype/clear/)() | مسح جميع الحقول. |
| override [GetXml](../../aspose.pdf/xmppdfaextensionvaluetype/getxml/)(XmlDocument) | إرجاع قائمة عناصر xml التي تمثل نوع القيمة في شجرة xml. |
| [Remove](../../aspose.pdf/xmppdfaextensionvaluetype/remove/)(XmpPdfAExtensionField) | إزالة الحقل من قائمة الحقول. |

### انظر أيضًا

* class [XmpPdfAExtensionObject](../xmppdfaextensionobject/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


