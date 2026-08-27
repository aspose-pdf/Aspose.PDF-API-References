---
title: "Enum XslFoLoadOptions.ParsingErrorsHandlingTypes"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Enum Aspose.Pdf.XslFoLoadOptionsParsingErrorsHandlingTypes. Il documento XSLFO di origine può contenere errori di formattazione. Questo enum elenca le possibili strategie di gestione di tali errori di formattazione"
type: docs
weight: 11730
url: /it/net/aspose.pdf/xslfoloadoptions.parsingerrorshandlingtypes/
---
## XslFoLoadOptions.ParsingErrorsHandlingTypes enumeration

Il documento XSLFO di origine può contenere errori di formattazione. Questo enum elenca le possibili strategie di gestione di tali errori di formattazione

```csharp
public enum ParsingErrorsHandlingTypes
```

### Valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| TryIgnore | `0` | In questo caso il convertitore sarà istruito a provare a procedere con la conversione e ignorare gli errori di formattazione trovati. In questo caso il successo non è garantito, problemi seri possono verificarsi più tardi nel convertitore, e in tal caso verrà sollevata un'eccezione con l'elenco degli errori di formattazione trovati. |
| ThrowExceptionImmediately | `1` | In questo caso la conversione sarà interrotta immediatamente e verrà sollevata un'eccezione subito dopo il rilevamento del primo errore di formattazione. |
| InvokeCustomHandler | `2` | Questo è il metodo più agile - il codice personalizzato deve fornire (in WarningCallback property) un gestore speciale che verrà chiamato quando viene rilevato un errore di formattazione. Tale gestore può, ad es., registrare o contare gli errori, ecc., e fornirà la decisione se l'elaborazione può continuare per questo o quello errore. |

### Vedi anche

* class [XslFoLoadOptions](../xslfoloadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


