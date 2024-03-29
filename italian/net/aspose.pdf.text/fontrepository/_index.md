---
title: FontRepository
second_title: Aspose.PDF per .NET API Reference
description: Esegue la ricerca dei caratteri. Cerca nei font installati dal sistema e nei font Pdf standard. Fornisce anche funzionalità per aprire font personalizzati.
type: docs
weight: 6720
url: /it/net/aspose.pdf.text/fontrepository/
---
## FontRepository class

Esegue la ricerca dei caratteri. Cerca nei font installati dal sistema e nei font Pdf standard. Fornisce anche funzionalità per aprire font personalizzati.

```csharp
public sealed class FontRepository
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [FontRepository](fontrepository)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| static [Sources](../../aspose.pdf.text/fontrepository/sources) { get; } | Ottiene la raccolta delle fonti dei caratteri. |
| static [Substitutions](../../aspose.pdf.text/fontrepository/substitutions) { get; } | Ottiene la raccolta delle strategie di sostituzione dei caratteri. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont#findfont)(string) | Cerca e restituisce il font con il nome del font specificato. |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont#findfont_3)(string, bool) | Cerca e restituisce il font con il nome del font specificato ignorando o rispettando la distinzione tra maiuscole e minuscole. |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont#findfont_1)(string, FontStyles) | Cerca e restituisce il carattere con il nome del carattere e lo stile del carattere specificati. |
| static [FindFont](../../aspose.pdf.text/fontrepository/findfont#findfont_2)(string, FontStyles, bool) | Cerca e restituisce il carattere con il nome del carattere e lo stile del carattere specificati ignorando o rispettando la distinzione tra maiuscole e minuscole. |
| static [LoadFonts](../../aspose.pdf.text/fontrepository/loadfonts)() | Carica i font installati dal sistema e i font Pdf standard. Questo metodo è stato progettato per accelerare il processo di caricamento dei caratteri. Per impostazione predefinita, i caratteri vengono caricati alla prima richiesta per qualsiasi carattere. L'uso di questo metodo carica i font Pdf di sistema e standard immediatamente prima dell'apertura di qualsiasi documento Pdf. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont#openfont_1)(string) | Apre il font con il percorso del file del font specificato. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont#openfont)(Stream, FontTypes) | Apre il font con il flusso di font specificato. |
| static [OpenFont](../../aspose.pdf.text/fontrepository/openfont#openfont_2)(string, string) | Apre il font con il percorso del file del font e il percorso del file delle metriche specificati. |
| static [ReloadFonts](../../aspose.pdf.text/fontrepository/reloadfonts)() | Ricarica tutti i font specificati dalla proprietà[`Sources`](./sources) |

### Esempi

L'esempio mostra come trovare il font e sostituire il font del testo della prima pagina.

```csharp
// Visualizza il valore IsSubset del carattere della prima occorrenza del testo
Font font = FontRepository.FindFont("Arial");

// Apri documento
Document doc = new Document(@"D:\Tests\input.pdf");

// assicurati che tutti i caratteri dichiarati nelle risorse della pagina siano incorporati
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// nota che se i caratteri sono dichiarati nelle risorse del modulo non sono accessibili dalle risorse della pagina
doc.Pages[1].Accept(absorber);

// Trova carattere
absorber.TextFragments[1].TextState.Font = font;

// Apri documento
doc.Save(@"D:\Tests\output.pdf"); 
```

### Guarda anche

* class [TextFragmentAbsorber](../textfragmentabsorber)
* class [Document](../../aspose.pdf/document)
* spazio dei nomi [Aspose.Pdf.Text](../../aspose.pdf.text)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
