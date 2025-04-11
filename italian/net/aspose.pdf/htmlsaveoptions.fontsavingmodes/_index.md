---
title: Enum HtmlSaveOptions.FontSavingModes
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.OpzioniDiSalvataggioHtml.ModalitàDiSalvataggioFonti enum. Elenco di modalità utilizzabili per il salvataggio delle fonti referenziati nelle PDF salvate.
type: docs
weight: 5630
url: /it/net/aspose.pdf/htmlsaveoptions.fontsavingmodes/
---
## HtmlSaveOptions.FontSavingModes enumeration

Enumera le modalità che possono essere utilizzate per il salvataggio dei font referenziati nel PDF salvato.

```csharp
public enum FontSavingModes
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| AlwaysSaveAsWOFF | `0` | Tutti i font referenziati saranno salvati e referenziati come font WOFF. |
| AlwaysSaveAsTTF | `1` | Tutti i font referenziati saranno salvati e referenziati come font TTF. |
| AlwaysSaveAsEOT | `2` | Tutti i font referenziati saranno salvati e referenziati come font EOT. |
| SaveInAllFormats | `3` | Tutti i font referenziati saranno salvati (e referenziati in CSS) come 3 file indipendenti: EOT, TTH, WOFF. Aumenta la dimensione dei dati di output ma rende l'output adatto per la stragrande maggioranza dei browser web. |
| DontSave | `4` | Tutti i font referenziati non saranno salvati. |

### See Also

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)