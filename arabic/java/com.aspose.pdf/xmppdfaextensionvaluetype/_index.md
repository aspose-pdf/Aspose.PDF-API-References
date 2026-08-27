---
title: "XmpPdfAExtensionValueType"
linktitle: "XmpPdfAExtensionValueType"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "مخطط PDF/A ValueType مطلوب لجميع أنواع قيم الخصائص التي لم يتم تعريفها في مواصفة XMP 2004، أي لأنواع القيم خارج القائمة التالية: -."
type: docs
weight: 5740
url: /ar/java/com.aspose.pdf/xmppdfaextensionvaluetype/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XmpPdfAExtensionObject com.aspose.pdf.XmpPdfAExtensionValueType, com.aspose.pdf.XmpPdfAExtensionObject, com.aspose.pdf.XmpPdfAExtensionValueType

```
public final class XmpPdfAExtensionValueType extends XmpPdfAExtensionObject
```

مخطط PDF/A ValueType مطلوب لجميع أنواع قيم الخاصية التي لم يتم تعريفها في مواصفة XMP 2004، أي لأنواع القيم خارج القائمة التالية: - أنواع المصفوفة (هذه أنواع حاوية قد تحتوي على حقل أو أكثر): Alt, Bag, Seq - أنواع القيم الأساسية: Boolean, (open and closed) Choice, Date, Dimensions, Integer, Lang Alt, Locale, MIMEType, ProperName, Real, Text, Thumbnail, URI, URL, XPath - أنواع قيم إدارة الوسائط: AgentName, RenditionClass, ResourceEvent, ResourceRef, Version - نوع قيمة الوظيفة/سير العمل الأساسي: Job - أنواع قيم مخطط EXIF: Flash, CFAPattern, DeviceSettings, GPSCoordinate, OECF/SFR, Rational عنوان مساحة اسم المخطط: http://www.aiim.org/pdfa/ns/type# البادئة المطلوبة لمساحة اسم المخطط: pdfaType

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [XmpPdfAExtensionValueType](#XmpPdfAExtensionValueType-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | يقوم بتهيئة كائن جديد. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [add](#add-com.aspose.pdf.XmpPdfAExtensionField-) | أضف حقلًا جديدًا. |
| [addRange](#addRange-com.aspose.pdf.XmpPdfAExtensionField:A-) | يضيف نطاق الحقول. |
| [clear](#clear--) | يمسح جميع الحقول. |
| [getFields](#getFields--) | يحصل على قائمة الحقول. |
| [getNamespaceUri](#getNamespaceUri--) | يحصل على URI مساحة الاسم. |
| [getPrefix](#getPrefix--) | يحصل على البادئة. |
| [getType](#getType--) | يحصل على نوع القيمة. |
| [getXml_](#getXml_-com.aspose.ms.System.Xml.XmlDocument-) | يُعيد قائمة عناصر XML التي تمثل الحقل في شجرة XML. |
| [getXmlInternal](#getXmlInternal-com.aspose.ms.System.Xml.XmlDocument-) | يعيد قائمة عناصر XML التي تمثل نوع القيمة في شجرة XML. |
| [remove](#remove-com.aspose.pdf.XmpPdfAExtensionField-) | يزيل الحقل من قائمة الحقول. |

### XmpPdfAExtensionValueType {#XmpPdfAExtensionValueType-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
يقوم بتهيئة كائن جديد.

### add {#add-com.aspose.pdf.XmpPdfAExtensionField-}
أضف حقلًا جديدًا.

### addRange {#addRange-com.aspose.pdf.XmpPdfAExtensionField:A-}
يضيف نطاق الحقول.

### clear {#clear--}
```
public void clear()
```

يمسح جميع الحقول.

### getFields {#getFields--}
```
public com.aspose.ms.System.Collections.Generic.List< XmpPdfAExtensionField > getFields()
```

يحصل على قائمة الحقول.

**Returns:**
IList

### getNamespaceUri {#getNamespaceUri--}
```
public String getNamespaceUri()
```

يحصل على URI مساحة الاسم.

**Returns:**
سلسلة

### getPrefix {#getPrefix--}
```
public String getPrefix()
```

يحصل على البادئة.

**Returns:**
سلسلة

### getType {#getType--}
```
public String getType()
```

يحصل على نوع القيمة.

**Returns:**
سلسلة

### getXml_ {#getXml_-com.aspose.ms.System.Xml.XmlDocument-}
يُعيد قائمة عناصر XML التي تمثل الحقل في شجرة XML.

### getXmlInternal {#getXmlInternal-com.aspose.ms.System.Xml.XmlDocument-}
يعيد قائمة عناصر XML التي تمثل نوع القيمة في شجرة XML.

### remove {#remove-com.aspose.pdf.XmpPdfAExtensionField-}
يزيل الحقل من قائمة الحقول.
