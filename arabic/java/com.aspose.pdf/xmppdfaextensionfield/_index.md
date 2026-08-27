---
title: "XmpPdfAExtensionField"
linktitle: "XmpPdfAExtensionField"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يصف هذا المخطط حقلًا في نوع مُنظم. إنه مشابه جدًا لمخطط نوع قيمة خاصية PDF/A، لكنه يعرّف حقلًا في بنية بدلاً من خاصية. المخطط."
type: docs
weight: 5690
url: /ar/java/com.aspose.pdf/xmppdfaextensionfield/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XmpPdfAExtensionObject com.aspose.pdf.XmpPdfAExtensionField, com.aspose.pdf.XmpPdfAExtensionObject, com.aspose.pdf.XmpPdfAExtensionField

```
public class XmpPdfAExtensionField extends XmpPdfAExtensionObject
```

هذا المخطط يصف حقلًا في نوع مُنظم. إنه مشابه جدًا لمخطط نوع قيمة خاصية PDF/A، لكنه يحدد حقلًا في بنية بدلاً من خاصية. عنوان مساحة اسم المخطط: http://www.aiim.org/pdfa/ns/field# البادئة المطلوبة لمساحة اسم المخطط: pdfaField.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [XmpPdfAExtensionField](#XmpPdfAExtensionField-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | يُنشئ الكائن. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getName](#getName--) | اسم الحقل. يجب أن تكون أسماء الحقول صالحة كأسماء عناصر XML. |
| [getValueType](#getValueType--) | نوع قيمة الحقل، مستمد من مواصفة XMP 2004، أو مخطط امتداد نوع قيمة PDF/A مدمج. أسماء نوع XMP معرفة مسبقًا أو أسماء الأنواع المخصصة. |
| [getXml_](#getXml_-com.aspose.ms.System.Xml.XmlDocument-) | يُعيد قائمة عناصر XML التي تمثل الحقل في شجرة XML. |
| [getXmlInternal](#getXmlInternal-com.aspose.ms.System.Xml.XmlDocument-) | يُعيد قائمة عناصر XML التي تمثل الحقل في شجرة XML. |

### XmpPdfAExtensionField {#XmpPdfAExtensionField-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
يُنشئ الكائن.

### getName {#getName--}
```
public String getName()
```

اسم الحقل. يجب أن تكون أسماء الحقول صالحة كأسماء عناصر XML.

**Returns:**
سلسلة

### getValueType {#getValueType--}
```
public String getValueType()
```

نوع قيمة الحقل، مستمد من مواصفة XMP 2004، أو مخطط امتداد نوع قيمة PDF/A مدمج. أسماء نوع XMP معرفة مسبقًا أو أسماء الأنواع المخصصة.

**Returns:**
سلسلة

### getXml_ {#getXml_-com.aspose.ms.System.Xml.XmlDocument-}
يُعيد قائمة عناصر XML التي تمثل الحقل في شجرة XML.

### getXmlInternal {#getXmlInternal-com.aspose.ms.System.Xml.XmlDocument-}
يُعيد قائمة عناصر XML التي تمثل الحقل في شجرة XML.
