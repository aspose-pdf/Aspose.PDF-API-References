---
title: "Enum LoadOptions.PageSizeAdjustmentModes"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Aspose.Pdf.LoadOptionsPageSizeAdjustmentModes enum. ATTENTION La funzionalità è stata implementata ma non è ancora stata resa disponibile nell'API pubblica a causa di un problema bloccante nello strato OSHARED rilevato per il documento di esempio. Rappresenta la modalità di utilizzo della dimensione della pagina durante la conversione. Formati come HTML, EPUB, ecc. solitamente hanno un layout fluttuante, quindi consentono di adattare la dimensione della pagina richiesta. Tuttavia a volte il contenuto specifica posizioni orizzontali o dimensioni che non permettono di inserire il contenuto nella dimensione della pagina richiesta. In tal caso possiamo definire cosa fare, cioè quando la dimensione del contenuto non si adatta alla dimensione iniziale della pagina richiesta del documento PDF risultante."
type: docs
weight: 6280
url: /it/net/aspose.pdf/loadoptions.pagesizeadjustmentmodes/
---
## LoadOptions.PageSizeAdjustmentModes enumeration

ATTENTION! La funzionalità è stata implementata ma non è ancora stata resa disponibile nell'API pubblica a causa di un problema bloccante nello strato OSHARED rilevato per il documento di esempio. Rappresenta la modalità di utilizzo della dimensione della pagina durante la conversione. I formati (come HTML, EPUB, ecc.), solitamente hanno un layout fluttuante, quindi consentono di adattare la dimensione della pagina richiesta. Tuttavia a volte il contenuto specifica posizioni orizzontali o dimensioni che non permettono di inserire il contenuto nella dimensione della pagina richiesta. In tal caso possiamo definire cosa fare (cioè quando la dimensione del contenuto non si adatta alla dimensione iniziale della pagina richiesta del documento PDF risultante).

```csharp
public enum PageSizeAdjustmentModes
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| NoAjustmentAllwaysUsePredefinedSize | `0` | In questa modalità le pagine risultanti avranno la dimensione della pagina richiesta definita in LoadOptions, indipendentemente dal fatto che il contenuto dopo la conversione esca o meno dai margini della pagina. |
| EnlargeRequiredViewportWidthAndDoConversionAgain | `1` | Questa modalità definisce tale comportamento: dopo aver ottenuto il risultato della conversione e aver rilevato che parte del contenuto è stata troncata, la larghezza della visualizzazione viene ingrandita per adattare il contenuto e la conversione viene ripetuta. Questa modalità consente di ottenere meno pagine nel risultato in tali casi, ma richiede un rendering ripetuto (e quindi più tempo di elaborazione). |

### Vedi anche

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


