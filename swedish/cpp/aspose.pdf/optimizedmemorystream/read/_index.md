---
title: "Aspose::Pdf::OptimizedMemoryStream::Read method"
linktitle: "Read"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::OptimizedMemoryStream::Read method. När den åsidosätts i en avledd klass, läser den en sekvens av byte från den aktuella strömmen och förflyttar positionen i strömmen med antalet lästa byte i C++."
type: docs
weight: 1000
url: /sv/cpp/aspose.pdf/optimizedmemorystream/read/
---
## OptimizedMemoryStream::Read method


När den överskrivs i en avledd klass, läser den en sekvens av byte från den aktuella strömmen och förflyttar positionen i strömmen med antalet lästa byte.

```cpp
int32_t Aspose::Pdf::OptimizedMemoryStream::Read(const System::ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const System::ArrayPtr\<uint8_t\>\& | En array av byte. När denna metod återvänder, innehåller bufferten den specificerade byte‑arrayen med värdena |
| förskjutning | int32_t | Det nollbaserade byte‑offsetet där lagringen av data som lästs från den aktuella strömmen ska börja. |
| count | int32_t | Det maximala antalet byte som ska läsas från den aktuella strömmen. |

### ReturnValue

Det totala antalet byte som lästs in i bufferten. Detta kan vara mindre än det begärda antalet byte om så många byte för närvarande inte är tillgängliga, eller noll (0) om slutet på strömmen har nåtts.

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [OptimizedMemoryStream](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
