---
title: "Classe DjvuLoadOptions"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Aspose.Pdf.DjvuLoadOptions class. La classe descrive le opzioni di caricamento DJVU"
type: docs
weight: 3860
url: /it/net/aspose.pdf/djvuloadoptions/
---
## DjvuLoadOptions class

La classe descrive le opzioni di caricamento DJVU.

```csharp
public class DjvuLoadOptions : LoadOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [DjvuLoadOptions](djvuloadoptions/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Ottiene o imposta il flag per disabilitare qualsiasi restrizione di licenza per tutti i font durante il caricamento del file. Quando `true`, consente di eseguire operazioni con font proibiti da una licenza di quel font, ad esempio consente di incorporare un font in un documento PDF anche se le regole di licenza disabilitano l'incorporamento per quel font. Per impostazione predefinita `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Rappresenta il formato file descritto da [`LoadOptions`](../loadoptions/). |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback per gestire eventuali avvisi generati. Il WarningHandler restituisce l'elemento enum ReturnAction che specifica Continue o Abort. Continue è l'azione predefinita e l'operazione Load continua, tuttavia l'utente può anche restituire Abort, nel qual caso l'operazione Load deve cessare. |

### Vedi anche

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


