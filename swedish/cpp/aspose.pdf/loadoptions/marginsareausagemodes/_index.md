---
title: "Aspose::Pdf::LoadOptions::MarginsAreaUsageModes enum"
linktitle: "MarginsAreaUsageModes"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::LoadOptions::MarginsAreaUsageModes enum. Representerar hur marginalområdet används under konvertering (som HTML, EPUB etc.), definierar behandlingen av instruktioner i det importerade formatet relaterade till marginalanvändning i C++."
type: docs
weight: 800
url: /sv/cpp/aspose.pdf/loadoptions/marginsareausagemodes/
---
## MarginsAreaUsageModes enum


Representerar läge för användning av marginalområdet under konvertering (som HTML, EPUB etc), definierar behandlingen av instruktioner från importerat format relaterade till användning av marginaler.

```cpp
enum class MarginsAreaUsageModes
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| PutContentOnMarginAreaIfNecessary | 0 | I det här läget följer konverteraren formatet för det importerade dokumentet (t.ex. CSS för importerad HTML) när marginalområdet används. Så, om formatet för det importerade dokumentet kräver användning av marginalområdet för rendering, kommer konverteraren att tillåta det. |
| NeverPutContentOnMarginArea | 1 | Detta läge förbjuder strikt användning av marginalområdet, så konverteraren kommer aldrig att använda marginalområdet för rendering, även om CSS eller formatet för källdokumentet tillåter eller kräver det. |

## Se även

* Class [LoadOptions](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
