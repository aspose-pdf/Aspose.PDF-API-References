---
title: "System::Threading::Tasks::ResultValueTask::get_Result metod"
linktitle: "get_Result"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Threading::Tasks::ResultValueTask::get_Result metod. Hämtar resultatet av den slutförda uppgiften i C++."
type: docs
weight: 900
url: /sv/cpp/system.threading.tasks/resultvaluetask/get_result/
---
## ResultValueTask::get_Result method


Hämtar resultatet av den slutförda uppgiften.

```cpp
T System::Threading::Tasks::ResultValueTask<T>::get_Result()
```


### ReturnValue

T Resultatvärdet.
## Anmärkningar



Om uppgiften stöds av en [ResultTask<T>](../../resulttask/), kommer denna metod att vänta på resultatet och cachea det. Efterföljande anrop kommer att returnera det cachade värdet utan att vänta.

## Se även

* Class [ResultValueTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
