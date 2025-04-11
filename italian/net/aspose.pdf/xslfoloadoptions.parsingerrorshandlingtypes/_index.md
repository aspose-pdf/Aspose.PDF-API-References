---
title: Enum XslFoLoadOptions.ParsingErrorsHandlingTypes
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XslFoLoadOptionsParsingErrorsHandlingTypes enum. Il documento XSLFO sorgente può contenere errori di formattazione. Questo enum enumera le possibili strategie di gestione di tali errori di formattazione
type: docs
weight: 11540
url: /it/net/aspose.pdf/xslfoloadoptions.parsingerrorshandlingtypes/
---
## XslFoLoadOptions.ParsingErrorsHandlingTypes enumeration

Il documento XSLFO sorgente può contenere errori di formattazione. Questo enum enumera le possibili strategie di gestione di tali errori di formattazione

```csharp
public enum ParsingErrorsHandlingTypes
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| TryIgnore | `0` | In questo caso il convertitore sarà istruito a tentare di procedere con la conversione e ignorare gli errori di formattazione trovati. In questo caso il successo non è garantito, problemi seri possono verificarsi successivamente nel convertitore, e in tal caso verrà sollevata un'eccezione con l'elenco degli errori di formattazione trovati. |
| ThrowExceptionImmediately | `1` | In questo caso la conversione verrà interrotta immediatamente e verrà sollevata un'eccezione immediatamente dopo aver rilevato il primo errore di formattazione |
| InvokeCustomHandler | `2` | Questo è il metodo più agile - il codice personalizzato deve fornire (nella proprietà WarningCallback) un gestore speciale che verrà chiamato quando viene rilevato un errore di formattazione. Quel gestore può ad esempio registrare o contare gli errori ecc. e fornirà una decisione su se il processo può continuare per questo o quel errore. |

### See Also

* class [XslFoLoadOptions](../xslfoloadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)