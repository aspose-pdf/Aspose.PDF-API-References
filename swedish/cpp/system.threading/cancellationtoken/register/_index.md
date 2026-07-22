---
title: "System::Threading::CancellationToken::Register metod"
linktitle: "Registrera"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Threading::CancellationToken::Register metod. Registrerar en återuppringning som kommer att anropas när avbokning begärs i C++."
type: docs
weight: 400
url: /sv/cpp/system.threading/cancellationtoken/register/
---
## CancellationToken::Register method


Registrerar en återuppringning som kommer att anropas när avbokning begärs.

```cpp
CancellationTokenRegistration System::Threading::CancellationToken::Register(const Action<> &callback) const
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| callback | const Action<>\& | Den [Action<>](../../../system/action/) som ska köras när avbokning begärs. |

### ReturnValue

Ett [CancellationTokenRegistration](../../cancellationtokenregistration/)-objekt som kan användas för att avregistrera återuppringningen.
## Anmärkningar



Om avbokning redan har begärts kommer återuppringningen att anropas omedelbart.

## Se även

* Class [CancellationTokenRegistration](../../cancellationtokenregistration/)
* Typedef [Action](../../../system/action/)
* Class [CancellationToken](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
