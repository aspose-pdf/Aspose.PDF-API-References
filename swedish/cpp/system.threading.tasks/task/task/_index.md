---
title: "System::Threading::Tasks::Task::Task konstruktor"
linktitle: "Uppgift"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Threading::Tasks::Task::Task konstruktor. Intern konstruktor för att skapa oinitialiserade uppdrag i C++."
type: docs
weight: 100
url: /sv/cpp/system.threading.tasks/task/task/
---
## Task::Task() constructor


Intern konstruktor för att skapa oinitierade uppgifter.

```cpp
System::Threading::Tasks::Task::Task()
```

## Se även

* Class [Task](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
## Task::Task(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\&) constructor


Skapar en [Task](../) med en tillståndsbevarande åtgärd och ett tillståndsobjekt.

```cpp
System::Threading::Tasks::Task::Task(const Action<SharedPtr<Object>> &action, const SharedPtr<Object> &state)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| action | const Action\<SharedPtr\<Object\>\>\& | Åtgärden att köra (accepterar tillståndsobjekt) |
| state | const SharedPtr\<Object\>\& | Användardefinierat tillståndsobjekt som skickas till åtgärden |

## Se även

* Typedef [Action](../../../system/action/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [Task](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
## Task::Task(const Action\<SharedPtr\<Object\>\>\&, const SharedPtr\<Object\>\&, const CancellationToken\&) constructor


Skapar en [Task](../) med tillståndsbevarande åtgärd, tillstånd och avbokningstoken.

```cpp
System::Threading::Tasks::Task::Task(const Action<SharedPtr<Object>> &action, const SharedPtr<Object> &state, const CancellationToken &cancellationToken)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| action | const Action\<SharedPtr\<Object\>\>\& | Åtgärden att köra (accepterar tillståndsobjekt) |
| state | const SharedPtr\<Object\>\& | Användardefinierat tillståndsobjekt som skickas till åtgärden |
| cancellationToken | const CancellationToken\& | Token för att övervaka avbokningsförfrågningar |

## Se även

* Typedef [Action](../../../system/action/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [CancellationToken](../../../system.threading/cancellationtoken/)
* Class [Task](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
## Task::Task(const Action<>\&) constructor


Skapar en [Task](../) med en åtgärd att köra.

```cpp
System::Threading::Tasks::Task::Task(const Action<> &action)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| action | const Action<>\& | Åtgärden att köra asynkront |

## Se även

* Typedef [Action](../../../system/action/)
* Class [Task](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
## Task::Task(const Action<>\&, const CancellationToken\&) constructor


Skapar en [Task](../) med en åtgärd och avbokningstoken.

```cpp
System::Threading::Tasks::Task::Task(const Action<> &action, const CancellationToken &cancellationToken)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| action | const Action<>\& | Åtgärden att köra asynkront |
| cancellationToken | const CancellationToken\& | Token för att övervaka avbokningsförfrågningar |

## Se även

* Typedef [Action](../../../system/action/)
* Class [CancellationToken](../../../system.threading/cancellationtoken/)
* Class [Task](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
