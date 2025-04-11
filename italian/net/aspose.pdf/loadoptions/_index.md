---
title: Class LoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.LoadOptions. Il tipo LoadOptions mantiene un livello di astrazione sulle singole opzioni di caricamento
type: docs
weight: 6120
url: /it/net/aspose.pdf/loadoptions/
---
## Classe LoadOptions

Il tipo LoadOptions mantiene un livello di astrazione sulle singole opzioni di caricamento

```csharp
public abstract class LoadOptions
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Ottiene o imposta un flag per disabilitare eventuali restrizioni di licenza per tutti i font durante il caricamento del file. Quando `true`, consente di eseguire operazioni con font che sono vietate da una licenza di questo font, ad esempio consente di incorporare un font in un documento PDF anche se le regole di licenza disabilitano l'incorporamento per questo font. Per impostazione predefinita `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Rappresenta il formato del file che `LoadOptions` descrive. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback per gestire eventuali avvisi generati. Il WarningHandler restituisce un elemento dell'enumerazione ReturnAction che specifica se Continuare o Abortire. Continuare è l'azione predefinita e l'operazione di caricamento continua, tuttavia l'utente può anche restituire Abortire, nel qual caso l'operazione di caricamento dovrebbe cessare. |

### Vedi Anche

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)