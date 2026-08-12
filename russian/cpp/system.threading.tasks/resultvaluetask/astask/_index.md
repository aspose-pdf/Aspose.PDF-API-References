---
title: "System::Threading::Tasks::ResultValueTask::AsTask метод"
linktitle: "AsTask"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Threading::Tasks::ResultValueTask::AsTask метод. Преобразует этот ResultValueTask в разделяемый указатель на ResultTask<T> в C++."
type: docs
weight: 200
url: /ru/cpp/system.threading.tasks/resultvaluetask/astask/
---
## ResultValueTask::AsTask method


Преобразует этот [ResultValueTask](../) в разделяемый указатель на [ResultTask<T>](../../resulttask/).

```cpp
RTaskPtr<T> System::Threading::Tasks::ResultValueTask<T>::AsTask() const
```


### ReturnValue

[RTaskPtr<T>](../../../system/rtaskptr/) A shared pointer to a [ResultTask<T>](../../resulttask/) that represents this operation.
## Примечания



Если [ResultValueTask](../) содержит прямой результат, создаёт завершённую задачу с этим результатом. Если он содержит задачу, возвращает разделяемый указатель на эту задачу.

## См. также

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Class [ResultValueTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
