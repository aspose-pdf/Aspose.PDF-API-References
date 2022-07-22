---
title: Convert
second_title: Aspose.PDF لمرجع .NET API
description: يحول الملف المصدر بتنسيق المصدر إلى ملف الوجهة بتنسيق الوجهة.
type: docs
weight: 790
url: /ar/net/aspose.pdf/document/convert/
---
## Convert(string, LoadOptions, string, SaveOptions) {#convert_3}

يحول الملف المصدر بتنسيق المصدر إلى ملف الوجهة بتنسيق الوجهة.

```csharp
public static void Convert(string srcFileName, LoadOptions loadOptions, string dstFileName, 
    SaveOptions saveOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| srcFileName | String | اسم الملف المصدر. |
| loadOptions | LoadOptions | تنسيق الملف المصدر. |
| dstFileName | String | اسم ملف الوجهة. |
| saveOptions | SaveOptions | تنسيق الملف الوجهة. |

### أنظر أيضا

* class [LoadOptions](../../loadoptions)
* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* مساحة الاسم [Aspose.Pdf](../../document)
* المجسم [Aspose.PDF](../../../)

---

## Convert(Stream, LoadOptions, string, SaveOptions) {#convert_1}

يحول الدفق بتنسيق المصدر إلى ملف الوجهة بتنسيق الوجهة.

```csharp
public static void Convert(Stream srcStream, LoadOptions loadOptions, string dstFileName, 
    SaveOptions saveOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| srcStream | Stream | تيار المصدر. |
| loadOptions | LoadOptions | تنسيق تدفق المصدر. |
| dstFileName | String | اسم ملف الوجهة. |
| saveOptions | SaveOptions | تنسيق الملف الوجهة. |

### أنظر أيضا

* class [LoadOptions](../../loadoptions)
* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* مساحة الاسم [Aspose.Pdf](../../document)
* المجسم [Aspose.PDF](../../../)

---

## Convert(string, LoadOptions, Stream, SaveOptions) {#convert_2}

يحول الملف المصدر بتنسيق المصدر إلى دفق بتنسيق الوجهة.

```csharp
public static void Convert(string srcFileName, LoadOptions loadOptions, Stream dstStream, 
    SaveOptions saveOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| srcFileName | String | اسم الملف المصدر. |
| loadOptions | LoadOptions | تنسيق الملف المصدر. |
| dstStream | Stream | تيار الوجهة. |
| saveOptions | SaveOptions | تنسيق تيار الوجهة. |

### أنظر أيضا

* class [LoadOptions](../../loadoptions)
* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* مساحة الاسم [Aspose.Pdf](../../document)
* المجسم [Aspose.PDF](../../../)

---

## Convert(Stream, LoadOptions, Stream, SaveOptions) {#convert}

يحول الدفق بتنسيق المصدر إلى دفق بتنسيق الوجهة.

```csharp
public static void Convert(Stream srcStream, LoadOptions loadOptions, Stream dstStream, 
    SaveOptions saveOptions)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| srcStream | Stream | تيار المصدر. |
| loadOptions | LoadOptions | تنسيق تدفق المصدر. |
| dstStream | Stream | تيار الوجهة. |
| saveOptions | SaveOptions | تنسيق الملف الوجهة. |

### أنظر أيضا

* class [LoadOptions](../../loadoptions)
* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* مساحة الاسم [Aspose.Pdf](../../document)
* المجسم [Aspose.PDF](../../../)

---

## Convert(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) {#convert_7}

قم بتحويل المستند وحفظ الأخطاء في الملف المحدد.

```csharp
public bool Convert(string outputLogFileName, PdfFormat format, ConvertErrorAction action, 
    ConvertTransparencyAction transparencyAction)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| outputLogFileName | String | مسار الملف حيث سيتم تخزين التعليقات. |
| format | PdfFormat | تنسيق pdf. |
| action | ConvertErrorAction | الإجراء الخاص بالكائنات التي لا يمكن تحويلها |
| transparencyAction | ConvertTransparencyAction | الإجراء الخاص بصور الكائنات المقنعة |

### قيمة الإرجاع

نتيجة العملية

### أنظر أيضا

* enum [PdfFormat](../../pdfformat)
* enum [ConvertErrorAction](../../converterroraction)
* enum [ConvertTransparencyAction](../../converttransparencyaction)
* class [Document](../../document)
* مساحة الاسم [Aspose.Pdf](../../document)
* المجسم [Aspose.PDF](../../../)

---

## Convert(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) {#convert_5}

قم بتحويل المستند وحفظ الأخطاء في الملف المحدد.

```csharp
public bool Convert(Stream outputLogStream, PdfFormat format, ConvertErrorAction action, 
    ConvertTransparencyAction transparencyAction)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| outputLogStream | Stream | تيار حيث سيتم تخزين التعليقات. |
| format | PdfFormat | تنسيق pdf. |
| action | ConvertErrorAction | الإجراء الخاص بالكائنات التي لا يمكن تحويلها |
| transparencyAction | ConvertTransparencyAction | الإجراء الخاص بصور الكائنات المقنعة |

### قيمة الإرجاع

نتيجة العملية

### أنظر أيضا

* enum [PdfFormat](../../pdfformat)
* enum [ConvertErrorAction](../../converterroraction)
* enum [ConvertTransparencyAction](../../converttransparencyaction)
* class [Document](../../document)
* مساحة الاسم [Aspose.Pdf](../../document)
* المجسم [Aspose.PDF](../../../)

---

## Convert(string, PdfFormat, ConvertErrorAction) {#convert_6}

قم بتحويل المستند وحفظ الأخطاء في الملف المحدد.

```csharp
public bool Convert(string outputLogFileName, PdfFormat format, ConvertErrorAction action)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| outputLogFileName | String | مسار الملف حيث سيتم تخزين التعليقات. |
| format | PdfFormat | تنسيق pdf. |
| action | ConvertErrorAction | الإجراء الخاص بالكائنات التي لا يمكن تحويلها |

### قيمة الإرجاع

نتيجة العملية

### أنظر أيضا

* enum [PdfFormat](../../pdfformat)
* enum [ConvertErrorAction](../../converterroraction)
* class [Document](../../document)
* مساحة الاسم [Aspose.Pdf](../../document)
* المجسم [Aspose.PDF](../../../)

---

## Convert(PdfFormatConversionOptions) {#convert_2}

تحويل المستند باستخدام خيارات التحويل المحددة

```csharp
public bool Convert(PdfFormatConversionOptions options)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| options | PdfFormatConversionOptions | مجموعة من الخيارات لتحويل وثيقة PDF |

### قيمة الإرجاع

نتيجة العملية

### أنظر أيضا

* class [PdfFormatConversionOptions](../../pdfformatconversionoptions)
* class [Document](../../document)
* مساحة الاسم [Aspose.Pdf](../../document)
* المجسم [Aspose.PDF](../../../)

---

## Convert(CallBackGetHocr) {#convert_3}

قم بتحويل المستند وحفظ الأخطاء في الملف المحدد.

```csharp
public bool Convert(CallBackGetHocr callback)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| callback | CallBackGetHocr | الإجراء الخاص بالكائنات التي لا يمكن تحويلها |

### قيمة الإرجاع

نتيجة العملية

### أنظر أيضا

* delegate [CallBackGetHocr](../../document.callbackgethocr)
* class [Document](../../document)
* مساحة الاسم [Aspose.Pdf](../../document)
* المجسم [Aspose.PDF](../../../)

---

## Convert(Stream, PdfFormat, ConvertErrorAction) {#convert_4}

قم بتحويل المستند وحفظ الأخطاء في الدفق المحدد.

```csharp
public bool Convert(Stream outputLogStream, PdfFormat format, ConvertErrorAction action)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| outputLogStream | Stream | تيار حيث سيتم تخزين التعليقات. |
| format | PdfFormat | تنسيق PDF. |
| action | ConvertErrorAction | الإجراء الخاص بالكائنات التي لا يمكن تحويلها |

### قيمة الإرجاع

نتيجة العملية

### أنظر أيضا

* enum [PdfFormat](../../pdfformat)
* enum [ConvertErrorAction](../../converterroraction)
* class [Document](../../document)
* مساحة الاسم [Aspose.Pdf](../../document)
* المجسم [Aspose.PDF](../../../)

---

## Convert(Fixup, Stream, bool, object[]) {#convert}

تحويل المستند عن طريق تطبيق Fixup .

```csharp
public bool Convert(Fixup fixup, Stream outputLog, bool onlyValidation = false, 
    object[] parameters = null)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| fixup | Fixup | نوع الإصلاح. |
| outputLog | Stream | سجل العملية. |
| onlyValidation | Boolean | التحقق من صحة الوثيقة فقط. |
| parameters | Object[] | خصائص الإصلاح التي لا يمكن تعيينها. |

### قيمة الإرجاع

نتيجة العملية.

### أنظر أيضا

* enum [Fixup](../../fixup)
* class [Document](../../document)
* مساحة الاسم [Aspose.Pdf](../../document)
* المجسم [Aspose.PDF](../../../)

---

## Convert(Fixup, string, bool, object[]) {#convert_1}

تحويل المستند عن طريق تطبيق Fixup .

```csharp
public bool Convert(Fixup fixup, string outputLog, bool onlyValidation = false, 
    object[] parameters = null)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| fixup | Fixup | نوع الإصلاح. |
| outputLog | String | سجل العملية. |
| onlyValidation | Boolean | التحقق من صحة الوثيقة فقط. |
| parameters | Object[] | خصائص الإصلاح التي لا يمكن تعيينها. |

### قيمة الإرجاع

نتيجة العملية.

### أنظر أيضا

* enum [Fixup](../../fixup)
* class [Document](../../document)
* مساحة الاسم [Aspose.Pdf](../../document)
* المجسم [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
