---
title: "Aspose::Pdf::OptimizedMemoryStream::Seek metod"
linktitle: "Sök"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::OptimizedMemoryStream::Seek metod. När den åsidosätts i en avledd klass sätter den positionen inom den aktuella strömmen i C++."
type: docs
weight: 1200
url: /sv/cpp/aspose.pdf/optimizedmemorystream/seek/
---
## OptimizedMemoryStream::Seek method


När den överskrivs i en avledd klass, anger den positionen i den aktuella strömmen.

```cpp
int64_t Aspose::Pdf::OptimizedMemoryStream::Seek(int64_t offset, System::IO::SeekOrigin origin) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| förskjutning | int64_t | En byteoffset relativt *origin*-parametern. |
| origin | System::IO::SeekOrigin | Ett värde av typen [T:System::IO::SeekOrigin](../) som indikerar referenspunkten som används för att erhålla den nya positionen. |

### ReturnValue

Den nya positionen inom den aktuella strömmen.

## Se även

* Enum [SeekOrigin](../../../system.io/seekorigin/)
* Class [OptimizedMemoryStream](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
