---
title: "IPdfFileStamp"
linktitle: "IPdfFileStamp"
second_title: "مرجع API لـ Aspose.PDF للـ Java"
description: "واجهة لإضافة الختم (علامة مائية أو خلفية) إلى ملفات PDF."
type: docs
weight: 320
url: /ar/java/com.aspose.pdf.facades/ipdffilestamp/
---
```
public interface IPdfFileStamp
```

واجهة لإضافة الختم (علامة مائية أو خلفية) إلى ملفات PDF.

## الحقول

| حقل | الوصف |
| --- | --- |
| [POS_BOTTOM_LEFT](#POS_BOTTOM_LEFT) | الموضع السفلي الأيسر. |
| [POS_BOTTOM_MIDDLE](#POS_BOTTOM_MIDDLE) | الموضع السفلي الأوسط. |
| [POS_BOTTOM_RIGHT](#POS_BOTTOM_RIGHT) | الموضع السفلي الأيمن. |
| [POS_SIDES_LEFT](#POS_SIDES_LEFT) | الموضع الأيسر. |
| [POS_SIDES_RIGHT](#POS_SIDES_RIGHT) | الموضع الأيمن. |
| [POS_UPPER_LEFT](#POS_UPPER_LEFT) | الموضع العلوي الأيسر. |
| [POS_UPPER_MIDDLE](#POS_UPPER_MIDDLE) | الموضع العلوي الأوسط. |
| [POS_UPPER_RIGHT](#POS_UPPER_RIGHT) | الموضع العلوي الأيمن. |

## الطرق

| طريقة | الوصف |
| --- | --- |
| [addFooter](#addFooter-com.aspose.pdf.facades.FormattedText-float-) | يضيف تذييلًا إلى صفحات المستند. |
| [addFooter](#addFooter-com.aspose.pdf.facades.FormattedText-float-float-float-) | يضيف تذييلًا إلى صفحات المستند. |
| [addFooter](#addFooter-java.io.InputStream-float-) | يضيف صورة ك تذييل للصفحة. |
| [addFooter](#addFooter-java.io.InputStream-float-float-float-) | يضيف صورة ك تذييل للصفحة. |
| [addFooter](#addFooter-java.lang.String-float-) | يضيف صورة ك تذييل إلى صفحات المستند. |
| [addFooter](#addFooter-java.lang.String-float-float-float-) | يضيف صورة ك تذييل للصفحات. |
| [addHeader](#addHeader-com.aspose.pdf.facades.FormattedText-float-) | يضيف رأسًا للصفحة. |
| [addHeader](#addHeader-com.aspose.pdf.facades.FormattedText-float-float-float-) | يضيف رأسًا إلى صفحات الملف. |
| [addHeader](#addHeader-java.io.InputStream-float-) | يضيف صورة ك رأس على الصفحات. |
| [addHeader](#addHeader-java.io.InputStream-float-float-float-) | يضيف صورة في أعلى الصفحة. |
| [addHeader](#addHeader-java.lang.String-float-) | يضيف صورة ك رأس إلى صفحات الملف. |
| [addHeader](#addHeader-java.lang.String-float-float-float-) | يضيف صورة ك رأس على الصفحات. |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-) | يضيف رقم الصفحة إلى الصفحة. |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-float-float-) | يضيف رقم الصفحة في الموضع المحدد على الصفحة. |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-int-) | يضيف رقم الصفحة إلى الصفحات. |
| [addPageNumber](#addPageNumber-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-) | يضيف رقم الصفحة إلى صفحات المستند. |
| [addPageNumber](#addPageNumber-java.lang.String-) | أضف رقم الصفحة إلى الملف. |
| [addPageNumber](#addPageNumber-java.lang.String-float-float-) | يضيف رقم الصفحة في الموضع المحدد على الصفحة. |
| [addPageNumber](#addPageNumber-java.lang.String-int-) | يضيف رقم الصفحة إلى الصفحات. |
| [addPageNumber](#addPageNumber-java.lang.String-int-float-float-float-float-) | يضيف رقم الصفحة إلى صفحات المستند. |
| [addStamp](#addStamp-com.aspose.pdf.facades.Stamp-) | يضيف ختمًا إلى الملف. |
| [close](#close--) | يغلق الملفات المفتوحة ويحفظ التغييرات. |
| [dispose](#dispose--) | مهمل. |
| [getAttachmentName](#getAttachmentName--) | يحصل على اسم المرفق عندما يتم تخزين نتيجة العملية في كائنات HttpResponse كمرفق. |
| [getContentDisposition](#getContentDisposition--) | يحصل على كيفية تخزين المحتوى عندما يتم تخزين نتيجة العملية في كائن HttpResponse. |
| [getDocument](#getDocument--) | يحصل على المستند الذي يعمل عليه PdfFileStamp. |
| [getInputFile](#getInputFile--) | يحصل على اسم ومسار ملف الإدخال. |
| [getInputStream](#getInputStream--) | يحصل على تدفق الإدخال. |
| [getKeepSecurity](#getKeepSecurity--) | يحافظ على الأمان إذا كان صحيحًا. |
| [getOutputFile](#getOutputFile--) | يحصل على اسم ومسار ملف الإخراج. |
| [getOutputStream](#getOutputStream--) | يحصل على تدفق الإخراج. |
| [getPageHeight](#getPageHeight--) | يحصل على ارتفاع الصفحة الأولى في ملف المصدر. |
| [getPageNumberRotation](#getPageNumberRotation--) | يحصل على دوران رقم الصفحة. |
| [getPageWidth](#getPageWidth--) | يحصل على عرض الصفحة الأولى في ملف الإدخال. |
| [getSaveOptions](#getSaveOptions--) | يحصل على خيارات الحفظ عندما يتم تخزين النتيجة كـ HttpResponse. |
| [getStartingNumber](#getStartingNumber--) | يحصل أو يضبط الرقم الابتدائي للصفحة الأولى في ملف الإدخال. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | يضبط اسم المرفق عندما يتم تخزين نتيجة العملية في كائنات HttpResponse كمرفق. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | يضبط كيفية تخزين المحتوى عندما يتم تخزين نتيجة العملية في كائن HttpResponse. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | يضبط تنسيق ملف PDF. |
| [setInputFile](#setInputFile-java.lang.String-) | يضبط اسم ومسار ملف الإدخال. |
| [setInputStream](#setInputStream-java.io.InputStream-) | يضبط تدفق الإدخال. |
| [setKeepSecurity](#setKeepSecurity-boolean-) | ضبط الحفاظ على الأمان |
| [setOutputFile](#setOutputFile-java.lang.String-) | يضبط اسم ومسار ملف الإخراج. |
| [setOutputStream](#setOutputStream-java.io.OutputStream-) | يضبط أو يضبط تدفق الإخراج. |
| [setPageNumberRotation](#setPageNumberRotation-float-) | يضبط دوران رقم الصفحة. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | يضبط خيارات الحفظ عندما يتم تخزين النتيجة كـ HttpResponse. |
| [setStartingNumber](#setStartingNumber-int-) | يضبط الرقم الابتدائي للصفحة الأولى في ملف الإدخال. |

### POS_BOTTOM_LEFT {#POS_BOTTOM_LEFT}
```
static final int POS_BOTTOM_LEFT
```

الموضع السفلي الأيسر.

### POS_BOTTOM_MIDDLE {#POS_BOTTOM_MIDDLE}
```
static final int POS_BOTTOM_MIDDLE
```

الموضع السفلي الأوسط.

### POS_BOTTOM_RIGHT {#POS_BOTTOM_RIGHT}
```
static final int POS_BOTTOM_RIGHT
```

الموضع السفلي الأيمن.

### POS_SIDES_LEFT {#POS_SIDES_LEFT}
```
static final int POS_SIDES_LEFT
```

الموضع الأيسر.

### POS_SIDES_RIGHT {#POS_SIDES_RIGHT}
```
static final int POS_SIDES_RIGHT
```

الموضع الأيمن.

### POS_UPPER_LEFT {#POS_UPPER_LEFT}
```
static final int POS_UPPER_LEFT
```

الموضع العلوي الأيسر.

### POS_UPPER_MIDDLE {#POS_UPPER_MIDDLE}
```
static final int POS_UPPER_MIDDLE
```

الموضع العلوي الأوسط.

### POS_UPPER_RIGHT {#POS_UPPER_RIGHT}
```
static final int POS_UPPER_RIGHT
```

الموضع العلوي الأيمن.

### addFooter {#addFooter-com.aspose.pdf.facades.FormattedText-float-}
يضيف تذييلًا إلى صفحات المستند.

### addFooter {#addFooter-com.aspose.pdf.facades.FormattedText-float-float-float-}
يضيف تذييلًا إلى صفحات المستند.

### addFooter {#addFooter-java.io.InputStream-float-}
يضيف صورة ك تذييل للصفحة.

### addFooter {#addFooter-java.io.InputStream-float-float-float-}
يضيف صورة ك تذييل للصفحة.

### addFooter {#addFooter-java.lang.String-float-}
يضيف صورة ك تذييل إلى صفحات المستند.

### addFooter {#addFooter-java.lang.String-float-float-float-}
يضيف صورة ك تذييل للصفحات.

### addHeader {#addHeader-com.aspose.pdf.facades.FormattedText-float-}
يضيف رأسًا للصفحة.

### addHeader {#addHeader-com.aspose.pdf.facades.FormattedText-float-float-float-}
يضيف رأسًا إلى صفحات الملف.

### addHeader {#addHeader-java.io.InputStream-float-}
يضيف صورة ك رأس على الصفحات.

### addHeader {#addHeader-java.io.InputStream-float-float-float-}
يضيف صورة في أعلى الصفحة.

### addHeader {#addHeader-java.lang.String-float-}
يضيف صورة ك رأس إلى صفحات الملف.

### addHeader {#addHeader-java.lang.String-float-float-float-}
يضيف صورة ك رأس على الصفحات.

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-}
يضيف رقم الصفحة إلى الصفحة.

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-float-float-}
يضيف رقم الصفحة في الموضع المحدد على الصفحة.

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-int-}
يضيف رقم الصفحة إلى الصفحات.

### addPageNumber {#addPageNumber-com.aspose.pdf.facades.FormattedText-int-float-float-float-float-}
يضيف رقم الصفحة إلى صفحات المستند.

### addPageNumber {#addPageNumber-java.lang.String-}
أضف رقم الصفحة إلى الملف.

### addPageNumber {#addPageNumber-java.lang.String-float-float-}
يضيف رقم الصفحة في الموضع المحدد على الصفحة.

### addPageNumber {#addPageNumber-java.lang.String-int-}
يضيف رقم الصفحة إلى الصفحات.

### addPageNumber {#addPageNumber-java.lang.String-int-float-float-float-float-}
يضيف رقم الصفحة إلى صفحات المستند.

### addStamp {#addStamp-com.aspose.pdf.facades.Stamp-}
يضيف ختمًا إلى الملف.

### close {#close--}
```
void close()
```

يغلق الملفات المفتوحة ويحفظ التغييرات.

### dispose {#dispose--}
```
@Deprecated void dispose()
```

مهمل.

### getAttachmentName {#getAttachmentName--}
```
String getAttachmentName()
```

يحصل على اسم المرفق عندما يتم تخزين نتيجة العملية في كائنات HttpResponse كمرفق.

**Returns:**
قيمة سلسلة

### getContentDisposition {#getContentDisposition--}
```
ContentDisposition getContentDisposition()
```

يحصل على كيفية تخزين المحتوى عندما يتم تخزين نتيجة العملية في كائن HttpResponse.

**Returns:**
عنصر ContentDisposition

### getDocument {#getDocument--}
```
IDocument getDocument()
```

يحصل على المستند الذي يعمل عليه PdfFileStamp.

**Returns:**
كائن IDocument

### getInputFile {#getInputFile--}
```
String getInputFile()
```

يحصل على اسم ومسار ملف الإدخال.

**Returns:**
كائن String

### getInputStream {#getInputStream--}
```
InputStream getInputStream()
```

يحصل على تدفق الإدخال.

**Returns:**
كائن InputStream

### getKeepSecurity {#getKeepSecurity--}
```
boolean getKeepSecurity()
```

يحافظ على الأمان إذا كان صحيحًا.

**Returns:**
قيمة منطقية

### getOutputFile {#getOutputFile--}
```
String getOutputFile()
```

يحصل على اسم ومسار ملف الإخراج.

**Returns:**
كائن String

### getOutputStream {#getOutputStream--}
```
OutputStream getOutputStream()
```

يحصل على تدفق الإخراج.

**Returns:**
كائن OutputStream

### getPageHeight {#getPageHeight--}
```
float getPageHeight()
```

يحصل على ارتفاع الصفحة الأولى في ملف المصدر.

**Returns:**
قيمة عائمة

### getPageNumberRotation {#getPageNumberRotation--}
```
float getPageNumberRotation()
```

يحصل على دوران رقم الصفحة.

**Returns:**
قيمة عائمة

### getPageWidth {#getPageWidth--}
```
float getPageWidth()
```

يحصل على عرض الصفحة الأولى في ملف الإدخال.

**Returns:**
قيمة عائمة

### getSaveOptions {#getSaveOptions--}
```
SaveOptions getSaveOptions()
```

يحصل على خيارات الحفظ عندما يتم تخزين النتيجة كـ HttpResponse.

**Returns:**
كائن SaveOptions

### getStartingNumber {#getStartingNumber--}
```
int getStartingNumber()
```

يحصل أو يضبط الرقم الابتدائي للصفحة الأولى في ملف الإدخال.

**Returns:**
قيمة int

### setAttachmentName {#setAttachmentName-java.lang.String-}
يضبط اسم المرفق عندما يتم تخزين نتيجة العملية في كائنات HttpResponse كمرفق.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
يضبط كيفية تخزين المحتوى عندما يتم تخزين نتيجة العملية في كائن HttpResponse.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
يضبط تنسيق ملف PDF.

### setInputFile {#setInputFile-java.lang.String-}
يضبط اسم ومسار ملف الإدخال.

### setInputStream {#setInputStream-java.io.InputStream-}
يضبط تدفق الإدخال.

### setKeepSecurity {#setKeepSecurity-boolean-}
```
void setKeepSecurity(boolean value)
```

ضبط الحفاظ على الأمان

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة منطقية |

### setOutputFile {#setOutputFile-java.lang.String-}
يضبط اسم ومسار ملف الإخراج.

### setOutputStream {#setOutputStream-java.io.OutputStream-}
يضبط أو يضبط تدفق الإخراج.

### setPageNumberRotation {#setPageNumberRotation-float-}
```
void setPageNumberRotation(float value)
```

يضبط دوران رقم الصفحة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة عائمة |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
يضبط خيارات الحفظ عندما يتم تخزين النتيجة كـ HttpResponse.

### setStartingNumber {#setStartingNumber-int-}
```
void setStartingNumber(int value)
```

يضبط الرقم الابتدائي للصفحة الأولى في ملف الإدخال.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| قيمة |  | قيمة int |
