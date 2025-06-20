---
title: Enum HtmlSaveOptions.FontSavingModes
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlSaveOptionsFontSavingModes enum. Enumerates modes that can be used for saving of fonts referenced in saved PDF
type: docs
weight: 5760
url: /net/aspose.pdf/htmlsaveoptions.fontsavingmodes/
---
## HtmlSaveOptions.FontSavingModes enumeration

Enumerates modes that can be used for saving of fonts referenced in saved PDF.

```csharp
public enum FontSavingModes
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| AlwaysSaveAsWOFF | `0` | All referenced fonts will be saved and referenced as WOFF-fonts. |
| AlwaysSaveAsTTF | `1` | All referenced fonts will be saved and referenced as TTF-fonts. |
| AlwaysSaveAsEOT | `2` | All referenced fonts will be saved and referenced as EOT-fonts. |
| SaveInAllFormats | `3` | All referenced fonts will be saved (and referenced in CSS) as 3 independent files : EOT, TTH, WOFF. It increases size of output data but makes output suitable for overwhelming majority of web browsers . |
| DontSave | `4` | All referenced fonts will not be saved. |

### See Also

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


