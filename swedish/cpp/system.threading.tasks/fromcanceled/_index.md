---
title: "System::Threading::Tasks::FromCanceled metod"
linktitle: "FromCanceled"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Threading::Tasks::FromCanceled metod. Skapar en task som har slutförts på grund av avbokning med den specificerade token i C++."
type: docs
weight: 1200
url: /sv/cpp/system.threading.tasks/fromcanceled/
---
## System::Threading::Tasks::FromCanceled method


Skapar en task som har slutförts på grund av avbokning med den specificerade token.

```cpp
TaskPtr System::Threading::Tasks::FromCanceled(const CancellationToken &cancellationToken)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| cancellationToken | const CancellationToken\& | Avbokningstoken som orsakade att tasken avbröts. |

### ReturnValue

En avbruten task.

## Se även

* Typedef [TaskPtr](../../system/taskptr/)
* Class [CancellationToken](../../system.threading/cancellationtoken/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
