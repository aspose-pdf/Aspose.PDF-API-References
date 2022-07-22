---
title: DocSaveOptions
second_title: Aspose.PDF per .NET API Reference
description: Opzioni di salvataggio per lesportazione in formato Doc
type: docs
weight: 1840
url: /it/net/aspose.pdf/docsaveoptions/
---
## DocSaveOptions class

Opzioni di salvataggio per l'esportazione in formato Doc

```csharp
public class DocSaveOptions : UnifiedSaveOptions, IPipelineOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [DocSaveOptions](docsaveoptions)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AddReturnToLineEnd](../../aspose.pdf/docsaveoptions/addreturntolineend) { get; set; } | Usa interruzioni di paragrafo o di riga |
| [BatchSize](../../aspose.pdf/docsaveoptions/batchsize) { get; set; } | Definisce la dimensione batch se la conversione batch è applicabile alla coppia di formati di origine e destinazione. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse) { get; set; } | Ottiene o imposta il valore booleano che indica che l'oggetto Response verrà chiuso dopo che il documento verrà salvato nella risposta. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly) { get; set; } | Questo attributo ha attivato la funzionalità per l'estrazione di immagini o testo per documenti PDF con sottolivello OCR. |
| [Format](../../aspose.pdf/docsaveoptions/format) { get; set; } | Formato di output |
| [ImageResolutionX](../../aspose.pdf/docsaveoptions/imageresolutionx) { get; set; } | Immagini convertite risoluzione X. |
| [ImageResolutionY](../../aspose.pdf/docsaveoptions/imageresolutiony) { get; set; } | Immagini convertite risoluzione Y. |
| [MaxDistanceBetweenTextLines](../../aspose.pdf/docsaveoptions/maxdistancebetweentextlines) { get; set; } | Questo parametro viene utilizzato per raggruppare le righe di testo in paragrafi. Determina la distanza tra due righe di testo relative. Specificato in centinaia di percento dell'altezza delle righe di testo. |
| [MemorySaveModePath](../../aspose.pdf/docsaveoptions/memorysavemodepath) { get; set; } | Definisce il percorso (nome del file o nome della directory) per contenere i dati temporanei di durante la conversione in modalità di salvataggio della memoria. |
| [Mode](../../aspose.pdf/docsaveoptions/mode) { get; set; } | Modalità di riconoscimento. |
| [RecognizeBullets](../../aspose.pdf/docsaveoptions/recognizebullets) { get; set; } | Attiva il riconoscimento dei punti elenco |
| [RelativeHorizontalProximity](../../aspose.pdf/docsaveoptions/relativehorizontalproximity) { get; set; } | In Pdf le parole possono essere rappresentate internamente con operatori che stampano le parole stampando indipendentemente le loro lettere o sillabe. Quindi, per rilevare le parole a volte abbiamo bisogno di rilevare gruppi di caratteri indipendenti che in realtà sono parole. Questa impostazione definisce la larghezza dello spazio tra gli elementi di testo (lettere, sillabe) che deve essere trattata come distanza tra le parole durante il riconoscimento delle parole nel PDF sorgente . (la presenza di uno spazio vuoto almeno con questa larghezza tra le lettere significa che elementi testuali appartengono a parole diverse). È normato per la dimensione del carattere - 1.0 significa il 100% della dimensione del carattere della parola presunta. ATTENZIONE! Viene utilizzato solo nei casi quando il PDF di origine contiene caratteri specifici usati raramente per i quali non è possibile calcolare il valore ottimale dal carattere. Quindi, nella stragrande maggioranza dei casi questo parametro non cambia nulla nel documento dei risultati. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat) { get; } | Formato di salvataggio dei dati. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler) { get; set; } | Richiamata per gestire eventuali avvisi generati. WarningHandler restituisce l'elemento enum ReturnAction specificando Continue o Abort. Continua è l'azione predefinita e l'operazione di salvataggio continua, tuttavia l'utente può anche restituire Interrompi, nel qual caso l'operazione di salvataggio dovrebbe cessare. |

## Campi

| Nome | Descrizione |
| --- | --- |
| [CustomProgressHandler](../../aspose.pdf/docsaveoptions/customprogresshandler) | Questo gestore può essere utilizzato per gestire gli eventi di avanzamento della conversione fe può essere utilizzato per mostrare la barra di avanzamento o messaggi sulla quantità corrente di pagine elaborate, esempio di codice del gestore che mostra l'avanzamento sulla console è : |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages) | A volte i PDF contengono immagini di sfondo (di pagine o celle di tabella) costruite da diverse immagini di sfondo affiancate dalla stessa piastrellatura. In tal caso i renderer di formati target (ad esempio MsWord per il formato DOCS) generano talvolta confini visibili tra parti di immagini di sfondo , perché le loro tecniche di smussamento dei bordi dell'immagine (anti-aliasing) sono diverse da Acrobat Reader. Se sembra che il documento esportato contenga limiti così visibili tra parti delle stesse immagini di sfondo, prova a utilizzare questa impostazione per eliminare di quello effetto indesiderato. ATTENZIONE! Questa ottimizzazione della qualità di solito rallenta sostanzialmente la conversione, quindi, per favore, usa questa opzione solo quando è veramente necessario. |

### Guarda anche

* class [UnifiedSaveOptions](../unifiedsaveoptions)
* interface [IPipelineOptions](../ipipelineoptions)
* spazio dei nomi [Aspose.Pdf](../../aspose.pdf)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
