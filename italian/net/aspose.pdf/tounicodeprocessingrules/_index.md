---
title: "Classe ToUnicodeProcessingRules"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.ToUnicodeProcessingRules. Questa classe descrive le regole che possono essere utilizzate per risolvere l'errore di Adobe Preflight 'Il testo non può essere mappato a Unicode'"
type: docs
weight: 11300
url: /it/net/aspose.pdf/tounicodeprocessingrules/
---
## ToUnicodeProcessingRules class

Questa classe descrive le regole che possono essere utilizzate per risolvere l'errore Adobe Preflight "Il testo non può essere mappato a Unicode".

```csharp
public class ToUnicodeProcessingRules
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor)() | Inizializza una nuova istanza della classe `ToUnicodeProcessingRules`. |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor_1)(bool) | Inizializza una nuova istanza della classe `ToUnicodeProcessingRules` con l'opzione specificata per rimuovere gli spazi dai nomi CMap. |
| [ToUnicodeProcessingRules](tounicodeprocessingrules/#constructor_2)(bool, bool) | Inizializza una nuova istanza della classe `ToUnicodeProcessingRules` con le opzioni specificate. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [MapNonLinkedSymbolsOnSpace](../../aspose.pdf/tounicodeprocessingrules/mapnonlinkedsymbolsonspace/) { get; set; } | Alcuni font non forniscono informazioni sugli Unicode per alcuni simboli di testo. Questa mancanza di informazioni genera un errore "Text cannot be mapped to Unicode". Usa questo flag per mappare i simboli non collegati sul carattere Unicode "space" (codice 32). |
| [RemoveSpacesFromCMapNames](../../aspose.pdf/tounicodeprocessingrules/removespacesfromcmapnames/) { get; set; } | Alcuni font hanno mappe di codici carattere ToUnicode con spazi nei nomi. Questi spazi potrebbero generare errori nella mappatura del testo Unicode. Questo flag indica di rimuovere gli spazi dai nomi delle mappe di codici carattere ToUnicode. Per impostazione predefinita false. |

### Vedi anche

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


