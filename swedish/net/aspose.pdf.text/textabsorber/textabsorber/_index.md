---
title: TextAbsorber.TextAbsorber
second_title: Aspose.PDF for .NET API Reference
description: TextAbsorber-konstruktör. Initierar en ny instans av TextAbsorber
type: docs
weight: 10
url: /sv/net/aspose.pdf.text/textabsorber/textabsorber/
---
## TextAbsorber() {#constructor}

Initierar en ny instans av [`TextAbsorber`](../).

```csharp
public TextAbsorber()
```

## Kommentarer

Utför textutvinning och ger åtkomst till den utvunna texten via [`Text`](../text/) objekt.

## Exempel

Exemplet visar hur man extraherar text från alla sidor i PDF-dokumentet.

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

### Se Även

* klass [TextAbsorber](../)
* namnrymd [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* samling [Aspose.PDF](../../../)

---

## TextAbsorber(TextExtractionOptions) {#constructor_1}

Initierar en ny instans av [`TextAbsorber`](../) med utvinningsalternativ.

```csharp
public TextAbsorber(TextExtractionOptions extractionOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| extractionOptions | TextExtractionOptions | Alternativ för textutvinning |

## Kommentarer

Utför textutvinning och ger åtkomst till den utvunna texten via [`Text`](../text/) objekt.

## Exempel

Exemplet visar hur man extraherar text från alla sidor i PDF-dokumentet.

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

### Se Även

* klass [TextExtractionOptions](../../textextractionoptions/)
* klass [TextAbsorber](../)
* namnrymd [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* samling [Aspose.PDF](../../../)

---

## TextAbsorber(TextExtractionOptions, TextSearchOptions) {#constructor_2}

Initierar en ny instans av [`TextAbsorber`](../) med utvinnings- och text sökalternativ.

```csharp
public TextAbsorber(TextExtractionOptions extractionOptions, TextSearchOptions textSearchOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| extractionOptions | TextExtractionOptions | Alternativ för textutvinning |
| textSearchOptions | TextSearchOptions | Alternativ för textsökning |

## Kommentarer

Utför textutvinning och ger åtkomst till den utvunna texten via [`Text`](../text/) objekt.

### Se Även

* klass [TextExtractionOptions](../../textextractionoptions/)
* klass [TextSearchOptions](../../textsearchoptions/)
* klass [TextAbsorber](../)
* namnrymd [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* samling [Aspose.PDF](../../../)

---

## TextAbsorber(TextSearchOptions) {#constructor_3}

Initierar en ny instans av [`TextAbsorber`](../) med alternativ för textsökning.

```csharp
public TextAbsorber(TextSearchOptions textSearchOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| textSearchOptions | TextSearchOptions | Alternativ för textsökning |

## Kommentarer

Utför textutvinning och ger åtkomst till den utvunna texten via [`Text`](../text/) objekt.

### Se Även

* klass [TextSearchOptions](../../textsearchoptions/)
* klass [TextAbsorber](../)
* namnrymd [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* samling [Aspose.PDF](../../../)