---
title: "System::Threading::ThreadPoolImpl::QueueUserWorkItem metod"
linktitle: "QueueUserWorkItem"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Threading::ThreadPoolImpl::QueueUserWorkItem metod. Lägger till arbetsobjekt i kön i C++."
type: docs
weight: 700
url: /sv/cpp/system.threading/threadpoolimpl/queueuserworkitem/
---
## ThreadPoolImpl::QueueUserWorkItem method


Lägger till arbetsobjekt i kön.

```cpp
bool System::Threading::ThreadPoolImpl::QueueUserWorkItem(WaitCallback callback, const System::SharedPtr<System::Object> &state)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| callback | WaitCallback | Callback-funktion att köra. |
| state | const System::SharedPtr\<System::Object\>\& | Argument till callback-funktion. |

### ReturnValue

Returnerar alltid true.

## Se även

* Typedef [WaitCallback](../../waitcallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [ThreadPoolImpl](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
