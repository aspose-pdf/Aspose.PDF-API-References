---
title: Aspose::Pdf::HtmlSaveOptions::FontSavingModes enum
linktitle: FontSavingModes
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::HtmlSaveOptions::FontSavingModes enum. Enumerates modes that can be used for saving of fonts referenced in saved PDF in C++.'
type: docs
weight: 5300
url: /cpp/aspose.pdf/htmlsaveoptions/fontsavingmodes/
---
## FontSavingModes enum


Enumerates modes that can be used for saving of fonts referenced in saved PDF.

```cpp
enum class FontSavingModes
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| AlwaysSaveAsWOFF | 0 | All referenced fonts will be saved and referenced as WOFF-fonts. |
| AlwaysSaveAsTTF | 1 | All referenced fonts will be saved and referenced as TTF-fonts. |
| AlwaysSaveAsEOT | 2 | All referenced fonts will be saved and referenced as EOT-fonts. |
| SaveInAllFormats | 3 | All referenced fonts will be saved (and referenced in CSS) as 3 independent files : EOT, TTH, WOFF. It increases size of output data but makes output suitable for overwhelming majority of web browsers . |
| DontSave | 4 | All referenced fonts will not be saved. |

## See Also

* Class [HtmlSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
