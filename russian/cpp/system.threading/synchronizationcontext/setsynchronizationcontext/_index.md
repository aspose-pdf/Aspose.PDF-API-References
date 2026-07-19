---
title: "Метод System::Threading::SynchronizationContext::SetSynchronizationContext"
linktitle: "SetSynchronizationContext"
second_title: "Справочник API Aspose.PDF для C++"
description: "Метод System::Threading::SynchronizationContext::SetSynchronizationContext. Устанавливает контекст синхронизации для текущего потока на C++."
type: docs
weight: 500
url: /ru/cpp/system.threading/synchronizationcontext/setsynchronizationcontext/
---
## SynchronizationContext::SetSynchronizationContext method


Устанавливает контекст синхронизации для текущего потока.

```cpp
static void System::Threading::SynchronizationContext::SetSynchronizationContext(const SharedPtr<SynchronizationContext> &syncContext)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| syncContext | const SharedPtr\<SynchronizationContext\>\& | Контекст синхронизации, который нужно установить для текущего потока. |
## Примечания



Передача nullptr очистит контекст синхронизации для текущего потока.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SynchronizationContext](../)
* Class [SynchronizationContext](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
