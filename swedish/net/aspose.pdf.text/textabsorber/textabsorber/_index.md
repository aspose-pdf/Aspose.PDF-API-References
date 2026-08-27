---
title: "TextAbsorber.TextAbsorber"
second_title: "Aspose.PDF för .NET API‑referens"
description: "TextAbsorber-konstruktor. Initierar en ny instans av TextAbsorber"
type: docs
weight: 10
url: /sv/net/aspose.pdf.text/textabsorber/textabsorber/
---
## TextAbsorber() {#constructor}

Initierar en ny instans av [`TextAbsorber`](../).

```csharp
public TextAbsorber()
```

## Anmärkningar

Utför textextraktion och ger åtkomst till den extraherade texten via [`Text`](../text/)-objektet.

## Exempel

Exemplet visar hur man extraherar text från alla sidor i PDF-dokumentet.

```csharp
// öppna dokument
Document doc = new Document(inFile);

// skapa TextAbsorber-objekt för att extrahera text
TextAbsorber absorber = new TextAbsorber();

// acceptera absorberaren för alla dokumentets sidor
doc.Pages.Accept(absorber);

// hämta den extraherade texten
string extractedText = absorber.Text;

```

### Se även

* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextAbsorber(TextExtractionOptions) {#constructor_1}

Initierar en ny instans av [`TextAbsorber`](../) med extraktionsalternativ.

```csharp
public TextAbsorber(TextExtractionOptions extractionOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| extractionOptions | TextExtractionOptions | Alternativ för textextraktion |

## Anmärkningar

Utför textextraktion och ger åtkomst till den extraherade texten via [`Text`](../text/)-objektet.

## Exempel

Exemplet visar hur man extraherar text från alla sidor i PDF-dokumentet.

```csharp
// öppna dokument
Document doc = new Document(inFile);

// skapa ett TextAbsorber-objekt för att extrahera text med formatering
TextAbsorber absorber = new TextAbsorber(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure));

// acceptera absorberaren för alla dokumentets sidor
doc.Pages.Accept(absorber);

// hämta den extraherade texten
string extractedText = absorber.Text;

```

### Se även

* class [TextExtractionOptions](../../textextractionoptions/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextAbsorber(TextExtractionOptions, TextSearchOptions) {#constructor_2}

Initierar en ny instans av [`TextAbsorber`](../) med extraktions- och textsökningsalternativ.

```csharp
public TextAbsorber(TextExtractionOptions extractionOptions, TextSearchOptions textSearchOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| extractionOptions | TextExtractionOptions | Alternativ för textextraktion |
| textSearchOptions | TextSearchOptions | Alternativ för textsökning |

## Anmärkningar

Utför textextraktion och ger åtkomst till den extraherade texten via [`Text`](../text/)-objektet.

### Se även

* class [TextExtractionOptions](../../textextractionoptions/)
* class [TextSearchOptions](../../textsearchoptions/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextAbsorber(TextSearchOptions) {#constructor_3}

Initierar en ny instans av [`TextAbsorber`](../) med textsökningsalternativ.

```csharp
public TextAbsorber(TextSearchOptions textSearchOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| textSearchOptions | TextSearchOptions | Alternativ för textsökning |

## Anmärkningar

Utför textextraktion och ger åtkomst till den extraherade texten via [`Text`](../text/)-objektet.

### Se även

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


