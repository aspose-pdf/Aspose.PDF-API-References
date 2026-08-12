---
title: "System::IO::FileStream::FlushAsync metod"
linktitle: "FlushAsync"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::FileStream::FlushAsync metod. Rensar asynkront alla buffertar för denna ström, får all buffrad data att skrivas till den underliggande enheten och övervakar avbokningsförfrågningar i C++."
type: docs
weight: 500
url: /sv/cpp/system.io/filestream/flushasync/
---
## FileStream::FlushAsync method


Rensar asynkront alla buffertar för denna ström, får all buffrad data att skrivas till den underliggande enheten och övervakar avbokningsförfrågningar.

```cpp
TaskPtr System::IO::FileStream::FlushAsync(const Threading::CancellationToken &cancellationToken) override
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cancellationToken | const Threading::CancellationToken\& | Tokenet för att övervaka avbokningsförfrågningar. |

### ReturnValue

En uppgift som representerar den asynkrona flush‑operationen.

## Se även

* Typedef [TaskPtr](../../../system/taskptr/)
* Class [CancellationToken](../../../system.threading/cancellationtoken/)
* Class [FileStream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
