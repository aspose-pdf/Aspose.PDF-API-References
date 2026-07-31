---
title: "TextAbsorber.TextAbsorber"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Costruttore di TextAbsorber. Inizializza una nuova istanza di TextAbsorber"
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

Esegue l'estrazione del testo e fornisce l'accesso al testo estratto tramite l'oggetto [`Text`](../text/).

## Esempi

L'esempio dimostra come estrarre il testo da tutte le pagine del documento PDF.

```csharp
// apri documento
Document doc = new Document(inFile);

// crea un oggetto TextAbsorber per estrarre testo
TextAbsorber absorber = new TextAbsorber();

// accetta l'assorbitore per tutte le pagine del documento
doc.Pages.Accept(absorber);

// ottieni il testo estratto
string extractedText = absorber.Text;

```

### Vedi anche

* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextAbsorber(TextExtractionOptions) {#constructor_1}

Inizializza una nuova istanza di [`TextAbsorber`](../) con le opzioni di estrazione.

```csharp
public TextAbsorber(TextExtractionOptions extractionOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| extractionOptions | TextExtractionOptions | Opzioni di estrazione del testo |

## Osservazioni

Esegue l'estrazione del testo e fornisce l'accesso al testo estratto tramite l'oggetto [`Text`](../text/).

## Esempi

L'esempio dimostra come estrarre il testo da tutte le pagine del documento PDF.

```csharp
// apri documento
Document doc = new Document(inFile);

// crea un oggetto TextAbsorber per estrarre il testo con formattazione
TextAbsorber absorber = new TextAbsorber(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure));

// accetta l'assorbitore per tutte le pagine del documento
doc.Pages.Accept(absorber);

// ottieni il testo estratto
string extractedText = absorber.Text;

```

### Vedi anche

* class [TextExtractionOptions](../../textextractionoptions/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextAbsorber(TextExtractionOptions, TextSearchOptions) {#constructor_2}

Inizializza una nuova istanza di [`TextAbsorber`](../) con le opzioni di estrazione e di ricerca del testo.

```csharp
public TextAbsorber(TextExtractionOptions extractionOptions, TextSearchOptions textSearchOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| extractionOptions | TextExtractionOptions | Opzioni di estrazione del testo |
| textSearchOptions | TextSearchOptions | Opzioni di ricerca del testo |

## Osservazioni

Esegue l'estrazione del testo e fornisce l'accesso al testo estratto tramite l'oggetto [`Text`](../text/).

### Vedi anche

* class [TextExtractionOptions](../../textextractionoptions/)
* class [TextSearchOptions](../../textsearchoptions/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## TextAbsorber(TextSearchOptions) {#constructor_3}

Inizializza una nuova istanza di [`TextAbsorber`](../) con le opzioni di ricerca del testo.

```csharp
public TextAbsorber(TextSearchOptions textSearchOptions)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| textSearchOptions | TextSearchOptions | Opzioni di ricerca del testo |

## Osservazioni

Esegue l'estrazione del testo e fornisce l'accesso al testo estratto tramite l'oggetto [`Text`](../text/).

### Vedi anche

* class [TextSearchOptions](../../textsearchoptions/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


