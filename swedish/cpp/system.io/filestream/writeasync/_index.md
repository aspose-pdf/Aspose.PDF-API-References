---
title: "System::IO::FileStream::WriteAsync metod"
linktitle: "WriteAsync"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::FileStream::WriteAsync metod. Skriver asynkront en sekvens av bytes till den aktuella strömmen, förflyttar den aktuella positionen i denna ström med antalet skrivna bytes och övervakar avbokningsförfrågningar i C++."
type: docs
weight: 2000
url: /sv/cpp/system.io/filestream/writeasync/
---
## FileStream::WriteAsync method


Skriver asynkront en sekvens av bytes till den aktuella strömmen, förflyttar den aktuella positionen i strömmen med antalet skrivna bytes och övervakar avbokningsförfrågningar.

```cpp
TaskPtr System::IO::FileStream::WriteAsync(const ArrayPtr<uint8_t> &buffer, int32_t offset, int32_t count, const Threading::CancellationToken &cancellationToken) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const ArrayPtr\<uint8_t\>\& | Arrayen som innehåller byte att skriva. |
| förskjutning | int32_t | Ett 0‑baserat index för elementet i **buffer** där delintervallet att skriva börjar. |
| count | int32_t | Antalet element i delintervallet som ska skrivas. |
| cancellationToken | const Threading::CancellationToken\& | Tokenet för att övervaka avbokningsförfrågningar. |

### ReturnValue

En uppgift som representerar den asynkrona skrivoperationen.

## Se även

* Typedef [TaskPtr](../../../system/taskptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [CancellationToken](../../../system.threading/cancellationtoken/)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
