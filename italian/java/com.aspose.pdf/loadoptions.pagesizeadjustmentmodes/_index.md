---
title: "LoadOptions.PageSizeAdjustmentModes"
linktitle: "LoadOptions.PageSizeAdjustmentModes"
second_title: "Riferimento API Aspose.PDF per Java"
description: "ATTENZIONE! La funzionalità è stata implementata ma non è ancora stata inserita nell'API pubblica poiché è stato rilevato un problema bloccante nello strato OSHARED per il documento di esempio. Rappresenta la modalità di utilizzo della dimensione della pagina."
type: docs
weight: 2810
url: /it/java/com.aspose.pdf/loadoptions.pagesizeadjustmentmodes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.LoadOptions.PageSizeAdjustmentModes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.LoadOptions.PageSizeAdjustmentModes, com.aspose.ms.System.Enum, com.aspose.pdf.LoadOptions.PageSizeAdjustmentModes

```
public static final class LoadOptions.PageSizeAdjustmentModes extends com.aspose.ms.System.Enum
```

ATTENZIONE! La funzionalità è implementata ma non è ancora stata resa disponibile nell'API pubblica poiché è stato riscontrato un problema bloccante nello strato OSHARED per il documento di esempio. Rappresenta la modalità di utilizzo della dimensione della pagina durante la conversione. I formati (come HTML, EPUB ecc.) solitamente hanno un layout fluido, quindi consentono di adattare la dimensione della pagina richiesta. Tuttavia a volte il contenuto specifica posizioni orizzontali o una dimensione che non permette di inserire il contenuto nella dimensione di pagina richiesta. In tal caso possiamo definire cosa fare in questa situazione (ad esempio quando la dimensione del contenuto non si adatta alla dimensione iniziale della pagina del documento PDF risultante).

## Campi

| Campo | Descrizione |
| --- | --- |
| [EnlargeRequiredViewportWidthAndDoConversionAgain](#EnlargeRequiredViewportWidthAndDoConversionAgain) | Questa modalità definisce tale comportamento: dopo aver ottenuto il risultato della conversione e aver rilevato il fatto che alcuni contenuti sono stati troncati, la larghezza della vista porta viene ingrandita per adattarsi al contenuto e la conversione viene ripetuta. Questa modalità consente di ottenere meno pagine nel risultato in tal caso, ma richiede il rendering ripetuto (e quindi più tempo di elaborazione). |
| [NoAjustmentAllwaysUsePredefinedSize](#NoAjustmentAllwaysUsePredefinedSize) | In questa modalità le pagine risultanti avranno la dimensione della pagina richiesta definita in LoadOptions, indipendentemente dal fatto che i contenuti dopo la conversione escano o meno dai limiti della pagina. |

### EnlargeRequiredViewportWidthAndDoConversionAgain {#EnlargeRequiredViewportWidthAndDoConversionAgain}
```
public static final int EnlargeRequiredViewportWidthAndDoConversionAgain
```

Questa modalità definisce tale comportamento: dopo aver ottenuto il risultato della conversione e aver rilevato il fatto che alcuni contenuti sono stati troncati, la larghezza della vista porta viene ingrandita per adattarsi al contenuto e la conversione viene ripetuta. Questa modalità consente di ottenere meno pagine nel risultato in tal caso, ma richiede il rendering ripetuto (e quindi più tempo di elaborazione).

### NoAjustmentAllwaysUsePredefinedSize {#NoAjustmentAllwaysUsePredefinedSize}
```
public static final int NoAjustmentAllwaysUsePredefinedSize
```

In questa modalità le pagine risultanti avranno la dimensione della pagina richiesta definita in LoadOptions, indipendentemente dal fatto che i contenuti dopo la conversione escano o meno dai limiti della pagina.
