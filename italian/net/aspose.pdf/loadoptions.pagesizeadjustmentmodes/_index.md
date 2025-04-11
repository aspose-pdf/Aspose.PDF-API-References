---
title: Enum LoadOptions.PageSizeAdjustmentModes
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LoadOptionsPageSizeAdjustmentModes enum. ATTENTION The feature implemented but did not put yet to public API since blocker issue in OSHARED layer revealed for sample document. Represents mode of usage of page size during conversion. Formats like HTML EPUB etc usually have float design so it allows to fit required pagesize. But sometimes content has specifies horizontal positions or size that does not allow put content into required page size. In such case we can define what should be done in this case i.e when size of content does not fit required initial page size of result PDF document
type: docs
weight: 6140
url: /it/net/aspose.pdf/loadoptions.pagesizeadjustmentmodes/
---
## LoadOptions.PageSizeAdjustmentModes enumeration

ATTENZIONE! La funzionalità è stata implementata ma non è ancora stata messa a disposizione dell'API pubblica poiché è emerso un problema bloccante nel layer OSHARED per il documento di esempio. Rappresenta la modalità di utilizzo della dimensione della pagina durante la conversione. Formati (come HTML, EPUB ecc.), di solito hanno un design fluttuante, quindi, consentono di adattare la dimensione della pagina richiesta. Ma a volte il contenuto ha posizioni orizzontali specifiche o dimensioni che non consentono di inserire il contenuto nella dimensione della pagina richiesta. In tal caso possiamo definire cosa dovrebbe essere fatto in questo caso (cioè quando la dimensione del contenuto non si adatta alla dimensione iniziale della pagina richiesta del documento PDF risultante).

```csharp
public enum PageSizeAdjustmentModes
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| NoAjustmentAllwaysUsePredefinedSize | `0` | In questa modalità le pagine risultanti avranno la dimensione della pagina richiesta definita in LoadOptions, indipendentemente dal fatto che il contenuto dopo la conversione esca o meno dai confini della pagina. |
| EnlargeRequiredViewportWidthAndDoConversionAgain | `1` | Questa modalità definisce un comportamento del genere: dopo aver ottenuto il risultato della conversione e rilevato che alcuni contenuti sono stati troncati, la larghezza del portview viene ampliata per adattarsi al contenuto e la conversione viene ripetuta. Questa modalità consente di ottenere meno pagine nel risultato in tal caso, ma richiede un rendering ripetuto (e quindi più tempo di elaborazione). |

### Vedi Anche

* classe [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)