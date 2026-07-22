---
title: "System::IO::FileStream::ReadAsync metod"
linktitle: "ReadAsync"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::FileStream::ReadAsync metod. Läser asynkront en sekvens av byte från den aktuella strömmen, förflyttar positionen i strömmen med antalet lästa byte och övervakar avbokningsförfrågningar i C++."
type: docs
weight: 1400
url: /sv/cpp/system.io/filestream/readasync/
---
## FileStream::ReadAsync method


Läser asynkront en sekvens av byte från den aktuella strömmen, förflyttar positionen i strömmen med antalet lästa byte och övervakar avbokningsförfrågningar.

```cpp
RTaskPtr<int32_t> System::IO::FileStream::ReadAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const ArrayPtr\<uint8_t\>\& | Bytearrayen att skriva de lästa byten till. |
| förskjutning | int32_t | En 0-baserad position i **buffer** att börja skriva på. |
| count | int32_t | Antalet byte att läsa. |
| cancellationToken | const Threading::CancellationToken\& | Tokenet för att övervaka avbokningsförfrågningar. |

### ReturnValue

Ett uppdrag som representerar den asynkrona läsoperationen. Värdet på TResult‑parametern innehåller det totala antalet byte som lästs in i buffer. Resultatvärdet kan vara mindre än det begärda antalet byte om antalet för närvarande tillgängliga byte är mindre än det begärda antalet, eller så kan det vara 0 (noll) om slutet på strömmen har nåtts.

## Se även

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [CancellationToken](../../../system.threading/cancellationtoken/)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
