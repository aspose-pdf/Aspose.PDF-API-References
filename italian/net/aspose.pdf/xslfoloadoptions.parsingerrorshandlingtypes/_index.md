---
title: XslFoLoadOptions.ParsingErrorsHandlingTypes
second_title: Aspose.PDF per .NET API Reference
description: Il documento XSLFO di origine può contenere errori di formattazione. Questo enum enumera le possibili strategie di gestione di tali errori di formattazione
type: docs
weight: 7590
url: /it/net/aspose.pdf/xslfoloadoptions.parsingerrorshandlingtypes/
---
## XslFoLoadOptions.ParsingErrorsHandlingTypes enumeration

Il documento XSLFO di origine può contenere errori di formattazione. Questo enum enumera le possibili strategie di gestione di tali errori di formattazione

```csharp
public enum ParsingErrorsHandlingTypes
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| TryIgnore | `0` | In questo caso al convertitore verrà richiesto di provare a procedere con la conversione e ignorare gli errori di formattazione trovati. In questo caso il successo non è garantito, problemi seri possono verificarsi in seguito nel convertitore, e in caso di risucchio verrà generata un'eccezione con l'elenco di formattazione trovata errori. |
| ThrowExceptionImmediately | `1` | In questo caso la conversione verrà interrotta immediatamente e l'eccezione verrà generata immediatamente dopo aver rilevato del primo errore di formattazione |
| InvokeCustomHandler | `2` | Questo è il metodo più agile: il codice personalizzato deve fornire (nella proprietà WarningCallback) il gestore special che verrà chiamato quando viene rilevato un errore di formattazione. Quel gestore può registrare o contare gli errori ecc. e fornirà la decisione se l'elaborazione può essere continuata per questo o quell'errore. |

### Guarda anche

* class [XslFoLoadOptions](../xslfoloadoptions)
* spazio dei nomi [Aspose.Pdf](../../aspose.pdf)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
