---
title: "Classe FontRepository"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Text.FontRepository. Esegue la ricerca dei font. Cerca nei font installati nel sistema e nei font Pdf standard. Fornisce anche la funzionalità per aprire font personalizzati"
type: docs
weight: 10720
url: /it/net/aspose.pdf.text/fontrepository/
---
## FontRepository class

Esegue la ricerca dei font. Cerca nei font installati nel sistema e nei font PDF standard. Fornisce anche la funzionalità di aprire font personalizzati.

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
| static [Sources](../../aspose.pdf.text/fontrepository/sources/) { get; } | Ottiene la collezione delle font source. |
| static [Substitutions](../../aspose.pdf.text/fontrepository/substitutions/) { get; } | Ottiene la collezione delle strategie di sostituzione dei font. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont)(string) | Cerca e restituisce il font con il nome del font specificato. |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_3)(string, bool) | Cerca e restituisce il font con il nome del font specificato ignorando o rispettando la sensibilità al maiuscolo/minuscolo. |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_1)(string, FontStyles) | Cerca e restituisce il font con il nome del font e lo stile del font specificati. |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont/#findfont_2)(string, FontStyles, bool) | Cerca e restituisce il font con il nome del font e lo stile del font specificati ignorando o rispettando la sensibilità al maiuscolo/minuscolo. |
| static [LoadFonts](../../aspose.pdf.text/fontrepository/loadfonts/)() | Carica i font installati dal sistema e i font Pdf standard. Questo metodo è stato progettato per velocizzare il processo di caricamento dei font. Per impostazione predefinita i font vengono caricati alla prima richiesta di qualsiasi font. L'uso di questo metodo carica i font di sistema e i font Pdf standard immediatamente prima che venga aperto qualsiasi documento Pdf. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont_1)(string) | Apre il font con il percorso del file font specificato. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont)(Stream, FontTypes) | Apre il font con lo stream del font specificato. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont/#openfont_2)(string, string) | Apre il font con il percorso del file font specificato e il percorso del file metriche. |
| static [ReloadFonts](../../aspose.pdf.text/fontrepository/reloadfonts/)() | Ricarica tutti i font specificati dalla proprietà [`Sources`](./sources/) |

## Esempi

L'esempio dimostra come trovare il font e sostituire il font del testo della prima pagina.

```csharp
// Trova font
Font font = FontRepository.FindFont("Arial");

// Apri documento
Document doc = new Document(@"D:\Tests\input.pdf");

// Crea l'oggetto TextFragmentAbsorber per trovare tutte le occorrenze del testo "hello world"
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accetta l'assorbitore per la prima pagina
doc.Pages[1].Accept(absorber);

// Cambia il font della prima occorrenza di testo
absorber.TextFragments[1].TextState.Font = font;

// Salva documento
doc.Save(@"D:\Tests\output.pdf"); 
```

### Vedi anche

* class [TextFragmentAbsorber](../textfragmentabsorber/)
* class [Document](../../aspose.pdf/document/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


