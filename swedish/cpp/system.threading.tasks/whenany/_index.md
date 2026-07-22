---
title: "System::Threading::Tasks::WhenAny method"
linktitle: "WhenAny"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Threading::Tasks::WhenAny method. Skapar en task som slutförs när någon av de angivna tasks har slutförts i C++."
type: docs
weight: 2800
url: /sv/cpp/system.threading.tasks/whenany/
---
## System::Threading::Tasks::WhenAny(const ArrayPtr\<RTaskPtr\<TResult\>\>\&) method


Skapar en task som slutförs när någon av de angivna tasks har slutförts.

```cpp
template<typename TResult> RTaskPtr<RTaskPtr<TResult>> System::Threading::Tasks::WhenAny(const ArrayPtr<RTaskPtr<TResult>> &tasks)
```


| Parameter | Beskrivning |
| --- | --- |
| TResult | Typen av resultatet för den slutförda tasken. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| taskar | const ArrayPtr\<RTaskPtr\<TResult\>\>\& | Uppgifterna att vänta på för att slutföras. |

### ReturnValue

En task som returnerar den första slutförda tasken när någon task slutförs.

## Se även

* Typedef [RTaskPtr](../../system/rtaskptr/)
* Typedef [ArrayPtr](../../system/arrayptr/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
## System::Threading::Tasks::WhenAny(const ArrayPtr\<TaskPtr\>\&) method


Skapar en task som slutförs när någon av de angivna tasks har slutförts.

```cpp
RTaskPtr<TaskPtr> System::Threading::Tasks::WhenAny(const ArrayPtr<TaskPtr> &tasks)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| taskar | const ArrayPtr\<TaskPtr\>\& | Uppgifterna att vänta på för att slutföras. |

### ReturnValue

En task som representerar slutförandet av en av de angivna tasks.

## Se även

* Typedef [RTaskPtr](../../system/rtaskptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [ArrayPtr](../../system/arrayptr/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
## System::Threading::Tasks::WhenAny(const SharedPtr\<Collections::Generic::IEnumerable\<RTaskPtr\<TResult\>\>\>\&) method


Skapar en task som slutförs när någon av de angivna tasks har slutförts.

```cpp
template<typename TResult> RTaskPtr<RTaskPtr<TResult>> System::Threading::Tasks::WhenAny(const SharedPtr<Collections::Generic::IEnumerable<RTaskPtr<TResult>>> &tasks)
```


| Parameter | Beskrivning |
| --- | --- |
| TResult | Typen av resultatet för den slutförda tasken. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| taskar | const SharedPtr\<Collections::Generic::IEnumerable\<RTaskPtr\<TResult\>\>\>\& | Uppgifterna att vänta på för att slutföras. |

### ReturnValue

En task som returnerar den första slutförda tasken när någon task slutförs.

## Se även

* Typedef [RTaskPtr](../../system/rtaskptr/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
## System::Threading::Tasks::WhenAny(const SharedPtr\<Collections::Generic::IEnumerable\<TaskPtr\>\>\&) method


Skapar en task som slutförs när någon av de angivna tasks har slutförts.

```cpp
RTaskPtr<TaskPtr> System::Threading::Tasks::WhenAny(const SharedPtr<Collections::Generic::IEnumerable<TaskPtr>> &tasks)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| taskar | const SharedPtr\<Collections::Generic::IEnumerable\<TaskPtr\>\>\& | Uppgifterna att vänta på för att slutföras. |

### ReturnValue

En task som representerar slutförandet av en av de angivna tasks.

## Se även

* Typedef [RTaskPtr](../../system/rtaskptr/)
* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
