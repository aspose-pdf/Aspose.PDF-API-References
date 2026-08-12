---
title: "System::IO::Stream::FlushAsync metod"
linktitle: "FlushAsync"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::IO::Stream::FlushAsync metod. Rensar asynkront alla buffertar för denna ström, får all buffrad data att skrivas till den underliggande enheten och övervakar avbokningsförfrågningar i C++."
type: docs
weight: 900
url: /sv/cpp/system.io/stream/flushasync/
---
## Stream::FlushAsync() method


Rensar asynkront alla buffertar för denna ström, får all buffrad data att skrivas till den underliggande enheten och övervakar avbokningsförfrågningar.

```cpp
TaskPtr System::IO::Stream::FlushAsync()
```


### ReturnValue

En uppgift som representerar den asynkrona flush‑operationen.

## Se även

* Typedef [TaskPtr](../../../system/taskptr/)
* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
## Stream::FlushAsync(const Threading::CancellationToken\&) method


Rensar asynkront alla buffertar för denna ström, får all buffrad data att skrivas till den underliggande enheten och övervakar avbokningsförfrågningar.

```cpp
virtual TaskPtr System::IO::Stream::FlushAsync(const Threading::CancellationToken &cancellationToken)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cancellationToken | const Threading::CancellationToken\& | Tokenet för att övervaka avbokningsförfrågningar. |

### ReturnValue

En uppgift som representerar den asynkrona flush‑operationen.

## Se även

* Typedef [TaskPtr](../../../system/taskptr/)
* Class [CancellationToken](../../../system.threading/cancellationtoken/)
* Class [Stream](../)
* Namespace [System::IO](../../)
* Library [Aspose.PDF for C++](../../../)
