---
title: System::Threading::Tasks::ResultTask::GetAwaiter method
linktitle: GetAwaiter
second_title: Aspose.PDF for C++ API Reference
description: 'System::Threading::Tasks::ResultTask::GetAwaiter method. Gets an awaiter for this result task for use with Await in C++.'
type: docs
weight: 600
url: /cpp/system.threading.tasks/resulttask/getawaiter/
---
## ResultTask::GetAwaiter method


Gets an awaiter for this result task for use with Await.

```cpp
Runtime::CompilerServices::ResultTaskAwaiter<T> System::Threading::Tasks::ResultTask<T>::GetAwaiter() const
```


### ReturnValue

[Runtime::CompilerServices::ResultTaskAwaiter<T>](../../../system.runtime.compilerservices/resulttaskawaiter/) An awaiter instance that returns the result
## Remarks



When awaited, the coroutine will resume with the result value available 

## See Also

* Class [ResultTaskAwaiter](../../../system.runtime.compilerservices/resulttaskawaiter/)
* Class [ResultTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
