---
title: "PdfContentEditor.ReplaceText"
linktitle: "ReplaceText"
articleTitle: "ReplaceText"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfContentEditor method. Replaces text in the PDF file on the specified page. TextState object (font family, color) can be specified to replaced text."
type: docs
weight: 470
url: "/net/aspose.pdf.facades/pdfcontenteditor/replacetext/"
product_version: "26.9.0"
---
## ReplaceText(string, int, string, [TextState](../../../aspose.pdf.text/textstate/)) {#replacetext}

Replaces text in the PDF file on the specified page. [`TextState`](../../../aspose.pdf.text/textstate/) object (font family, color) can be specified to replaced text.

```csharp
public bool ReplaceText(string srcString, int thePage, string destString, TextState textState)
```

| Parameter | Type | Description |
| --- | --- | --- |
| srcString | string | The string to be replaced. |
| thePage | int | Page number (0 means "all pages"). |
| destString | string | The replaced string. |
| textState | TextState | Text state (Text Color, Font etc). |

### Return Value

bool

Returns true if replacement was made.

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, string) {#replacetext_1}

Replaces text in the PDF file.

```csharp
public bool ReplaceText(string srcString, string destString)
```

| Parameter | Type | Description |
| --- | --- | --- |
| srcString | string | The string to be replaced. |
| destString | string | Replacing string. |

### Return Value

bool

Returns true if replacement was made.

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, int, string) {#replacetext_2}

Replaces text in the PDF file on the specified page.

```csharp
public bool ReplaceText(string srcString, int thePage, string destString)
```

| Parameter | Type | Description |
| --- | --- | --- |
| srcString | string | The sting to be replaced. |
| thePage | int | Page number (0 for all pages) |
| destString | string | Replacing string. |

### Return Value

bool

Returns true if replacement was made.

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, string, [TextState](../../../aspose.pdf.text/textstate/)) {#replacetext_3}

Replaces text in the PDF file using specified [`TextState`](../../../aspose.pdf.text/textstate/) object.

```csharp
public bool ReplaceText(string srcString, string destString, TextState textState)
```

| Parameter | Type | Description |
| --- | --- | --- |
| srcString | string | String to be replaced |
| destString | string | Replacing string |
| textState | TextState | Text state (Text Color, Font etc) |

### Return Value

bool

Returns true if replacement was made.

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, string, int) {#replacetext_4}

Replaces text in the PDF file and sets font size.

```csharp
public bool ReplaceText(string srcString, string destString, int fontSize)
```

| Parameter | Type | Description |
| --- | --- | --- |
| srcString | string | String to be replaced. |
| destString | string | Replacing string. |
| fontSize | int | Font size. |

### Return Value

bool

Returns true if replacement was made.

### See Also

* class [PdfContentEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

