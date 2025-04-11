---
title: TextAbsorber.TextAbsorber
second_title: Aspose.PDF for .NET API Reference
description: Costruttore di TextAbsorber. Inizializza una nuova istanza di TextAbsorber
type: docs
weight: 10
url: /it/net/aspose.pdf.text/textabsorber/textabsorber/
---
## TextAbsorber() {#constructor}

Inizializza una nuova istanza di [`TextAbsorber`](../).

```csharp
public TextAbsorber()
```

## Osservazioni

Esegue l'estrazione del testo e fornisce accesso al testo estratto tramite l'oggetto [`Text`](../text/).

## Esempi

L'esempio dimostra come estrarre testo da tutte le pagine del documento PDF.

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

### Vedi Anche

* classe [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextAbsorber(TextExtractionOptions) {#constructor_1}

Inizializza una nuova istanza di [`TextAbsorber`](../) con opzioni di estrazione.

```csharp
public TextAbsorber(TextExtractionOptions extractionOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| extractionOptions | TextExtractionOptions | Opzioni di estrazione del testo |

## Osservazioni

Esegue l'estrazione del testo e fornisce accesso al testo estratto tramite l'oggetto [`Text`](../text/).

## Esempi

L'esempio dimostra come estrarre testo da tutte le pagine del documento PDF.

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

### Vedi Anche

* classe [TextExtractionOptions](../../textextractionoptions/)
* classe [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextAbsorber(TextExtractionOptions, TextSearchOptions) {#constructor_2}

Inizializza una nuova istanza di [`TextAbsorber`](../) con opzioni di estrazione e di ricerca del testo.

```csharp
public TextAbsorber(TextExtractionOptions extractionOptions, TextSearchOptions textSearchOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| extractionOptions | TextExtractionOptions | Opzioni di estrazione del testo |
| textSearchOptions | TextSearchOptions | Opzioni di ricerca del testo |

## Osservazioni

Esegue l'estrazione del testo e fornisce accesso al testo estratto tramite l'oggetto [`Text`](../text/).

### Vedi Anche

* classe [TextExtractionOptions](../../textextractionoptions/)
* classe [TextSearchOptions](../../textsearchoptions/)
* classe [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextAbsorber(TextSearchOptions) {#constructor_3}

Inizializza una nuova istanza di [`TextAbsorber`](../) con opzioni di ricerca del testo.

```csharp
public TextAbsorber(TextSearchOptions textSearchOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| textSearchOptions | TextSearchOptions | Opzioni di ricerca del testo |

## Osservazioni

Esegue l'estrazione del testo e fornisce accesso al testo estratto tramite l'oggetto [`Text`](../text/).

### Vedi Anche

* classe [TextSearchOptions](../../textsearchoptions/)
* classe [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)