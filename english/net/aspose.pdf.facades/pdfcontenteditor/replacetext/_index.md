---
title: ReplaceText
second_title: Aspose.PDF for .NET API Reference
description: Replaces text in the PDF file on the specified page. TextStateaspose.pdf.text/textstate object font family color can be specified to replaced text.
type: docs
weight: 450
url: /net/aspose.pdf.facades/pdfcontenteditor/replacetext/
---
## ReplaceText(string, int, string, TextState) {#replacetext_1}

Replaces text in the PDF file on the specified page. [`TextState`](../../../aspose.pdf.text/textstate) object (font family, color) can be specified to replaced text.

```csharp
public bool ReplaceText(string srcString, int thePage, string destString, TextState textState)
```

| Parameter | Type | Description |
| --- | --- | --- |
| srcString | String | The string to be replaced. |
| thePage | Int32 | Page number (0 means "all pages"). |
| destString | String | The replaced string. |
| textState | TextState | Text state (Text Color, Font etc). |

### Return Value

Returns true if replacement was made.

### Examples

The example demonstrates how to replace text on the first page of the PDF document and set [`TextState`](../../../aspose.pdf.text/textstate) text properties for the new text.

```csharp
// open document
Document doc = new Document(inFile);

// Create font and mark it to be embedded
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// create PdfContentEditor object to edit text
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// create textState object
TextState textState = new TextState();
textState.Font = font;
textState.FontSize = 17;
textState.FontStyle = FontStyle.Bold | FontStyle.Italic;
textState.ForegroundColor = Color.Red;

// change text with specified font
editor.ReplaceText("hello world", 1, "hi world", textState);

// save document
doc.Save(outFile);
```

### See Also

* class [TextState](../../../aspose.pdf.text/textstate)
* class [PdfContentEditor](../../pdfcontenteditor)
* namespace [Aspose.Pdf.Facades](../../pdfcontenteditor)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, string) {#replacetext_2}

Replaces text in the PDF file.

```csharp
public bool ReplaceText(string srcString, string destString)
```

| Parameter | Type | Description |
| --- | --- | --- |
| srcString | String | The string to be replaced. |
| destString | String | Replacing string. |

### Return Value

Returns true if replacement was made.

### Examples

The example demonstrates how to replace text in PDF document.

```csharp
// open document
Document doc = new Document(inFile);

// create PdfContentEditor object to edit text
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// change text 
editor.ReplaceText("hello world", "hi world");

// save document
doc.Save(outFile);
```

### See Also

* class [PdfContentEditor](../../pdfcontenteditor)
* namespace [Aspose.Pdf.Facades](../../pdfcontenteditor)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, int, string) {#replacetext}

Replaces text in the PDF file on the specified page.

```csharp
public bool ReplaceText(string srcString, int thePage, string destString)
```

| Parameter | Type | Description |
| --- | --- | --- |
| srcString | String | The sting to be replaced. |
| thePage | Int32 | Page number (0 for all pages) |
| destString | String | Replacing string. |

### Return Value

Returns true if replacement was made.

### Examples

The example demonstrates how to replace text in PDF document on the specified page.

```csharp
// open document
Document doc = new Document(inFile);

// create PdfContentEditor object to edit text
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// change text 
editor.ReplaceText("hello world", 1, "hi world");

// save document
doc.Save(outFile);
```

### See Also

* class [PdfContentEditor](../../pdfcontenteditor)
* namespace [Aspose.Pdf.Facades](../../pdfcontenteditor)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, string, TextState) {#replacetext_3}

Replaces text in the PDF file using specified [`TextState`](../../../aspose.pdf.text/textstate) object.

```csharp
public bool ReplaceText(string srcString, string destString, TextState textState)
```

| Parameter | Type | Description |
| --- | --- | --- |
| srcString | String | String to be replaced |
| destString | String | Replacing string |
| textState | TextState | Text state (Text Color, Font etc) |

### Return Value

Returns true if replacement was made.

### Examples

The example demonstrates how to replace text and set [`TextState`](../../../aspose.pdf.text/textstate) text properties for the new text.

```csharp
// open document
Document doc = new Document(inFile);

// Create font and mark it to be embedded
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// create PdfContentEditor object to edit text
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// create textState object
TextState textState = new TextState();
textState.Font = font;
textState.FontStyle = FontStyle.Bold | FontStyle.Italic;

// change text with specified font
editor.ReplaceText("hello world", "hi world", textState);

// save document
doc.Save(outFile);
```

### See Also

* class [TextState](../../../aspose.pdf.text/textstate)
* class [PdfContentEditor](../../pdfcontenteditor)
* namespace [Aspose.Pdf.Facades](../../pdfcontenteditor)
* assembly [Aspose.PDF](../../../)

---

## ReplaceText(string, string, int) {#replacetext_4}

Replaces text in the PDF file and sets font size.

```csharp
public bool ReplaceText(string srcString, string destString, int fontSize)
```

| Parameter | Type | Description |
| --- | --- | --- |
| srcString | String | String to be replaced. |
| destString | String | Replacing string. |
| fontSize | Int32 | Font size. |

### Return Value

Returns true if replacement was made.

### Examples

The example demonstrates how to replace text and set font size for the new text.

```csharp
// open document
Document doc = new Document(inFile);

// Create font and mark it to be embedded
Aspose.Pdf.Text.Font font = FontRepository.FindFont("Courier New");
font.IsEmbedded = true;

// create PdfContentEditor object to edit text
PdfContentEditor editor = new PdfContentEditor();
editor.BindPdf(doc);

// change text with specified font
editor.ReplaceText("hello world", "hi world", 14);

// save document
doc.Save(outFile);
```

### See Also

* class [PdfContentEditor](../../pdfcontenteditor)
* namespace [Aspose.Pdf.Facades](../../pdfcontenteditor)
* assembly [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
