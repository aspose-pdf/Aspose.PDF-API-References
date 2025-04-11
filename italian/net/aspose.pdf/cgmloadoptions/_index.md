---
title: Class CgmLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.CgmLoadOptions class. Contains options for loading/importing CGM file into pdf document
type: docs
weight: 3010
url: /it/net/aspose.pdf/cgmloadoptions/
---
## Classe CgmLoadOptions

Contiene opzioni per il caricamento/importazione di file CGM in un documento pdf.

```csharp
public sealed class CgmLoadOptions : LoadOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [CgmLoadOptions](cgmloadoptions/#constructor)() | Crea opzioni di caricamento predefinite per convertire un file CGM in un documento pdf. Dimensione predefinita della pagina pdf - A4 300dpi 2480 X 3508. |
| [CgmLoadOptions](cgmloadoptions/#constructor_1)(SizeF) | Crea opzioni di caricamento con !:pageSize definito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Ottiene o imposta un flag per disabilitare eventuali restrizioni di licenza per tutti i font durante il caricamento del file. Quando `true`, consente di eseguire operazioni con font che sono vietate da una licenza di questo font, ad esempio consente di incorporare un font in un documento PDF anche se le regole di licenza disabilitano l'incorporamento per questo font. Di default `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Rappresenta il formato del file che [`LoadOptions`](../loadoptions/) descrive. |
| [PageSize](../../aspose.pdf/cgmloadoptions/pagesize/) { get; } | Ottiene o imposta la dimensione della pagina di output per l'importazione. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback per gestire eventuali avvisi generati. Il WarningHandler restituisce un elemento dell'enumerazione ReturnAction che specifica se Continuare o Abortire. Continuare è l'azione predefinita e l'operazione di caricamento continua, tuttavia l'utente può anche restituire Abortire, nel qual caso l'operazione di caricamento dovrebbe cessare. |

### Vedi Anche

* classe [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)