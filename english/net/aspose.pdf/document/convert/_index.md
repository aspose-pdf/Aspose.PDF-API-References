---
title: "Document.Convert"
linktitle: "Convert"
articleTitle: "Convert"
second_title: "Aspose.PDF for .NET API Reference"
description: "Document method. Convert document and save errors into the specified file."
type: docs
weight: 390
url: "/net/aspose.pdf/document/convert/"
product_version: "26.9.0"
---
## Convert(string, [PdfFormat](../../../aspose.pdf/pdfformat/), [ConvertErrorAction](../../../aspose.pdf/converterroraction/), [ConvertTransparencyAction](../../../aspose.pdf/converttransparencyaction/)) {#convert}

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

* enum [PdfFormat](../../../aspose.pdf/pdfformat/)
* enum [ConvertErrorAction](../../../aspose.pdf/converterroraction/)
* enum [ConvertTransparencyAction](../../../aspose.pdf/converttransparencyaction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, [PdfFormat](../../../aspose.pdf/pdfformat/), [ConvertErrorAction](../../../aspose.pdf/converterroraction/), [ConvertTransparencyAction](../../../aspose.pdf/converttransparencyaction/)) {#convert_1}

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

* enum [PdfFormat](../../../aspose.pdf/pdfformat/)
* enum [ConvertErrorAction](../../../aspose.pdf/converterroraction/)
* enum [ConvertTransparencyAction](../../../aspose.pdf/converttransparencyaction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, [PdfFormat](../../../aspose.pdf/pdfformat/), [ConvertErrorAction](../../../aspose.pdf/converterroraction/)) {#convert_2}

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

* enum [PdfFormat](../../../aspose.pdf/pdfformat/)
* enum [ConvertErrorAction](../../../aspose.pdf/converterroraction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert([PdfFormatConversionOptions](../../../aspose.pdf/pdfformatconversionoptions/)) {#convert_3}

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

* class [PdfFormatConversionOptions](../../../aspose.pdf/pdfformatconversionoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(CallBackGetHocrWithPage, bool) {#convert_4}

Recognize images inside the document and add hocr strings over it.

```csharp
public bool Convert(CallBackGetHocrWithPage callback, bool flattenImages = false)
```

| Parameter | Type | Description |
| --- | --- | --- |
| callback | CallBackGetHocrWithPage | Action for images that will be processed by hocr recognize. |
| flattenImages | Boolean | Text in pdf images can be painted using the mechanics of masks, in which case the images must be flattened. |

### Return Value

The operation result. If there are no images in the document returns `!:false`.

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(CallBackGetHocr, bool) {#convert_5}

Recognize images inside the document and add hocr strings over it.

```csharp
public bool Convert(CallBackGetHocr callback, bool flattenImages = false)
```

| Parameter | Type | Description |
| --- | --- | --- |
| callback | CallBackGetHocr | Action for images that will be processed by hocr recognize. |
| flattenImages | Boolean | Text in pdf images can be painted using the mechanics of masks, in which case the images must be flattened. |

### Return Value

The operation result. If there are no images in the document returns `!:false`.

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, [PdfFormat](../../../aspose.pdf/pdfformat/), [ConvertErrorAction](../../../aspose.pdf/converterroraction/)) {#convert_6}

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

* enum [PdfFormat](../../../aspose.pdf/pdfformat/)
* enum [ConvertErrorAction](../../../aspose.pdf/converterroraction/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert([Fixup](../../../aspose.pdf/fixup/), Stream, bool, object[]) {#convert_7}

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

* enum [Fixup](../../../aspose.pdf/fixup/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert([Fixup](../../../aspose.pdf/fixup/), string, bool, object[]) {#convert_8}

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

* enum [Fixup](../../../aspose.pdf/fixup/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, [LoadOptions](../../../aspose.pdf/loadoptions/), string, [SaveOptions](../../../aspose.pdf/saveoptions/)) {#convert_9}

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

* class [LoadOptions](../../../aspose.pdf/loadoptions/)
* class [SaveOptions](../../../aspose.pdf/saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, [LoadOptions](../../../aspose.pdf/loadoptions/), string, [SaveOptions](../../../aspose.pdf/saveoptions/)) {#convert_10}

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

* class [LoadOptions](../../../aspose.pdf/loadoptions/)
* class [SaveOptions](../../../aspose.pdf/saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, [LoadOptions](../../../aspose.pdf/loadoptions/), Stream, [SaveOptions](../../../aspose.pdf/saveoptions/)) {#convert_11}

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

* class [LoadOptions](../../../aspose.pdf/loadoptions/)
* class [SaveOptions](../../../aspose.pdf/saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, [LoadOptions](../../../aspose.pdf/loadoptions/), Stream, [SaveOptions](../../../aspose.pdf/saveoptions/)) {#convert_12}

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

* class [LoadOptions](../../../aspose.pdf/loadoptions/)
* class [SaveOptions](../../../aspose.pdf/saveoptions/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

