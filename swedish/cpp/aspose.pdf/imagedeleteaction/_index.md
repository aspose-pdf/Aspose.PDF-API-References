---
title: "Aspose::Pdf::ImageDeleteAction enum"
linktitle: "ImageDeleteAction"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::ImageDeleteAction enum. Åtgärd som utförs med bildobjektet när bilden tas bort från samlingen. Om bildobjektet tas bort i C++."
type: docs
weight: 24500
url: /sv/cpp/aspose.pdf/imagedeleteaction/
---
## ImageDeleteAction enum


Åtgärd som utförs med bildobjektet när bilden tas bort från samlingen. Om bildobjektet tas bort.

```cpp
enum class ImageDeleteAction
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| KeepContents | 0 | [Image](../image/) kommer att tas bort från samlingen. Om sidinnehållet innehåller referenser till bilden kommer de inte att tas bort. [Document](../document/) kan bli ogiltigt. |
| None | 1 | [Image](../image/) kommer att tas bort från samlingen och från sidinnehållet, men bildobjektet kommer inte att raderas. Filstorleken kommer inte att minskas. |
| ForceDelete | 2 | [Image](../image/) kommer att tas bort från samlingen och bildobjektet kommer att tas bort från dokumentet. Om andra referenser till samma objekt finns kan dokumentet bli korrupt. |
| Check | 3 | [Image](../image/) kommer att tas bort från samlingen och bildobjektet tas bort endast om inga andra referenser till bilden finns från andra sidor. Detta kan kräva mer tid jämfört med alternativet ForceDelete. |

## Se även

* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
