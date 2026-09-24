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
public bool Convert(string outputLogFileName, PdfFormat format, ConvertErrorAction action, ConvertTransparencyAction transparencyAction)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputLogFileName | string | Path to file where the comments will be stored. |
| format | PdfFormat | The pdf format. |
| action | ConvertErrorAction | Action for objects that can not be converted |
| transparencyAction | ConvertTransparencyAction | Action for image masked objects |

### Return Value

bool

The operation result

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, [PdfFormat](../../../aspose.pdf/pdfformat/), [ConvertErrorAction](../../../aspose.pdf/converterroraction/), [ConvertTransparencyAction](../../../aspose.pdf/converttransparencyaction/)) {#convert_1}

Convert document and save errors into the specified file.

```csharp
public bool Convert(Stream outputLogStream, PdfFormat format, ConvertErrorAction action, ConvertTransparencyAction transparencyAction)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputLogStream | Stream | Stream where the comments will be stored. |
| format | PdfFormat | The pdf format. |
| action | ConvertErrorAction | Action for objects that can not be converted |
| transparencyAction | ConvertTransparencyAction | Action for image masked objects |

### Return Value

bool

The operation result

### See Also

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
| outputLogFileName | string | Path to file where the comments will be stored. |
| format | PdfFormat | The pdf format. |
| action | ConvertErrorAction | Action for objects that can not be converted |

### Return Value

bool

The operation result

### See Also

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

bool

The operation result

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(CallBackGetHocrWithPage, bool) {#convert_4}



```csharp
public bool Convert(CallBackGetHocrWithPage callback, bool flattenImages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| callback | CallBackGetHocrWithPage |  |
| flattenImages | bool |  |

### Return Value

bool

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(CallBackGetHocr, bool) {#convert_5}



```csharp
public bool Convert(CallBackGetHocr callback, bool flattenImages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| callback | CallBackGetHocr |  |
| flattenImages | bool |  |

### Return Value

bool

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

bool

The operation result

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert([Fixup](../../../aspose.pdf/fixup/), Stream, bool, object[]) {#convert_7}

Convert document by applying the Fixup.

```csharp
public bool Convert(Fixup fixup, Stream outputLog, bool onlyValidation, object[] parameters)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fixup | Fixup | The Fixup type. |
| outputLog | Stream | The log of process. |
| onlyValidation | bool | Only document validation. |
| parameters | object[] | Properties for Fixup that can not be set. |

### Return Value

bool

The operation result.

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert([Fixup](../../../aspose.pdf/fixup/), string, bool, object[]) {#convert_8}

Convert document by applying the Fixup.

```csharp
public bool Convert(Fixup fixup, string outputLog, bool onlyValidation, object[] parameters)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fixup | Fixup | The Fixup type. |
| outputLog | string | The log of process. |
| onlyValidation | bool | Only document validation. |
| parameters | object[] | Properties for Fixup that can not be set. |

### Return Value

bool

The operation result.

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, [LoadOptions](../../../aspose.pdf/loadoptions/), string, [SaveOptions](../../../aspose.pdf/saveoptions/)) {#convert_9}

Converts source file in source format into destination file in destination format.

```csharp
public void Convert(string srcFileName, LoadOptions loadOptions, string dstFileName, SaveOptions saveOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| srcFileName | string | The source file name. |
| loadOptions | LoadOptions | The source file format. |
| dstFileName | string | The destination file name. |
| saveOptions | SaveOptions | The destination file format. |

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, [LoadOptions](../../../aspose.pdf/loadoptions/), string, [SaveOptions](../../../aspose.pdf/saveoptions/)) {#convert_10}

Converts stream in source format into destination file in destination format.

```csharp
public void Convert(Stream srcStream, LoadOptions loadOptions, string dstFileName, SaveOptions saveOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| srcStream | Stream | The source stream. |
| loadOptions | LoadOptions | The source stream format. |
| dstFileName | string | The destination file name. |
| saveOptions | SaveOptions | The destination file format. |

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(string, [LoadOptions](../../../aspose.pdf/loadoptions/), Stream, [SaveOptions](../../../aspose.pdf/saveoptions/)) {#convert_11}

Converts source file in source format into stream in destination format.

```csharp
public void Convert(string srcFileName, LoadOptions loadOptions, Stream dstStream, SaveOptions saveOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| srcFileName | string | The source file name. |
| loadOptions | LoadOptions | The source file format. |
| dstStream | Stream | The destination stream. |
| saveOptions | SaveOptions | The destination stream format. |

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Convert(Stream, [LoadOptions](../../../aspose.pdf/loadoptions/), Stream, [SaveOptions](../../../aspose.pdf/saveoptions/)) {#convert_12}

Converts stream in source format into stream in destination format.

```csharp
public void Convert(Stream srcStream, LoadOptions loadOptions, Stream dstStream, SaveOptions saveOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| srcStream | Stream | The source stream. |
| loadOptions | LoadOptions | The source stream format. |
| dstStream | Stream | The destination stream. |
| saveOptions | SaveOptions | The destination file format. |

### See Also

* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

