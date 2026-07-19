---
title: "System::Threading::SynchronizationContext::get_Current метод"
linktitle: "get_Current"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Threading::SynchronizationContext::get_Current метод. Получает контекст синхронизации для текущего потока в C++."
type: docs
weight: 400
url: /ru/cpp/system.threading/synchronizationcontext/get_current/
---
## SynchronizationContext::get_Current method


Получает контекст синхронизации для текущего потока.

```cpp
static const SharedPtr<SynchronizationContext> & System::Threading::SynchronizationContext::get_Current()
```


### ReturnValue

[SharedPtr<SynchronizationContext>](../../../system/sharedptr/) A shared pointer to the current thread's synchronization context.
## Примечания



Возвращает null, если для текущего потока не установлен контекст синхронизации.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SynchronizationContext](../)
* Class [SynchronizationContext](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
