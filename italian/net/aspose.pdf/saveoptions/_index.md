---
title: Class SaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.SaveOptions. Il tipo SaveOptions mantiene un livello di astrazione sulle singole opzioni di salvataggio
type: docs
weight: 9870
url: /it/net/aspose.pdf/saveoptions/
---
## Classe SaveOptions

Il tipo SaveOptions mantiene un livello di astrazione sulle singole opzioni di salvataggio

```csharp
public abstract class SaveOptions
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Ottiene o imposta un valore booleano che indica se i glifi del font saranno memorizzati nella cache durante la preparazione delle pagine aps. Migliora le prestazioni della conversione da pdf ad altri formati, ma aumenta il consumo di memoria. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Ottiene o imposta un valore booleano che indica se l'oggetto Response sarà chiuso dopo che il documento è stato salvato nella risposta. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Formato dei dati salvati. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback per gestire eventuali avvisi generati. Il WarningHandler restituisce un elemento dell'enumerazione ReturnAction che specifica se Continuare o Abortire. Continuare è l'azione predefinita e l'operazione di salvataggio continua, tuttavia l'utente può anche restituire Abortire, nel qual caso l'operazione di salvataggio dovrebbe cessare. |

### Vedi Anche

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)