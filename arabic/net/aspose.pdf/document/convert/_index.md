---
title: "Document.Convert"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة Document. تحويل المستند وحفظ الأخطاء في الملف المحدد"
type: docs
weight: 600
url: /ar/net/aspose.pdf/document/convert/
---
## Convert(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) {#convert_8}

تحويل المستند وحفظ الأخطاء في الملف المحدد.

```csharp
public bool Convert(string outputLogFileName, PdfFormat format, ConvertErrorAction action, 
    ConvertTransparencyAction transparencyAction)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputLogFileName | String | المسار إلى الملف حيث سيتم تخزين التعليقات. |
| format | PdfFormat | تنسيق pdf. |
| إجراء | ConvertErrorAction | الإجراء للكائنات التي لا يمكن تحويلها |
| transparencyAction | ConvertTransparencyAction | إجراء للكائنات ذات القناع الصوري |

### قيمة الإرجاع

نتيجة العملية

### انظر أيضًا

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* enum [ConvertTransparencyAction](../../converttransparencyaction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) {#convert_6}

تحويل المستند وحفظ الأخطاء في الملف المحدد.

```csharp
public bool Convert(Stream outputLogStream, PdfFormat format, ConvertErrorAction action, 
    ConvertTransparencyAction transparencyAction)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputLogStream | Stream | المجري حيث سيتم تخزين التعليقات. |
| format | PdfFormat | تنسيق pdf. |
| إجراء | ConvertErrorAction | الإجراء للكائنات التي لا يمكن تحويلها |
| transparencyAction | ConvertTransparencyAction | إجراء للكائنات ذات القناع الصوري |

### قيمة الإرجاع

نتيجة العملية

### انظر أيضًا

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* enum [ConvertTransparencyAction](../../converttransparencyaction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, PdfFormat, ConvertErrorAction) {#convert_7}

تحويل المستند وحفظ الأخطاء في الملف المحدد.

```csharp
public bool Convert(string outputLogFileName, PdfFormat format, ConvertErrorAction action)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputLogFileName | String | المسار إلى الملف حيث سيتم تخزين التعليقات. |
| format | PdfFormat | تنسيق pdf. |
| إجراء | ConvertErrorAction | الإجراء للكائنات التي لا يمكن تحويلها |

### قيمة الإرجاع

نتيجة العملية

### انظر أيضًا

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(PdfFormatConversionOptions) {#convert_2}

تحويل المستند باستخدام خيارات التحويل المحددة

```csharp
public bool Convert(PdfFormatConversionOptions options)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| options | PdfFormatConversionOptions | مجموعة من الخيارات لتحويل مستند PDF |

### قيمة الإرجاع

نتيجة العملية

### انظر أيضًا

* class [PdfFormatConversionOptions](../../pdfformatconversionoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(CallBackGetHocrWithPage, bool) {#convert_4}

التعرف على الصور داخل المستند وإضافة سلاسل hocr فوقها.

```csharp
public bool Convert(CallBackGetHocrWithPage callback, bool flattenImages = false)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| callback | CallBackGetHocrWithPage | إجراء للصور التي سيتم معالجتها بواسطة التعرف على hocr. |
| flattenImages | Boolean | يمكن رسم النص في صور pdf باستخدام آلية الأقنعة، وفي هذه الحالة يجب تسوية الصور. |

### قيمة الإرجاع

نتيجة العملية. إذا لم يكن هناك صور في المستند تُرجع !:false.

### انظر أيضًا

* delegate [CallBackGetHocrWithPage](../../document.callbackgethocrwithpage/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(CallBackGetHocr, bool) {#convert_3}

التعرف على الصور داخل المستند وإضافة سلاسل hocr فوقها.

```csharp
public bool Convert(CallBackGetHocr callback, bool flattenImages = false)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| callback | CallBackGetHocr | إجراء للصور التي سيتم معالجتها بواسطة التعرف على hocr. |
| flattenImages | Boolean | يمكن رسم النص في صور pdf باستخدام آلية الأقنعة، وفي هذه الحالة يجب تسوية الصور. |

### قيمة الإرجاع

نتيجة العملية. إذا لم يكن هناك صور في المستند تُرجع !:false.

### انظر أيضًا

* delegate [CallBackGetHocr](../../document.callbackgethocr/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, PdfFormat, ConvertErrorAction) {#convert_5}

تحويل المستند وحفظ الأخطاء في الدفق المحدد.

```csharp
public bool Convert(Stream outputLogStream, PdfFormat format, ConvertErrorAction action)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputLogStream | Stream | المجري حيث سيتم تخزين التعليقات. |
| format | PdfFormat | تنسيق Pdf. |
| إجراء | ConvertErrorAction | الإجراء للكائنات التي لا يمكن تحويلها |

### قيمة الإرجاع

نتيجة العملية

### انظر أيضًا

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Fixup, Stream, bool, object[]) {#convert}

تحويل المستند بتطبيق الـ Fixup.

```csharp
public bool Convert(Fixup fixup, Stream outputLog, bool onlyValidation = false, 
    object[] parameters = null)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fixup | Fixup | نوع Fixup. |
| outputLog | Stream | سجل العملية. |
| onlyValidation | Boolean | التحقق من المستند فقط. |
| معلمات | Object[] | الخصائص الخاصة بـ Fixup التي لا يمكن تعيينها. |

### قيمة الإرجاع

نتيجة العملية.

### انظر أيضًا

* enum [Fixup](../../fixup/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Fixup, string, bool, object[]) {#convert_1}

تحويل المستند بتطبيق الـ Fixup.

```csharp
public bool Convert(Fixup fixup, string outputLog, bool onlyValidation = false, 
    object[] parameters = null)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fixup | Fixup | نوع Fixup. |
| outputLog | String | سجل العملية. |
| onlyValidation | Boolean | التحقق من المستند فقط. |
| معلمات | Object[] | الخصائص الخاصة بـ Fixup التي لا يمكن تعيينها. |

### قيمة الإرجاع

نتيجة العملية.

### انظر أيضًا

* enum [Fixup](../../fixup/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, LoadOptions, string, SaveOptions) {#convert_3}

يقوم بتحويل ملف المصدر بصيغته المصدر إلى ملف الوجهة بصيغته الوجهة.

```csharp
public static void Convert(string srcFileName, LoadOptions loadOptions, string dstFileName, 
    SaveOptions saveOptions)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| srcFileName | String | اسم ملف المصدر. |
| loadOptions | LoadOptions | تنسيق ملف المصدر. |
| dstFileName | String | اسم ملف الوجهة. |
| saveOptions | SaveOptions | تنسيق ملف الوجهة. |

### انظر أيضًا

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, LoadOptions, string, SaveOptions) {#convert_1}

يحوّل التدفق من الصيغة المصدر إلى ملف الوجهة بالصِيغة الوجهة.

```csharp
public static void Convert(Stream srcStream, LoadOptions loadOptions, string dstFileName, 
    SaveOptions saveOptions)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| srcStream | Stream | دفق المصدر. |
| loadOptions | LoadOptions | تنسيق دفق المصدر. |
| dstFileName | String | اسم ملف الوجهة. |
| saveOptions | SaveOptions | تنسيق ملف الوجهة. |

### انظر أيضًا

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, LoadOptions, Stream, SaveOptions) {#convert_2}

يحوّل الملف المصدر من الصيغة المصدر إلى تدفق بالصِيغة الوجهة.

```csharp
public static void Convert(string srcFileName, LoadOptions loadOptions, Stream dstStream, 
    SaveOptions saveOptions)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| srcFileName | String | اسم ملف المصدر. |
| loadOptions | LoadOptions | تنسيق ملف المصدر. |
| dstStream | Stream | دفق الوجهة. |
| saveOptions | SaveOptions | تنسيق دفق الوجهة. |

### انظر أيضًا

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, LoadOptions, Stream, SaveOptions) {#convert}

يحوّل التدفق من الصيغة المصدر إلى تدفق بالصِيغة الوجهة.

```csharp
public static void Convert(Stream srcStream, LoadOptions loadOptions, Stream dstStream, 
    SaveOptions saveOptions)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| srcStream | Stream | دفق المصدر. |
| loadOptions | LoadOptions | تنسيق دفق المصدر. |
| dstStream | Stream | دفق الوجهة. |
| saveOptions | SaveOptions | تنسيق ملف الوجهة. |

### انظر أيضًا

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


