---
title: TextAbsorber.TextAbsorber
second_title: Aspose.PDF for .NET API Reference
description: TextAbsorber-Konstruktor. Initialisiert eine neue Instanz des TextAbsorbers
type: docs
weight: 10
url: /de/net/aspose.pdf.text/textabsorber/textabsorber/
---
## TextAbsorber() {#constructor}

Initialisiert eine neue Instanz des [`TextAbsorber`](../).

```csharp
public TextAbsorber()
```

## Bemerkungen

Führt die Textextraktion durch und bietet Zugriff auf den extrahierten Text über das [`Text`](../text/) Objekt.

## Beispiele

Das Beispiel zeigt, wie man Text von allen Seiten des PDF-Dokuments extrahiert.

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

### Siehe auch

* Klasse [TextAbsorber](../)
* Namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../../)

---

## TextAbsorber(TextExtractionOptions) {#constructor_1}

Initialisiert eine neue Instanz des [`TextAbsorber`](../) mit Extraktionsoptionen.

```csharp
public TextAbsorber(TextExtractionOptions extractionOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| extractionOptions | TextExtractionOptions | Textextraktionsoptionen |

## Bemerkungen

Führt die Textextraktion durch und bietet Zugriff auf den extrahierten Text über das [`Text`](../text/) Objekt.

## Beispiele

Das Beispiel zeigt, wie man Text von allen Seiten des PDF-Dokuments extrahiert.

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

### Siehe auch

* Klasse [TextExtractionOptions](../../textextractionoptions/)
* Klasse [TextAbsorber](../)
* Namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../../)

---

## TextAbsorber(TextExtractionOptions, TextSearchOptions) {#constructor_2}

Initialisiert eine neue Instanz des [`TextAbsorber`](../) mit Extraktions- und Textsuchoptionen.

```csharp
public TextAbsorber(TextExtractionOptions extractionOptions, TextSearchOptions textSearchOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| extractionOptions | TextExtractionOptions | Textextraktionsoptionen |
| textSearchOptions | TextSearchOptions | Textsuchoptionen |

## Bemerkungen

Führt die Textextraktion durch und bietet Zugriff auf den extrahierten Text über das [`Text`](../text/) Objekt.

### Siehe auch

* Klasse [TextExtractionOptions](../../textextractionoptions/)
* Klasse [TextSearchOptions](../../textsearchoptions/)
* Klasse [TextAbsorber](../)
* Namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../../)

---

## TextAbsorber(TextSearchOptions) {#constructor_3}

Initialisiert eine neue Instanz des [`TextAbsorber`](../) mit Textsuchoptionen.

```csharp
public TextAbsorber(TextSearchOptions textSearchOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| textSearchOptions | TextSearchOptions | Textsuchoptionen |

## Bemerkungen

Führt die Textextraktion durch und bietet Zugriff auf den extrahierten Text über das [`Text`](../text/) Objekt.

### Siehe auch

* Klasse [TextSearchOptions](../../textsearchoptions/)
* Klasse [TextAbsorber](../)
* Namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* Assembly [Aspose.PDF](../../../)