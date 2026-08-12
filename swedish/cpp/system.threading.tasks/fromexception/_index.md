---
title: "Metoden System::Threading::Tasks::FromException"
linktitle: "FromException"
second_title: "Aspose.PDF för C++ API-referens"
description: "Metoden System::Threading::Tasks::FromException. Skapar en uppgift som har slutförts med ett specificerat undantag i C++."
type: docs
weight: 1300
url: /sv/cpp/system.threading.tasks/fromexception/
---
## System::Threading::Tasks::FromException(const Exception\&) method


Skapar en uppgift som har slutförts med ett specificerat undantag.

```cpp
TaskPtr System::Threading::Tasks::FromException(const Exception &exception)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| undantag | const Exception\& | Undantaget som ska användas för att slutföra uppgiften. |

### ReturnValue

En felaktig uppgift.

## Se även

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [Exception](../../system/exception/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
## System::Threading::Tasks::FromException(const Exception\&) method


Skapar en uppgift som har slutförts med ett specificerat undantag och resultattyp.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::FromException(const Exception &exception)
```


| Parameter | Beskrivning |
| --- | --- |
| TResult | Typen av uppgiftens resultat. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| undantag | const Exception\& | Undantaget som ska användas för att slutföra uppgiften. |

### ReturnValue

En felaktig uppgift med den specificerade resultattypen.

## Se även

* Typedef [RTaskPtr](../../system/rtaskptr/)
* Typedef [Exception](../../system/exception/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
