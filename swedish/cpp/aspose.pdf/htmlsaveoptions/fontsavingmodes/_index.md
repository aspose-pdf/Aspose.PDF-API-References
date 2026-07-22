---
title: "Aspose::Pdf::HtmlSaveOptions::FontSavingModes‑enum"
linktitle: "FontSavingModes"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::HtmlSaveOptions::FontSavingModes‑enum. Enumererar lägen som kan användas för att spara teckensnitt som refereras i den sparade PDF‑filen i C++."
type: docs
weight: 5300
url: /sv/cpp/aspose.pdf/htmlsaveoptions/fontsavingmodes/
---
## FontSavingModes enum


Enumererar lägen som kan användas för att spara teckensnitt som refereras i sparad PDF.

```cpp
enum class FontSavingModes
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| AlwaysSaveAsWOFF | 0 | Alla refererade teckensnitt kommer att sparas och refereras som WOFF‑teckensnitt. |
| AlwaysSaveAsTTF | 1 | Alla refererade typsnitt kommer att sparas och refereras som TTF-typsnitt. |
| AlwaysSaveAsEOT | 2 | Alla refererade typsnitt kommer att sparas och refereras som EOT-typsnitt. |
| SaveInAllFormats | 3 | Alla refererade typsnitt kommer att sparas (och refereras i CSS) som 3 oberoende filer: EOT, TTH, WOFF. Det ökar storleken på utdata men gör utdata lämplig för överväldigande majoritet av webbläsare. |
| DontSave | 4 | Alla refererade typsnitt kommer inte att sparas. |

## Se även

* Class [HtmlSaveOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
