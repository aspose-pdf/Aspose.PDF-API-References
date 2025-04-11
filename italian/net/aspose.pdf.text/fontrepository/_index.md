---
title: Class FontRepository
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Text.FontRepository. Esegue la ricerca di font. Cerca nei font installati nel sistema e nei font Pdf standard. Fornisce anche funzionalità per aprire font personalizzati.
type: docs
weight: 10540
url: /it/net/aspose.pdf.text/fontrepository/
---
## Classe FontRepository

Esegue la ricerca di font. Cerca nei font installati nel sistema e nei font Pdf standard. Fornisce anche funzionalità per aprire font personalizzati.

```csharp
public sealed class FontRepository
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [FontRepository](fontrepository/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| static [Sources](../../aspose.pdf.text/fontrepository/sources/) { get; } | Ottiene la collezione di font sources. |
| static [Substitutions](../../aspose.pdf.text/fontrepository/substitutions/) { get; } | Ottiene la collezione di strategie di sostituzione dei font. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont)(string) | Cerca e restituisce il font con il nome specificato. |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_3)(string, bool) | Cerca e restituisce il font con il nome specificato ignorando o rispettando la sensibilità al maiuscolo/minuscolo. |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_1)(string, FontStyles) | Cerca e restituisce il font con il nome e lo stile di font specificati. |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_2)(string, FontStyles, bool) | Cerca e restituisce il font con il nome e lo stile di font specificati ignorando o rispettando la sensibilità al maiuscolo/minuscolo. |
| static [LoadFonts](../../aspose.pdf.text/fontrepository/loadfonts/)() | Carica i font installati nel sistema e i font Pdf standard. Questo metodo è stato progettato per accelerare il processo di caricamento dei font. Per impostazione predefinita, i font vengono caricati alla prima richiesta per qualsiasi font. L'uso di questo metodo carica immediatamente i font di sistema e i font Pdf standard prima che venga aperto qualsiasi documento Pdf. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont_1)(string) | Apre il font con il percorso del file font specificato. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont)(Stream, FontTypes) | Apre il font con lo stream di font specificato. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont_2)(string, string) | Apre il font con il percorso del file font specificato e il percorso del file metriche. |
| static [ReloadFonts](../../aspose.pdf.text/fontrepository/reloadfonts/)() | Ricarica tutti i font specificati dalla proprietà [`Sources`](./sources/) |

## Esempi

L'esempio dimostra come trovare un font e sostituire il font del testo della prima pagina.

```csharp
// Find font
Font font = FontRepository.FindFont("Arial");

// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change font of the first text occurrence
absorber.TextFragments[1].TextState.Font = font;

// Save document
doc.Save(@"D:\Tests\output.pdf"); 
```

### Vedi Anche

* classe [TextFragmentAbsorber](../textfragmentabsorber/)
* classe [Document](../../aspose.pdf/document/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)