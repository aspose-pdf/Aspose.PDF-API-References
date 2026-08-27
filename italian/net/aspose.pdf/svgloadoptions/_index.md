---
title: "Classe SvgLoadOptions"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Aspose.Pdf.SvgLoadOptions class. Rappresenta le opzioni per il caricamento/importazione di file SVG in un documento pdf"
type: docs
weight: 10390
url: /it/net/aspose.pdf/svgloadoptions/
---
## SvgLoadOptions class

Rappresenta le opzioni per caricare/importare un file SVG in un documento pdf.

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
| [AdjustPageSize](../../aspose.pdf/svgloadoptions/adjustpagesize/) { get; set; } | Adatta la dimensione della pagina pdf alla dimensione SVG |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Ottiene o imposta il flag per disabilitare qualsiasi restrizione di licenza per tutti i font durante il caricamento del file. Quando `true`, consente di eseguire operazioni con font proibiti da una licenza di quel font, ad esempio consente di incorporare un font in un documento PDF anche se le regole di licenza disabilitano l'incorporamento per quel font. Per impostazione predefinita `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Rappresenta il formato file descritto da [`LoadOptions`](../loadoptions/). |
| [PageInfo](../../aspose.pdf/svgloadoptions/pageinfo/) { get; set; } | Ottiene o imposta le informazioni della pagina che devono essere applicate durante il caricamento del documento. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback per gestire eventuali avvisi generati. Il WarningHandler restituisce l'elemento enum ReturnAction che specifica Continue o Abort. Continue è l'azione predefinita e l'operazione Load continua, tuttavia l'utente può anche restituire Abort, nel qual caso l'operazione Load deve cessare. |

## Campi

| Nome | Descrizione |
| --- | --- |
| [ConversionEngine](../../aspose.pdf/svgloadoptions/conversionengine/) | Consente di selezionare il motore di conversione da utilizzare durante la conversione. Attualmente il nuovo motore è in fase di B-testing, quindi questo valore è impostato per impostazione predefinita su ConversionEngines.LegacyEngine |

### Vedi anche

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


