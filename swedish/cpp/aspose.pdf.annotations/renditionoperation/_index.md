---
title: "Aspose::Pdf::Annotations::RenditionOperation enum"
linktitle: "RenditionOperation"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Annotations::RenditionOperation enum. Operationen som ska utföras när åtgärden utlöses i C++."
type: docs
weight: 14700
url: /sv/cpp/aspose.pdf.annotations/renditionoperation/
---
## RenditionOperation enum


Operationen som ska utföras när åtgärden utlöses.

```cpp
enum class RenditionOperation
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| PlayStop | 0 | Om ingen rendition är associerad med annoteringen, spela den angivna renditionen och associera den med annoteringen. Om en rendition redan är associerad med annoteringen ska den stoppas, och den nya renditionen ska associeras med annoteringen. |
| Stop | 1 | Stoppa alla renditioner som spelas i samband med annoteringen. |
| Pause | 2 | Pausa alla renditioner som spelas i samband med annoteringen. |
| Återuppta | 3 | Återuppta alla renditioner som spelas i samband med annoteringen. |
| PlayResume | 4 | Spela den angivna renditionen och associera den med annoteringen. Om en rendition redan är associerad med annoteringen, återuppta renditionen om den är pausad. |
| Odefinierad | -1 | Operationen är inte definierad. |

## Se även

* Namespace [Aspose::Pdf::Annotations](../)
* Library [Aspose.PDF for C++](../../)
