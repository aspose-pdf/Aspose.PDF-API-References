---
title: Class UnifiedSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.UnifiedSaveOptions. Questa classe rappresenta le opzioni di salvataggio per il salvataggio che utilizza un modo di conversione unificato con un modello di documento interno unificato
type: docs
weight: 11140
url: /it/net/aspose.pdf/unifiedsaveoptions/
---
## Classe UnifiedSaveOptions

Questa classe rappresenta le opzioni di salvataggio per il salvataggio che utilizza un modo di conversione unificato (con modello di documento interno unificato)

```csharp
public class UnifiedSaveOptions : SaveOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [UnifiedSaveOptions](unifiedsaveoptions/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Ottiene o imposta un valore booleano che indica se i glifi del carattere saranno memorizzati nella cache durante la preparazione delle pagine aps. Migliora le prestazioni della conversione da pdf ad altri formati, ma aumenta il consumo di memoria. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Ottiene o imposta un valore booleano che indica se l'oggetto Response sarà chiuso dopo che il documento è stato salvato nella risposta. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Questo attributo attiva la funzionalità per estrarre immagini o testo per documenti PDF con sottolivello OCR. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Formato di salvataggio dei dati. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback per gestire eventuali avvisi generati. Il WarningHandler restituisce un elemento dell'enum ReturnAction che specifica se Continuare o Abortire. Continuare è l'azione predefinita e l'operazione di salvataggio continua, tuttavia l'utente può anche restituire Abortire, nel qual caso l'operazione di salvataggio dovrebbe cessare. |

## Campi

| Nome | Descrizione |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Elabora le pagine in più thread. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | A volte i PDF contengono immagini di sfondo (di pagine o celle di tabella) costruite da diverse immagini di sfondo a mosaico identiche messe una vicino all'altra. In tal caso, i renderer dei formati di destinazione (ad esempio MsWord per il formato DOCS) a volte generano confini visibili tra le parti delle immagini di sfondo, poiché le loro tecniche di levigatura dei bordi delle immagini (anti-aliasing) sono diverse da quelle di Acrobat Reader. Se sembra che il documento esportato contenga tali confini visibili tra le parti delle stesse immagini di sfondo, si prega di provare a utilizzare questa impostazione per eliminare quell'effetto indesiderato. ATTENZIONE! Questa ottimizzazione della qualità rallenta solitamente in modo sostanziale la conversione, quindi, si prega di utilizzare questa opzione solo quando è davvero necessario. |

### Vedi Anche

* classe [SaveOptions](../saveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)