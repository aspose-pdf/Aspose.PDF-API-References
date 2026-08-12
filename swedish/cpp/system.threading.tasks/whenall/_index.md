---
title: "System::Threading::Tasks::WhenAll metod"
linktitle: "WhenAll"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Threading::Tasks::WhenAll metod. Skapar en task som kommer att slutföras när alla de levererade taskarna har slutförts i C++."
type: docs
weight: 2400
url: /sv/cpp/system.threading.tasks/whenall/
---
## System::Threading::Tasks::WhenAll(const ArrayPtr\<RTaskPtr\<TResult\>\>\&) method


Skapar en task som kommer att slutföras när alla de levererade taskarna har slutförts.

```cpp
template<typename TResult> RTaskPtr<ArrayPtr<TResult>> System::Threading::Tasks::WhenAll(const ArrayPtr<RTaskPtr<TResult>> &tasks)
```


| Parameter | Beskrivning |
| --- | --- |
| TResult | Typen av de slutförda taskarnas resultat. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| taskar | const ArrayPtr\<RTaskPtr\<TResult\>\>\& | Uppgifterna att vänta på för att slutföras. |

### ReturnValue

En uppgift som returnerar en array med alla resultat när alla uppgifter är slutförda.

## Se även

* Typedef [RTaskPtr](../../system/rtaskptr/)
* Typedef [ArrayPtr](../../system/arrayptr/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
## System::Threading::Tasks::WhenAll(const ArrayPtr\<TaskPtr\>\&) method


Skapar en task som kommer att slutföras när alla de levererade taskarna har slutförts.

```cpp
TaskPtr System::Threading::Tasks::WhenAll(const ArrayPtr<TaskPtr> &tasks)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| taskar | const ArrayPtr\<TaskPtr\>\& | Uppgifterna att vänta på för att slutföras. |

### ReturnValue

En uppgift som representerar slutförandet av alla levererade uppgifter.

## Se även

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [ArrayPtr](../../system/arrayptr/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
## System::Threading::Tasks::WhenAll(const SharedPtr\<Collections::Generic::IEnumerable\<RTaskPtr\<TResult\>\>\>\&) method


Skapar en task som kommer att slutföras när alla de levererade taskarna har slutförts.

```cpp
template<typename TResult> RTaskPtr<ArrayPtr<TResult>> System::Threading::Tasks::WhenAll(const SharedPtr<Collections::Generic::IEnumerable<RTaskPtr<TResult>>> &tasks)
```


| Parameter | Beskrivning |
| --- | --- |
| TResult | Typen av de slutförda taskarnas resultat. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| taskar | const SharedPtr\<Collections::Generic::IEnumerable\<RTaskPtr\<TResult\>\>\>\& | Uppgifterna att vänta på för att slutföras. |

### ReturnValue

En uppgift som returnerar en array med alla resultat när alla uppgifter är slutförda.

## Se även

* Typedef [RTaskPtr](../../system/rtaskptr/)
* Typedef [ArrayPtr](../../system/arrayptr/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
## System::Threading::Tasks::WhenAll(const SharedPtr\<Collections::Generic::IEnumerable\<TaskPtr\>\>\&) method


Skapar en task som kommer att slutföras när alla de levererade taskarna har slutförts.

```cpp
TaskPtr System::Threading::Tasks::WhenAll(const SharedPtr<Collections::Generic::IEnumerable<TaskPtr>> &tasks)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| taskar | const SharedPtr\<Collections::Generic::IEnumerable\<TaskPtr\>\>\& | Uppgifterna att vänta på för att slutföras. |

### ReturnValue

En uppgift som representerar slutförandet av alla levererade uppgifter.

## Se även

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
