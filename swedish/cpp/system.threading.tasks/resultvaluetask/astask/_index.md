---
title: "System::Threading::Tasks::ResultValueTask::AsTask metod"
linktitle: "AsTask"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Threading::Tasks::ResultValueTask::AsTask metod. Konverterar detta ResultValueTask till en delad pekare till ResultTask<T> i C++."
type: docs
weight: 200
url: /sv/cpp/system.threading.tasks/resultvaluetask/astask/
---
## ResultValueTask::AsTask method


Konverterar detta [ResultValueTask](../) till en delad pekare till [ResultTask<T>](../../resulttask/).

```cpp
RTaskPtr<T> System::Threading::Tasks::ResultValueTask<T>::AsTask() const
```


### ReturnValue

[RTaskPtr<T>](../../../system/rtaskptr/) A shared pointer to a [ResultTask<T>](../../resulttask/) that represents this operation.
## Anmärkningar



Om [ResultValueTask](../) innehåller ett direkt resultat, skapar ett slutfört uppgift med det resultatet. Om det innehåller ett uppgift, returnerar en delad pekare till den uppgiften.

## Se även

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Class [ResultValueTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
