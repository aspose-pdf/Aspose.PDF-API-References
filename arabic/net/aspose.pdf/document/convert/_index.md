---
title: Document.Convert
second_title: Aspose.PDF for .NET API Reference
description: طريقة الوثيقة. تحويل الوثيقة وحفظ الأخطاء في الملف المحدد
type: docs
weight: 580
url: /ar/net/aspose.pdf/document/convert/
---
## Convert(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) {#convert_8}

تحويل الوثيقة وحفظ الأخطاء في الملف المحدد.

```csharp
public bool Convert(string outputLogFileName, PdfFormat format, ConvertErrorAction action, 
    ConvertTransparencyAction transparencyAction)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputLogFileName | String | مسار الملف حيث سيتم تخزين التعليقات. |
| format | PdfFormat | تنسيق PDF. |
| action | ConvertErrorAction | الإجراء للأشياء التي لا يمكن تحويلها |
| transparencyAction | ConvertTransparencyAction | الإجراء للأشياء المmasked بالصور |

### Return Value

نتيجة العملية

### See Also

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* enum [ConvertTransparencyAction](../../converttransparencyaction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) {#convert_6}

تحويل الوثيقة وحفظ الأخطاء في الملف المحدد.

```csharp
public bool Convert(Stream outputLogStream, PdfFormat format, ConvertErrorAction action, 
    ConvertTransparencyAction transparencyAction)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputLogStream | Stream | التدفق حيث سيتم تخزين التعليقات. |
| format | PdfFormat | تنسيق PDF. |
| action | ConvertErrorAction | الإجراء للأشياء التي لا يمكن تحويلها |
| transparencyAction | ConvertTransparencyAction | الإجراء للأشياء المmasked بالصور |

### Return Value

نتيجة العملية

### See Also

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* enum [ConvertTransparencyAction](../../converttransparencyaction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, PdfFormat, ConvertErrorAction) {#convert_7}

تحويل الوثيقة وحفظ الأخطاء في الملف المحدد.

```csharp
public bool Convert(string outputLogFileName, PdfFormat format, ConvertErrorAction action)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputLogFileName | String | مسار الملف حيث سيتم تخزين التعليقات. |
| format | PdfFormat | تنسيق PDF. |
| action | ConvertErrorAction | الإجراء للأشياء التي لا يمكن تحويلها |

### Return Value

نتيجة العملية

### See Also

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(PdfFormatConversionOptions) {#convert_2}

تحويل الوثيقة باستخدام خيارات التحويل المحددة

```csharp
public bool Convert(PdfFormatConversionOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| options | PdfFormatConversionOptions | مجموعة من الخيارات لتحويل وثيقة PDF |

### Return Value

نتيجة العملية

### See Also

* class [PdfFormatConversionOptions](../../pdfformatconversionoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(CallBackGetHocrWithPage, bool) {#convert_4}

التعرف على الصور داخل الوثيقة وإضافة سلاسل hocr فوقها.

```csharp
public bool Convert(CallBackGetHocrWithPage callback, bool flattenImages = false)
```

| Parameter | Type | Description |
| --- | --- | --- |
| callback | CallBackGetHocrWithPage | الإجراء للصور التي سيتم معالجتها بواسطة التعرف على hocr. |
| flattenImages | Boolean | يمكن رسم النص في صور PDF باستخدام آلية الأقنعة، وفي هذه الحالة يجب تسطيح الصور. |

### Return Value

نتيجة العملية. إذا لم تكن هناك صور في الوثيقة، فإنها تعيد !:false.

### See Also

* delegate [CallBackGetHocrWithPage](../../document.callbackgethocrwithpage/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(CallBackGetHocr, bool) {#convert_3}

التعرف على الصور داخل الوثيقة وإضافة سلاسل hocr فوقها.

```csharp
public bool Convert(CallBackGetHocr callback, bool flattenImages = false)
```

| Parameter | Type | Description |
| --- | --- | --- |
| callback | CallBackGetHocr | الإجراء للصور التي سيتم معالجتها بواسطة التعرف على hocr. |
| flattenImages | Boolean | يمكن رسم النص في صور PDF باستخدام آلية الأقنعة، وفي هذه الحالة يجب تسطيح الصور. |

### Return Value

نتيجة العملية. إذا لم تكن هناك صور في الوثيقة، فإنها تعيد !:false.

### See Also

* delegate [CallBackGetHocr](../../document.callbackgethocr/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, PdfFormat, ConvertErrorAction) {#convert_5}

تحويل الوثيقة وحفظ الأخطاء في التدفق المحدد.

```csharp
public bool Convert(Stream outputLogStream, PdfFormat format, ConvertErrorAction action)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputLogStream | Stream | التدفق حيث سيتم تخزين التعليقات. |
| format | PdfFormat | تنسيق PDF. |
| action | ConvertErrorAction | الإجراء للأشياء التي لا يمكن تحويلها |

### Return Value

نتيجة العملية

### See Also

* enum [PdfFormat](../../pdfformat/)
* enum [ConvertErrorAction](../../converterroraction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Fixup, Stream, bool, object[]) {#convert}

تحويل الوثيقة عن طريق تطبيق Fixup.

```csharp
public bool Convert(Fixup fixup, Stream outputLog, bool onlyValidation = false, 
    object[] parameters = null)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fixup | Fixup | نوع Fixup. |
| outputLog | Stream | سجل العملية. |
| onlyValidation | Boolean | فقط تحقق من الوثيقة. |
| parameters | Object[] | خصائص لـ Fixup التي لا يمكن تعيينها. |

### Return Value

نتيجة العملية.

### See Also

* enum [Fixup](../../fixup/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Fixup, string, bool, object[]) {#convert_1}

تحويل الوثيقة عن طريق تطبيق Fixup.

```csharp
public bool Convert(Fixup fixup, string outputLog, bool onlyValidation = false, 
    object[] parameters = null)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fixup | Fixup | نوع Fixup. |
| outputLog | String | سجل العملية. |
| onlyValidation | Boolean | فقط تحقق من الوثيقة. |
| parameters | Object[] | خصائص لـ Fixup التي لا يمكن تعيينها. |

### Return Value

نتيجة العملية.

### See Also

* enum [Fixup](../../fixup/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, LoadOptions, string, SaveOptions) {#convert_3}

تحويل ملف المصدر في التنسيق المصدر إلى ملف الوجهة في التنسيق الوجهة.

```csharp
public static void Convert(string srcFileName, LoadOptions loadOptions, string dstFileName, 
    SaveOptions saveOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| srcFileName | String | اسم ملف المصدر. |
| loadOptions | LoadOptions | تنسيق ملف المصدر. |
| dstFileName | String | اسم ملف الوجهة. |
| saveOptions | SaveOptions | تنسيق ملف الوجهة. |

### See Also

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, LoadOptions, string, SaveOptions) {#convert_1}

تحويل التدفق في التنسيق المصدر إلى ملف الوجهة في التنسيق الوجهة.

```csharp
public static void Convert(Stream srcStream, LoadOptions loadOptions, string dstFileName, 
    SaveOptions saveOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| srcStream | Stream | التدفق المصدر. |
| loadOptions | LoadOptions | تنسيق التدفق المصدر. |
| dstFileName | String | اسم ملف الوجهة. |
| saveOptions | SaveOptions | تنسيق ملف الوجهة. |

### See Also

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, LoadOptions, Stream, SaveOptions) {#convert_2}

تحويل ملف المصدر في التنسيق المصدر إلى تدفق في التنسيق الوجهة.

```csharp
public static void Convert(string srcFileName, LoadOptions loadOptions, Stream dstStream, 
    SaveOptions saveOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| srcFileName | String | اسم ملف المصدر. |
| loadOptions | LoadOptions | تنسيق ملف المصدر. |
| dstStream | Stream | التدفق الوجهة. |
| saveOptions | SaveOptions | تنسيق التدفق الوجهة. |

### See Also

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, LoadOptions, Stream, SaveOptions) {#convert}

تحويل التدفق في التنسيق المصدر إلى تدفق في التنسيق الوجهة.

```csharp
public static void Convert(Stream srcStream, LoadOptions loadOptions, Stream dstStream, 
    SaveOptions saveOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| srcStream | Stream | التدفق المصدر. |
| loadOptions | LoadOptions | تنسيق التدفق المصدر. |
| dstStream | Stream | التدفق الوجهة. |
| saveOptions | SaveOptions | تنسيق الملف الوجهة. |

### See Also

* class [LoadOptions](../../loadoptions/)
* class [SaveOptions](../../saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)