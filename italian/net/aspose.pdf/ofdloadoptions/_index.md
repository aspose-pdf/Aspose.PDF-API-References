---
title: Class OfdLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.OfdLoadOptions. Opzioni di caricamento per il formato OFD
type: docs
weight: 7060
url: /it/net/aspose.pdf/ofdloadoptions/
---
## Classe OfdLoadOptions

Opzioni di caricamento per il formato OFD.

```csharp
public class OfdLoadOptions : LoadOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [OfdLoadOptions](ofdloadoptions/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Ottiene o imposta un flag per disabilitare eventuali restrizioni di licenza per tutti i font durante il caricamento del file. Quando `true`, consente di eseguire operazioni con font che sono vietate da una licenza di questo font, ad esempio consente di incorporare un font in un documento PDF anche se le regole di licenza disabilitano l'incorporamento per questo font. Per impostazione predefinita `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Rappresenta il formato del file che [`LoadOptions`](../loadoptions/) descrive. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback per gestire eventuali avvisi generati. Il WarningHandler restituisce un elemento dell'enumerazione ReturnAction che specifica se Continuare o Abortire. Continuare è l'azione predefinita e l'operazione di caricamento continua, tuttavia l'utente può anche restituire Abortire, nel qual caso l'operazione di caricamento dovrebbe cessare. |

### Vedi Anche

* classe [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)