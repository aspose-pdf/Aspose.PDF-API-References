---
title: Class PsLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: La classe Aspose.Pdf.PsLoadOptions. Rappresenta le opzioni per il caricamento/importazione di un file .mht in un documento pdf
type: docs
weight: 9730
url: /it/net/aspose.pdf/psloadoptions/
---
## Classe PsLoadOptions

Rappresenta le opzioni per il caricamento/importazione di un file .mht in un documento pdf.

```csharp
public sealed class PsLoadOptions : LoadOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PsLoadOptions](psloadoptions/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Ottiene o imposta un flag per disabilitare eventuali restrizioni di licenza per tutti i caratteri durante il caricamento del file. Quando `true`, consente di eseguire operazioni con caratteri che sono vietate da una licenza di questo carattere, ad esempio consente di incorporare un carattere in un documento PDF anche se le regole di licenza disabilitano l'incorporamento per questo carattere. Per impostazione predefinita `false`. |
| [FontsFolders](../../aspose.pdf/psloadoptions/fontsfolders/) { get; set; } | Ottiene o imposta i percorsi delle cartelle dei caratteri. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Rappresenta il formato del file che [`LoadOptions`](../loadoptions/) descrive. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback per gestire eventuali avvisi generati. Il WarningHandler restituisce un elemento dell'enum ReturnAction che specifica se Continuare o Abortire. Continuare è l'azione predefinita e l'operazione di caricamento continua, tuttavia l'utente può anche restituire Abortire, nel qual caso l'operazione di caricamento dovrebbe cessare. |

### Vedi Anche

* classe [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)