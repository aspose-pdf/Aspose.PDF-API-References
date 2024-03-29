---
title: SvgLoadOptions
second_title: Aspose.PDF per .NET API Reference
description: Rappresenta le opzioni per caricare/importare file SVG in un documento pdf.
type: docs
weight: 6430
url: /it/net/aspose.pdf/svgloadoptions/
---
## SvgLoadOptions class

Rappresenta le opzioni per caricare/importare file SVG in un documento pdf.

```csharp
public sealed class SvgLoadOptions : LoadOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SvgLoadOptions](svgloadoptions)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AdjustPageSize](../../aspose.pdf/svgloadoptions/adjustpagesize) { get; set; } | Dimensione pagina pdf Adust in formato svg |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat) { get; } | Rappresenta il formato di file che[`LoadOptions`](../loadoptions) descrive. |
| [PageInfo](../../aspose.pdf/svgloadoptions/pageinfo) { get; set; } | Ottiene o imposta le informazioni sulla pagina che devono essere applicate durante il caricamento del documento. NOTA che questo parametro funziona solo quando ConversionEngine == ConversionEngines.NewEngine |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler) { get; set; } | Richiamata per gestire eventuali avvisi generati. WarningHandler restituisce l'elemento enum ReturnAction specificando Continue o Abort. Continua è l'azione predefinita e l'operazione di caricamento continua, tuttavia l'utente può anche restituire Interrompi, nel qual caso l'operazione di caricamento dovrebbe cessare. |

## Campi

| Nome | Descrizione |
| --- | --- |
| [ConversionEngine](../../aspose.pdf/svgloadoptions/conversionengine) | Consente di selezionare il motore di conversione che verrà utilizzato durante la conversione. Attualmente il nuovo motore è in fase di test B, quindi questo valore è impostato per impostazione predefinita su ConversionEngines.LegacyEngine |

### Guarda anche

* class [LoadOptions](../loadoptions)
* spazio dei nomi [Aspose.Pdf](../../aspose.pdf)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
