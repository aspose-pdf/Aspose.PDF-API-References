---
title: Class ToUnicodeProcessingRules
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.ToUnicodeProcessingRules. Questa classe descrive le regole che possono essere utilizzate per risolvere l'errore di Adobe Preflight "Il testo non può essere mappato su Unicode"
type: docs
weight: 11110
url: /it/net/aspose.pdf/tounicodeprocessingrules/
---
## Classe ToUnicodeProcessingRules

Questa classe descrive le regole che possono essere utilizzate per risolvere l'errore di Adobe Preflight "Il testo non può essere mappato su Unicode".

```csharp
public class ToUnicodeProcessingRules
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor)() | Inizializza una nuova istanza della classe `ToUnicodeProcessingRules`. |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor_1)(bool) | Inizializza una nuova istanza della classe `ToUnicodeProcessingRules` con l'opzione specificata per rimuovere gli spazi dai nomi CMap. |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor_2)(bool, bool) | Inizializza una nuova istanza della classe `ToUnicodeProcessingRules` con opzioni specificate. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [MapNonLinkedSymbolsOnSpace](../../aspose.pdf/tounicodeprocessingrules/mapnonlinkedsymbolsonspace/) { get; set; } | Alcuni caratteri non forniscono informazioni sugli unicodes per alcuni simboli di testo. Questa mancanza di informazioni provoca un errore "Il testo non può essere mappato su Unicode". Usa questo flag per mappare simboli non collegati su unicode "spazio" (codice 32). |
| [RemoveSpacesFromCMapNames](../../aspose.pdf/tounicodeprocessingrules/removespacesfromcmapnames/) { get; set; } | Alcuni caratteri hanno mappe di codice carattere ToUnicode con spazi nei nomi. Questi spazi potrebbero causare errori con la mappatura del testo unicode. Questo flag ordina di rimuovere gli spazi dai nomi delle mappe di codice carattere ToUnicode. Di default è falso. |

### Vedi Anche

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)