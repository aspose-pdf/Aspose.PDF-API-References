---
title: "SubmitFormAction"
linktitle: "SubmitFormAction"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "فئة تصف إجراء submit-form."
type: docs
weight: 4690
url: /ar/java/com.aspose.pdf/submitformaction/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.PdfAction com.aspose.pdf.SubmitFormAction, com.aspose.pdf.PdfAction, com.aspose.pdf.SubmitFormAction

**All Implemented Interfaces:**
IAppointment

```
public final class SubmitFormAction extends PdfAction
```

فئة تصف إجراء submit-form.

## الحقول

| حقل | الوصف |
| --- | --- |
| [CANONICAL_FORMAT](#CANONICAL_FORMAT) | إذا تم التعيين، يجب تحويل أي قيم حقول مُرسَلة تمثل تواريخ إلى الصيغة القياسية. |
| [EMBED_FORM](#EMBED_FORM) | إذا تم التعيين، يجب أن يكون إدخال F في ملف FDF المُرسَل مواصفة ملف تحتوي على تدفق ملف مدمج يمثل ملف PDF الذي يُرسَل منه الـ FDF. |
| [EXCL_F_KEY](#EXCL_F_KEY) | إذا تم التعيين، يجب أن يستثني الـ FDF المُرسَل إدخال F. |
| [EXCL_NON_USER_ANNOTS](#EXCL_NON_USER_ANNOTS) | إذا تم التعيين، يجب أن يتضمن فقط تلك التعليقات التوضيحية التي يكون إدخال T الخاص بها يطابق اسم المستخدم الحالي. |
| [EXCLUDE](#EXCLUDE) | إذا تم الإلغاء، يحدد مصفوفة Fields الحقول التي يجب تضمينها في الإرسال. |
| [EXPORT_FORMAT](#EXPORT_FORMAT) | إذا تم التعيين، يجب إرسال أسماء الحقول والقيم بصيغة نموذج HTML. |
| [GET_METHOD](#GET_METHOD) | إذا تم التعيين، يجب إرسال أسماء الحقول والقيم باستخدام طلب HTTP GET. |
| [INCLUDE_ANNOTATIONS](#INCLUDE_ANNOTATIONS) | إذا تم التعيين، يجب أن يتضمن ملف FDF المُرسَل جميع التعليقات التوضيحية في مستند PDF الأساسي. |
| [INCLUDE_APPEND_SAVES](#INCLUDE_APPEND_SAVES) | إذا تم التعيين، يجب أن يتضمن ملف FDF المُرسَل محتويات جميع التحديثات المتزايدة. |
| [INCLUDE_NO_VALUE_FIELDS](#INCLUDE_NO_VALUE_FIELDS) | إذا تم التعيين، يجب إرسال جميع الحقول المحددة بواسطة مصفوفة Fields وعلم Include/Exclude. |
| [SUBMIT_COORDINATES](#SUBMIT_COORDINATES) | إذا تم التعيين، يجب نقل إحداثيات نقرة الفأرة التي تسببت في إجراء submit-form كجزء من بيانات النموذج. |
| [SUBMIT_PDF](#SUBMIT_PDF) | إذا تم التعيين، يجب إرسال المستند كملف PDF، باستخدام نوع المحتوى MIME application/pdf. |
| [XFDF](#XFDF) | إذا تم التعيين، يجب إرسال أسماء الحقول والقيم كـ XFDF. |

## المنشئات

| منشئ | الوصف |
| --- | --- |
| [SubmitFormAction](#SubmitFormAction--) | يُهيئ كائن SubmitFormAction. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [getFlags](#getFlags--) | يحصل على flagas لإجراء الإرسال |
| [getUrl](#getUrl--) | عنوان URL الوجهة. |
| [setFlags](#setFlags-int-) | يضبط flagas لإجراء الإرسال. |
| [setUrl](#setUrl-com.aspose.pdf.FileSpecification-) | عنوان URL الوجهة. |

### CANONICAL_FORMAT {#CANONICAL_FORMAT}
```
public static final int CANONICAL_FORMAT
```

إذا تم التعيين، يجب تحويل أي قيم حقول مُرسَلة تمثل تواريخ إلى الصيغة القياسية.

### EMBED_FORM {#EMBED_FORM}
```
public static final int EMBED_FORM
```

إذا تم التعيين، يجب أن يكون إدخال F في ملف FDF المُرسَل مواصفة ملف تحتوي على تدفق ملف مدمج يمثل ملف PDF الذي يُرسَل منه الـ FDF.

### EXCL_F_KEY {#EXCL_F_KEY}
```
public static final int EXCL_F_KEY
```

إذا تم التعيين، يجب أن يستثني الـ FDF المُرسَل إدخال F.

### EXCL_NON_USER_ANNOTS {#EXCL_NON_USER_ANNOTS}
```
public static final int EXCL_NON_USER_ANNOTS
```

إذا تم التعيين، يجب أن يتضمن فقط تلك التعليقات التوضيحية التي يكون إدخال T الخاص بها يطابق اسم المستخدم الحالي.

### EXCLUDE {#EXCLUDE}
```
public static final int EXCLUDE
```

إذا تم الإلغاء، يحدد مصفوفة Fields الحقول التي يجب تضمينها في الإرسال.

### EXPORT_FORMAT {#EXPORT_FORMAT}
```
public static final int EXPORT_FORMAT
```

إذا تم التعيين، يجب إرسال أسماء الحقول والقيم بصيغة نموذج HTML.

### GET_METHOD {#GET_METHOD}
```
public static final int GET_METHOD
```

إذا تم التعيين، يجب إرسال أسماء الحقول والقيم باستخدام طلب HTTP GET.

### INCLUDE_ANNOTATIONS {#INCLUDE_ANNOTATIONS}
```
public static final int INCLUDE_ANNOTATIONS
```

إذا تم التعيين، يجب أن يتضمن ملف FDF المُرسَل جميع التعليقات التوضيحية في مستند PDF الأساسي.

### INCLUDE_APPEND_SAVES {#INCLUDE_APPEND_SAVES}
```
public static final int INCLUDE_APPEND_SAVES
```

إذا تم التعيين، يجب أن يتضمن ملف FDF المُرسَل محتويات جميع التحديثات المتزايدة.

### INCLUDE_NO_VALUE_FIELDS {#INCLUDE_NO_VALUE_FIELDS}
```
public static final int INCLUDE_NO_VALUE_FIELDS
```

إذا تم التعيين، يجب إرسال جميع الحقول المحددة بواسطة مصفوفة Fields وعلم Include/Exclude.

### SUBMIT_COORDINATES {#SUBMIT_COORDINATES}
```
public static final int SUBMIT_COORDINATES
```

إذا تم التعيين، يجب نقل إحداثيات نقرة الفأرة التي تسببت في إجراء submit-form كجزء من بيانات النموذج.

### SUBMIT_PDF {#SUBMIT_PDF}
```
public static final int SUBMIT_PDF
```

إذا تم التعيين، يجب إرسال المستند كملف PDF، باستخدام نوع المحتوى MIME application/pdf.

### XFDF {#XFDF}
```
public static final int XFDF
```

إذا تم التعيين، يجب إرسال أسماء الحقول والقيم كـ XFDF.

### SubmitFormAction {#SubmitFormAction--}
```
public SubmitFormAction()
```

يُهيئ كائن SubmitFormAction.

### getFlags {#getFlags--}
```
public int getFlags()
```

يحصل على flagas لإجراء الإرسال

**Returns:**
قيمة int

### getUrl {#getUrl--}
```
public FileSpecification getUrl()
```

عنوان URL الوجهة.

**Returns:**
قيمة FileSpecification

### setFlags {#setFlags-int-}
```
public void setFlags(int value)
```

يضبط flagas لإجراء الإرسال.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |

### setUrl {#setUrl-com.aspose.pdf.FileSpecification-}
عنوان URL الوجهة.
