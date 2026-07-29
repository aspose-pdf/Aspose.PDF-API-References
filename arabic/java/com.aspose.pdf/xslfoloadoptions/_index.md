---
title: "XslFoLoadOptions"
linktitle: "XslFoLoadOptions"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل خيارات تحميل/استيراد ملف XSL-FO إلى مستند PDF."
type: docs
weight: 5780
url: /ar/java/com.aspose.pdf/xslfoloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.XmlLoadOptions com.aspose.pdf.XslFoLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.XmlLoadOptions com.aspose.pdf.XslFoLoadOptions, com.aspose.pdf.XmlLoadOptions, com.aspose.pdf.XslFoLoadOptions

```
public final class XslFoLoadOptions extends XmlLoadOptions
```

يمثل خيارات تحميل/استيراد ملف XSL-FO إلى مستند PDF.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [XslFoLoadOptions](#XslFoLoadOptions--) | ينشئ كائن {@code XslFoLoadOptions} بدون بيانات xsl. |
| [XslFoLoadOptions](#XslFoLoadOptions-java.io.InputStream-) | ينشئ كائن {@code XslFoLoadOptions} بدون بيانات xsl. |
| [XslFoLoadOptions](#XslFoLoadOptions-java.lang.String-) | ينشئ كائن {@code XslFoLoadOptions} بدون بيانات xsl. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getBasePath](#getBasePath--) | المسار/الرابط الأساسي الذي يتم منه البحث عن المسارات النسبية للموارد الخارجية (إن وجدت) المشار إليها في ملف SVG المحمل. |
| [getParsingErrorsHandlingType](#getParsingErrorsHandlingType--) | قد يحتوي مستند XSLFO المصدر على أخطاء تنسيق. يعدد هذا enum الاستراتيجيات الممكنة لمعالجة تلك الأخطاء |
| [setBasePath](#setBasePath-java.lang.String-) |  |
| [setParsingErrorsHandlingType](#setParsingErrorsHandlingType-int-) | قد يحتوي مستند XSLFO المصدر على أخطاء تنسيق. يعدد هذا enum الاستراتيجيات الممكنة لمعالجة تلك الأخطاء |

### XslFoLoadOptions {#XslFoLoadOptions--}
```
public XslFoLoadOptions()
```

ينشئ كائن {@code XslFoLoadOptions} بدون بيانات xsl.

### XslFoLoadOptions {#XslFoLoadOptions-java.io.InputStream-}
ينشئ كائن {@code XslFoLoadOptions} بدون بيانات xsl.

### XslFoLoadOptions {#XslFoLoadOptions-java.lang.String-}
ينشئ كائن {@code XslFoLoadOptions} بدون بيانات xsl.

### getBasePath {#getBasePath--}
```
public String getBasePath()
```

المسار/الرابط الأساسي الذي يتم منه البحث عن المسارات النسبية للموارد الخارجية (إن وجدت) المشار إليها في ملف SVG المحمل.

**Returns:**
سلسلة

### getParsingErrorsHandlingType {#getParsingErrorsHandlingType--}
```
public int getParsingErrorsHandlingType()
```

قد يحتوي مستند XSLFO المصدر على أخطاء تنسيق. يعدد هذا enum الاستراتيجيات الممكنة لمعالجة تلك الأخطاء

**Returns:**
عنصر ParsingErrorsHandlingTypes @see ParsingErrorsHandlingTypes

### setBasePath {#setBasePath-java.lang.String-}


### setParsingErrorsHandlingType {#setParsingErrorsHandlingType-int-}
```
public void setParsingErrorsHandlingType(int parsingErrorsHandlingType)
```

قد يحتوي مستند XSLFO المصدر على أخطاء تنسيق. يعدد هذا enum الاستراتيجيات الممكنة لمعالجة تلك الأخطاء

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| parsingErrorsHandlingType |  | عنصر ParsingErrorsHandlingTypes @see ParsingErrorsHandlingTypes |
