---
title: "Aspose::Pdf::Text::TextEditOptions::ClippingPathsProcessingMode enum"
linktitle: "ClippingPathsProcessingMode"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Text::TextEditOptions::ClippingPathsProcessingMode enum. Klippvägsbearbetningslägen i C++."
type: docs
weight: 1600
url: /sv/cpp/aspose.pdf.text/texteditoptions/clippingpathsprocessingmode/
---
## ClippingPathsProcessingMode enum


Klippvägsbearbetningslägen.

```cpp
enum class ClippingPathsProcessingMode
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| KeepIntact | 0 | Behåller klippvägarna i den ursprungliga sidlayouten. (Standard) |
| Expand | 1 | Ursprunglig klippväg kommer att expanderas om redigerad text kräver mer utrymme. |
| Ta bort | 2 | Ursprunglig klippväg kommer att tas bort om redigerad text kräver mer utrymme. Varning: Eftersom klippvägar kan interagera med varandra kan borttagning leda till oväntade resultat i sidlayouten. |

## Se även

* Class [TextEditOptions](../)
* Namespace [Aspose::Pdf::Text](../../)
* Library [Aspose.PDF for C++](../../../)
