---
title: "Aspose::Pdf::HeadingRecognitionStrategy enum"
linktitle: "HeadingRecognitionStrategy"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::HeadingRecognitionStrategy enum. Representerar typer av rubrikigenkänningsstrategier i C++."
type: docs
weight: 23900
url: /sv/cpp/aspose.pdf/headingrecognitionstrategy/
---
## HeadingRecognitionStrategy enum


Representerar typer av rubrikigenkänningsstrategier.

```cpp
enum class HeadingRecognitionStrategy
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| Outlines | 0 | Representerar rubrikigenkänningsstrategin med hjälp av Outlines. |
| Heuristic | 1 | Representerar rubrikigenkänningsstrategin med hjälp av heuristiska regler och teckenstorleksstatistik. |
| Auto | 2 | Tillhandahåller ett automatiskt val av rubrikigenkänningsstrategi. Detta är standardalternativet. Om dokumentet innehåller bokmärken kommer [Outlines](../outlines/)-strategin att väljas, annars [Heuristic](./). |
| Ingen | 3 | Känn inte igen rubriker. Detta alternativ kan vara användbart i komplext formaterade dokument. |

## Se även

* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
