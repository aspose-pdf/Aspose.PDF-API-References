---
title: Convert
second_title: Aspose.PDF for .NET API Reference
description: Converts source file in source format into destination file in destination format.
type: docs
weight: 800
url: /net/aspose.pdf/document/convert/
---
## Convert(string, LoadOptions, string, SaveOptions) {#convert_3}

Converts source file in source format into destination file in destination format.

```csharp
public static void Convert(string srcFileName, LoadOptions loadOptions, string dstFileName, 
    SaveOptions saveOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| srcFileName | String | The source file name. |
| loadOptions | LoadOptions | The source file format. |
| dstFileName | String | The destination file name. |
| saveOptions | SaveOptions | The destination file format. |

### See Also

* class [LoadOptions](../../loadoptions)
* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* namespace [Aspose.Pdf](../../document)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, LoadOptions, string, SaveOptions) {#convert_1}

Converts stream in source format into destination file in destination format.

```csharp
public static void Convert(Stream srcStream, LoadOptions loadOptions, string dstFileName, 
    SaveOptions saveOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| srcStream | Stream | The source stream. |
| loadOptions | LoadOptions | The source stream format. |
| dstFileName | String | The destination file name. |
| saveOptions | SaveOptions | The destination file format. |

### See Also

* class [LoadOptions](../../loadoptions)
* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* namespace [Aspose.Pdf](../../document)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, LoadOptions, Stream, SaveOptions) {#convert_2}

Converts source file in source format into stream in destination format.

```csharp
public static void Convert(string srcFileName, LoadOptions loadOptions, Stream dstStream, 
    SaveOptions saveOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| srcFileName | String | The source file name. |
| loadOptions | LoadOptions | The source file format. |
| dstStream | Stream | The destination stream. |
| saveOptions | SaveOptions | The destination stream format. |

### See Also

* class [LoadOptions](../../loadoptions)
* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* namespace [Aspose.Pdf](../../document)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, LoadOptions, Stream, SaveOptions) {#convert}

Converts stream in source format into stream in destination format.

```csharp
public static void Convert(Stream srcStream, LoadOptions loadOptions, Stream dstStream, 
    SaveOptions saveOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| srcStream | Stream | The source stream. |
| loadOptions | LoadOptions | The source stream format. |
| dstStream | Stream | The destination stream. |
| saveOptions | SaveOptions | The destination file format. |

### See Also

* class [LoadOptions](../../loadoptions)
* class [SaveOptions](../../saveoptions)
* class [Document](../../document)
* namespace [Aspose.Pdf](../../document)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) {#convert_7}

Convert document and save errors into the specified file.

```csharp
public bool Convert(string outputLogFileName, PdfFormat format, ConvertErrorAction action, 
    ConvertTransparencyAction transparencyAction)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputLogFileName | String | Path to file where the comments will be stored. |
| format | PdfFormat | The pdf format. |
| action | ConvertErrorAction | Action for objects that can not be converted |
| transparencyAction | ConvertTransparencyAction | Action for image masked objects |

### Return Value

The operation result

### See Also

* enum [PdfFormat](../../pdfformat)
* enum [ConvertErrorAction](../../converterroraction)
* enum [ConvertTransparencyAction](../../converttransparencyaction)
* class [Document](../../document)
* namespace [Aspose.Pdf](../../document)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) {#convert_5}

Convert document and save errors into the specified file.

```csharp
public bool Convert(Stream outputLogStream, PdfFormat format, ConvertErrorAction action, 
    ConvertTransparencyAction transparencyAction)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputLogStream | Stream | Stream where the comments will be stored. |
| format | PdfFormat | The pdf format. |
| action | ConvertErrorAction | Action for objects that can not be converted |
| transparencyAction | ConvertTransparencyAction | Action for image masked objects |

### Return Value

The operation result

### See Also

* enum [PdfFormat](../../pdfformat)
* enum [ConvertErrorAction](../../converterroraction)
* enum [ConvertTransparencyAction](../../converttransparencyaction)
* class [Document](../../document)
* namespace [Aspose.Pdf](../../document)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, PdfFormat, ConvertErrorAction) {#convert_6}

Convert document and save errors into the specified file.

```csharp
public bool Convert(string outputLogFileName, PdfFormat format, ConvertErrorAction action)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputLogFileName | String | Path to file where the comments will be stored. |
| format | PdfFormat | The pdf format. |
| action | ConvertErrorAction | Action for objects that can not be converted |

### Return Value

The operation result

### See Also

* enum [PdfFormat](../../pdfformat)
* enum [ConvertErrorAction](../../converterroraction)
* class [Document](../../document)
* namespace [Aspose.Pdf](../../document)
* assembly [Aspose.PDF](../../../)

---

## Convert(PdfFormatConversionOptions) {#convert_2}

Convert document using specified conversion options

```csharp
public bool Convert(PdfFormatConversionOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| options | PdfFormatConversionOptions | set of options for convert PDF document |

### Return Value

The operation result

### See Also

* class [PdfFormatConversionOptions](../../pdfformatconversionoptions)
* class [Document](../../document)
* namespace [Aspose.Pdf](../../document)
* assembly [Aspose.PDF](../../../)

---

## Convert(CallBackGetHocr) {#convert_3}

Convert document and save errors into the specified file.

```csharp
public bool Convert(CallBackGetHocr callback)
```

| Parameter | Type | Description |
| --- | --- | --- |
| callback | CallBackGetHocr | Action for objects that can not be converted |

### Return Value

The operation result

### See Also

* delegate [CallBackGetHocr](../../document.callbackgethocr)
* class [Document](../../document)
* namespace [Aspose.Pdf](../../document)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, PdfFormat, ConvertErrorAction) {#convert_4}

Convert document and save errors into the specified stream.

```csharp
public bool Convert(Stream outputLogStream, PdfFormat format, ConvertErrorAction action)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputLogStream | Stream | Stream where the comments will be stored. |
| format | PdfFormat | Pdf format. |
| action | ConvertErrorAction | Action for objects that can not be converted |

### Return Value

The operation result

### See Also

* enum [PdfFormat](../../pdfformat)
* enum [ConvertErrorAction](../../converterroraction)
* class [Document](../../document)
* namespace [Aspose.Pdf](../../document)
* assembly [Aspose.PDF](../../../)

---

## Convert(Fixup, Stream, bool, object[]) {#convert}

Convert document by applying the Fixup.

```csharp
public bool Convert(Fixup fixup, Stream outputLog, bool onlyValidation = false, 
    object[] parameters = null)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fixup | Fixup | The Fixup type. |
| outputLog | Stream | The log of process. |
| onlyValidation | Boolean | Only document validation. |
| parameters | Object[] | Properties for Fixup that can not be set. |

### Return Value

The operation result.

### See Also

* enum [Fixup](../../fixup)
* class [Document](../../document)
* namespace [Aspose.Pdf](../../document)
* assembly [Aspose.PDF](../../../)

---

## Convert(Fixup, string, bool, object[]) {#convert_1}

Convert document by applying the Fixup.

```csharp
public bool Convert(Fixup fixup, string outputLog, bool onlyValidation = false, 
    object[] parameters = null)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fixup | Fixup | The Fixup type. |
| outputLog | String | The log of process. |
| onlyValidation | Boolean | Only document validation. |
| parameters | Object[] | Properties for Fixup that can not be set. |

### Return Value

The operation result.

### See Also

* enum [Fixup](../../fixup)
* class [Document](../../document)
* namespace [Aspose.Pdf](../../document)
* assembly [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
