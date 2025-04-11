---
title: Enum HtmlSaveOptions.FontSavingModes
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlSaveOptionsFontSavingModes Enum. Enumeriert Modi, die zum Speichern von Schriftarten verwendet werden können, die in gespeicherten PDFs referenziert werden.
type: docs
weight: 5630
url: /de/net/aspose.pdf/htmlsaveoptions.fontsavingmodes/
---
## HtmlSaveOptions.FontSavingModes Enumeration

Enumeriert Modi, die zum Speichern von Schriftarten verwendet werden können, die in gespeicherten PDFs referenziert werden.

```csharp
public enum FontSavingModes
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| AlwaysSaveAsWOFF | `0` | Alle referenzierten Schriftarten werden gespeichert und als WOFF-Schriftarten referenziert. |
| AlwaysSaveAsTTF | `1` | Alle referenzierten Schriftarten werden gespeichert und als TTF-Schriftarten referenziert. |
| AlwaysSaveAsEOT | `2` | Alle referenzierten Schriftarten werden gespeichert und als EOT-Schriftarten referenziert. |
| SaveInAllFormats | `3` | Alle referenzierten Schriftarten werden gespeichert (und in CSS referenziert) als 3 unabhängige Dateien: EOT, TTH, WOFF. Dies erhöht die Größe der Ausgabedaten, macht die Ausgabe jedoch für die überwältigende Mehrheit der Webbrowser geeignet. |
| DontSave | `4` | Alle referenzierten Schriftarten werden nicht gespeichert. |

### Siehe auch

* Klasse [HtmlSaveOptions](../htmlsaveoptions/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)