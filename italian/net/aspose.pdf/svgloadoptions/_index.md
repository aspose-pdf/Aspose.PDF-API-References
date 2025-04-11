---
title: Class SvgLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.SvgLoadOptions. Rappresenta le opzioni per il caricamento/importazione di file SVG nel documento pdf
type: docs
weight: 10210
url: /it/net/aspose.pdf/svgloadoptions/
---
## Classe SvgLoadOptions

Rappresenta le opzioni per il caricamento/importazione di file SVG nel documento pdf.

```csharp
public sealed class SvgLoadOptions : LoadOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SvgLoadOptions](svgloadoptions/)() | Il costruttore predefinito. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AdjustPageSize](../../aspose.pdf/svgloadoptions/adjustpagesize/) { get; set; } | Adatta la dimensione della pagina pdf alla dimensione svg |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Ottiene o imposta un flag per disabilitare eventuali restrizioni di licenza per tutti i caratteri durante il caricamento del file. Quando `true`, consente di eseguire operazioni con caratteri che sono vietate da una licenza di questo carattere, ad esempio consente di incorporare un carattere in un documento PDF anche se le regole di licenza disabilitano l'incorporamento per questo carattere. Per impostazione predefinita `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Rappresenta il formato del file che [`LoadOptions`](../loadoptions/) descrive. |
| [PageInfo](../../aspose.pdf/svgloadoptions/pageinfo/) { get; set; } | Ottiene o imposta le informazioni sulla pagina che devono essere applicate durante il caricamento del documento. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback per gestire eventuali avvisi generati. Il WarningHandler restituisce un elemento dell'enumerazione ReturnAction che specifica se Continuare o Abortire. Continuare è l'azione predefinita e l'operazione di caricamento continua, tuttavia l'utente può anche restituire Abortire, nel qual caso l'operazione di caricamento dovrebbe cessare. |

## Campi

| Nome | Descrizione |
| --- | --- |
| [ConversionEngine](../../aspose.pdf/svgloadoptions/conversionengine/) | Consente di selezionare il motore di conversione che sarà in uso durante la conversione. Attualmente, il nuovo motore è in fase di test B, quindi questo valore per impostazione predefinita è impostato su ConversionEngines.LegacyEngine |

### Vedi Anche

* classe [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)