---
title: "System::Threading::Tasks::ResultTask::GetAwaiter metod"
linktitle: "GetAwaiter"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Threading::Tasks::ResultTask::GetAwaiter metod. Hämtar en awaiter för detta result task för användning med Await i C++."
type: docs
weight: 600
url: /sv/cpp/system.threading.tasks/resulttask/getawaiter/
---
## ResultTask::GetAwaiter method


Hämtar en awaiter för denna resultatuppgift för användning med Await.

```cpp
Runtime::CompilerServices::ResultTaskAwaiter<T> System::Threading::Tasks::ResultTask<T>::GetAwaiter() const
```


### ReturnValue

[Runtime::CompilerServices::ResultTaskAwaiter<T>](../../../system.runtime.compilerservices/resulttaskawaiter/) An awaiter instance that returns the result
## Anmärkningar



När den väntas på kommer koroutinen att återupptas med resultatvärdet tillgängligt

## Se även

* Class [ResultTaskAwaiter](../../../system.runtime.compilerservices/resulttaskawaiter/)
* Class [ResultTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
