---
title: "PageNumberStamp"
linktitle: "PageNumberStamp"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "يمثل ختم رقم الصفحة ويُستخدم لترقيم الصفحات."
type: docs
weight: 3440
url: /ar/java/com.aspose.pdf/pagenumberstamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Stamp com.aspose.pdf.TextStamp com.aspose.pdf.PageNumberStamp, com.aspose.pdf.Stamp, com.aspose.pdf.TextStamp com.aspose.pdf.PageNumberStamp, com.aspose.pdf.TextStamp, com.aspose.pdf.PageNumberStamp

```
public final class PageNumberStamp extends TextStamp
```

يمثل ختم رقم الصفحة ويُستخدم لترقيم الصفحات.

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [PageNumberStamp](#PageNumberStamp--) | ينشئ مثالًا جديدًا من الفئة {@code PageNumberStamp}. تم تعيين التنسيق إلى "#". |
| [PageNumberStamp](#PageNumberStamp-com.aspose.pdf.facades.FormattedText-) | ينشئ مثالًا جديدًا من الفئة {@code PageNumberStamp}. تم تعيين التنسيق إلى "#". |
| [PageNumberStamp](#PageNumberStamp-java.lang.String-) | ينشئ مثالًا جديدًا من الفئة {@code PageNumberStamp}. تم تعيين التنسيق إلى "#". |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getFormat](#getFormat--) | يحصل على قيمة String لتخطيط أرقام الصفحات. يجب أن تشمل القيمة الحرف '#' الذي يُستبدل برقم الصفحة أثناء عملية التخطيط. |
| [getNumberingStyle](#getNumberingStyle--) | نمط الترقيم المستخدم بواسطة هذه الطباعة. |
| [getStartingNumber](#getStartingNumber--) | يحصل على قيمة عدد الصفحة الابتدائية. الصفحات الأخرى سيتم ترقيمها بدءًا من هذه القيمة. |
| [put](#put-com.aspose.pdf.Page-) | يضيف رقم الصفحة. |
| [setFormat](#setFormat-java.lang.String-) | يضبط قيمة سلسلة لتخطيط أرقام الصفحات. يجب أن تشمل القيمة الحرف '#' الذي يُستبدل برقم الصفحة أثناء عملية التخطيط. |
| [setNumberingStyle](#setNumberingStyle-com.aspose.pdf.NumberingStyle-) | نمط الترقيم المستخدم بواسطة هذه الطباعة. |
| [setStartingNumber](#setStartingNumber-int-) | يضبط قيمة عدد الصفحة الابتدائية. الصفحات الأخرى سيتم ترقيمها بدءًا من هذه القيمة. |

### PageNumberStamp {#PageNumberStamp--}
```
public PageNumberStamp()
```

ينشئ مثالًا جديدًا من الفئة {@code PageNumberStamp}. تم تعيين التنسيق إلى "#".

### PageNumberStamp {#PageNumberStamp-com.aspose.pdf.facades.FormattedText-}
ينشئ مثالًا جديدًا من الفئة {@code PageNumberStamp}. تم تعيين التنسيق إلى "#".

### PageNumberStamp {#PageNumberStamp-java.lang.String-}
ينشئ مثالًا جديدًا من الفئة {@code PageNumberStamp}. تم تعيين التنسيق إلى "#".

### getFormat {#getFormat--}
```
public String getFormat()
```

يحصل على قيمة String لتخطيط أرقام الصفحات. يجب أن تشمل القيمة الحرف '#' الذي يُستبدل برقم الصفحة أثناء عملية التخطيط.

**Returns:**
قيمة سلسلة

### getNumberingStyle {#getNumberingStyle--}
```
public NumberingStyle getNumberingStyle()
```

نمط الترقيم المستخدم بواسطة هذه الطباعة.

**Returns:**
قيمة NumberingStyle @see NumberingStyle

### getStartingNumber {#getStartingNumber--}
```
public int getStartingNumber()
```

يحصل على قيمة عدد الصفحة الابتدائية. الصفحات الأخرى سيتم ترقيمها بدءًا من هذه القيمة.

**Returns:**
قيمة int

### put {#put-com.aspose.pdf.Page-}
يضيف رقم الصفحة.

### setFormat {#setFormat-java.lang.String-}
يضبط قيمة سلسلة لتخطيط أرقام الصفحات. يجب أن تشمل القيمة الحرف '#' الذي يُستبدل برقم الصفحة أثناء عملية التخطيط.

### setNumberingStyle {#setNumberingStyle-com.aspose.pdf.NumberingStyle-}
نمط الترقيم المستخدم بواسطة هذه الطباعة.

### setStartingNumber {#setStartingNumber-int-}
```
public void setStartingNumber(int value)
```

يضبط قيمة عدد الصفحة الابتدائية. الصفحات الأخرى سيتم ترقيمها بدءًا من هذه القيمة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |
