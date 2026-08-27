---
title: "XslFoLoadOptions.ParsingErrorsHandlingTypes"
linktitle: "XslFoLoadOptions.ParsingErrorsHandlingTypes"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Il documento XSLFO di origine può contenere errori di formattazione. Questo enum elenca le possibili strategie di gestione di tali errori di formattazione."
type: docs
weight: 5790
url: /it/java/com.aspose.pdf/xslfoloadoptions.parsingerrorshandlingtypes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.XslFoLoadOptions.ParsingErrorsHandlingTypes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.XslFoLoadOptions.ParsingErrorsHandlingTypes, com.aspose.ms.System.Enum, com.aspose.pdf.XslFoLoadOptions.ParsingErrorsHandlingTypes

```
public static final class XslFoLoadOptions.ParsingErrorsHandlingTypes extends com.aspose.ms.System.Enum
```

Il documento XSLFO di origine può contenere errori di formattazione. Questo enum elenca le possibili strategie di gestione di tali errori di formattazione.

## Campi

| Campo | Descrizione |
| --- | --- |
| [InvokeCustomHandler](#InvokeCustomHandler) | Questo è il metodo più agile - il codice personalizzato deve fornire (nella proprietà WarningCallback) un gestore speciale che verrà chiamato quando viene rilevato un errore di formattazione. Tale gestore può, ad es., registrare o contare gli errori ecc. e fornirà la decisione se l'elaborazione può continuare per questo o quello errore. |
| [ThrowExceptionImmediately](#ThrowExceptionImmediately) | In questo caso la conversione verrà interrotta immediatamente e verrà sollevata un'eccezione subito dopo il rilevamento del primo errore di formattazione. |
| [TryIgnore](#TryIgnore) | In questo caso il convertitore sarà istruito a provare a proseguire con la conversione e ignorare gli errori di formattazione trovati. In questo caso il successo non è garantito, problemi seri possono verificarsi più tardi nel convertitore, e in tal caso verrà sollevata un'eccezione con l'elenco degli errori di formattazione trovati. |

### InvokeCustomHandler {#InvokeCustomHandler}
```
public static final int InvokeCustomHandler
```

Questo è il metodo più agile - il codice personalizzato deve fornire (nella proprietà WarningCallback) un gestore speciale che verrà chiamato quando viene rilevato un errore di formattazione. Tale gestore può, ad es., registrare o contare gli errori ecc. e fornirà la decisione se l'elaborazione può continuare per questo o quello errore.

### ThrowExceptionImmediately {#ThrowExceptionImmediately}
```
public static final int ThrowExceptionImmediately
```

In questo caso la conversione verrà interrotta immediatamente e verrà sollevata un'eccezione subito dopo il rilevamento del primo errore di formattazione.

### TryIgnore {#TryIgnore}
```
public static final int TryIgnore
```

In questo caso il convertitore sarà istruito a provare a proseguire con la conversione e ignorare gli errori di formattazione trovati. In questo caso il successo non è garantito, problemi seri possono verificarsi più tardi nel convertitore, e in tal caso verrà sollevata un'eccezione con l'elenco degli errori di formattazione trovati.
