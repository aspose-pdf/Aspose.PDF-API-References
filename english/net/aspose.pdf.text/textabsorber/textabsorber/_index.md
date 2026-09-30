---
title: "TextAbsorber.TextAbsorber"
linktitle: "TextAbsorber"
articleTitle: "TextAbsorber"
second_title: "Aspose.PDF for .NET API Reference"
description: "TextAbsorber constructor. Initializes a new instance of the TextAbsorber."
type: docs
weight: 10
url: "/net/aspose.pdf.text/textabsorber/textabsorber/"
product_version: "26.9.0"
---
## TextAbsorber() {#constructor}

Initializes a new instance of the [`TextAbsorber`](../../../aspose.pdf.text/textabsorber/).

Performs text extraction and provides access to the extracted text via `Text` object.

```csharp
public TextAbsorber()
```

## Examples

The example demonstrates how to extract text from all pages of the PDF document.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text
TextAbsorber absorber = new TextAbsorber();

// accept the absorber for all document's pages
doc.Pages.Accept(absorber);

// get the extracted text
string extractedText = absorber.Text;
```

### See Also

* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextAbsorber([TextExtractionOptions](../../../aspose.pdf.text/textextractionoptions/)) {#constructor_1}

Initializes a new instance of the [`TextAbsorber`](../../../aspose.pdf.text/textabsorber/) with extraction options.

Performs text extraction and provides access to the extracted text via `Text` object.

```csharp
public TextAbsorber(TextExtractionOptions extractionOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| extractionOptions | TextExtractionOptions | Text extraction options |

## Examples

The example demonstrates how to extract text from all pages of the PDF document.

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text with formatting
TextAbsorber absorber = new TextAbsorber(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure));

// accept the absorber for all document's pages
doc.Pages.Accept(absorber);

// get the extracted text
string extractedText = absorber.Text;
```

### See Also

* class [TextExtractionOptions](../../../aspose.pdf.text/textextractionoptions/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextAbsorber([TextSearchOptions](../../../aspose.pdf.text/textsearchoptions/)) {#constructor_2}

Initializes a new instance of the [`TextAbsorber`](../../../aspose.pdf.text/textabsorber/) with text search options.

Performs text extraction and provides access to the extracted text via `Text` object.

```csharp
public TextAbsorber(TextSearchOptions textSearchOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| textSearchOptions | TextSearchOptions | Text search options |

### See Also

* class [TextSearchOptions](../../../aspose.pdf.text/textsearchoptions/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextAbsorber([TextExtractionOptions](../../../aspose.pdf.text/textextractionoptions/), [TextSearchOptions](../../../aspose.pdf.text/textsearchoptions/)) {#constructor_3}

Initializes a new instance of the [`TextAbsorber`](../../../aspose.pdf.text/textabsorber/) with extraction and text search options.

Performs text extraction and provides access to the extracted text via `Text` object.

```csharp
public TextAbsorber(TextExtractionOptions extractionOptions, TextSearchOptions textSearchOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| extractionOptions | TextExtractionOptions | Text extraction options |
| textSearchOptions | TextSearchOptions | Text search options |

### See Also

* class [TextExtractionOptions](../../../aspose.pdf.text/textextractionoptions/)
* class [TextSearchOptions](../../../aspose.pdf.text/textsearchoptions/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

