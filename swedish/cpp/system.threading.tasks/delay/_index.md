---
title: "System::Threading::Tasks::Delay metod"
linktitle: "Delay"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Threading::Tasks::Delay metod. Skapar en uppgift som avslutas efter en tidsfördröjning i C++."
type: docs
weight: 1000
url: /sv/cpp/system.threading.tasks/delay/
---
## System::Threading::Tasks::Delay(int32_t) method


Skapar en uppgift som avslutas efter en tidsfördröjning.

```cpp
TaskPtr System::Threading::Tasks::Delay(int32_t millisecondsDelay)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| millisecondsDelay | int32_t | Antalet millisekunder att vänta innan den returnerade uppgiften avslutas, eller -1 för att vänta obegränsat. |

### ReturnValue

En uppgift som representerar tidsfördröjningen.

## Se även

* Typedef [TaskPtr](../../system/taskptr/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
## System::Threading::Tasks::Delay(int32_t, const CancellationToken\&) method


Skapar en uppgift som avslutas efter en tidsfördröjning och kan avbrytas.

```cpp
TaskPtr System::Threading::Tasks::Delay(int32_t millisecondsDelay, const CancellationToken &cancellationToken)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| millisecondsDelay | int32_t | Antalet millisekunder att vänta innan den returnerade uppgiften avslutas, eller -1 för att vänta obegränsat. |
| cancellationToken | const CancellationToken\& | Avbokningstoken som kan användas för att avbryta fördröjningen. |

### ReturnValue

En uppgift som representerar tidsfördröjningen.

## Se även

* Typedef [TaskPtr](../../system/taskptr/)
* Class [CancellationToken](../../system.threading/cancellationtoken/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
