---
title: "System::Threading::ThreadPool::QueueUserWorkItem-metod"
linktitle: "QueueUserWorkItem"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Threading::ThreadPool::QueueUserWorkItem-metod. Lägger till ett arbetsobjekt i kön som presenteras med ett återanrop utan parametrar i C++."
type: docs
weight: 600
url: /sv/cpp/system.threading/threadpool/queueuserworkitem/
---
## ThreadPool::QueueUserWorkItem(WaitCallback) method


Lägger till ett arbetsobjekt i kön som finns med en callback utan parametrar.

```cpp
static bool System::Threading::ThreadPool::QueueUserWorkItem(WaitCallback callback)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| callback | WaitCallback | Återuppringningsfunktion som ska användas som ett jobb. |

### ReturnValue

Returnerar alltid true.

## Se även

* Typedef [WaitCallback](../../waitcallback/)
* Class [ThreadPool](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
## ThreadPool::QueueUserWorkItem(WaitCallback, const System::SharedPtr\<System::Object\>\&) method


Lägger till ett arbetsobjekt i kön som finns med en callback utan parametrar.

```cpp
static bool System::Threading::ThreadPool::QueueUserWorkItem(WaitCallback callback, const System::SharedPtr<System::Object> &state)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| callback | WaitCallback | Återuppringningsfunktion som ska användas som ett jobb. |
| state | const System::SharedPtr\<System::Object\>\& | Parameter för jobbfunktion. |

### ReturnValue

Returnerar alltid true.

## Se även

* Typedef [WaitCallback](../../waitcallback/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [ThreadPool](../)
* Namespace [System::Threading](../../)
* Library [Aspose.PDF for C++](../../../)
