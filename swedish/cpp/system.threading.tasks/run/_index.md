---
title: "System::Threading::Tasks::Run‑metod"
linktitle: "Run"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Threading::Tasks::Run‑metod. Köar det angivna arbetet för att köras i trådpoolen och returnerar en Task‑handtag för det arbetet i C++."
type: docs
weight: 1600
url: /sv/cpp/system.threading.tasks/run/
---
## System::Threading::Tasks::Run(const Action<>\&) method


Köar det angivna arbetet för att köras i trådpoolen och returnerar ett [Task](../task/)‑handtag för det arbetet.

```cpp
TaskPtr System::Threading::Tasks::Run(const Action<> &action)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| action | const Action<>\& | Arbetet som ska köras asynkront. |

### ReturnValue

En [Task](../task/) som representerar arbetet som köats för att köras i trådpoolen.

## Se även

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [Action](../../system/action/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
## System::Threading::Tasks::Run(const Action<>\&, const CancellationToken\&) method


Köar det angivna arbetet för att köras i trådpoolen och returnerar ett [Task](../task/)‑handtag för det arbetet.

```cpp
TaskPtr System::Threading::Tasks::Run(const Action<> &action, const CancellationToken &cancellationToken)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| action | const Action<>\& | Arbetet som ska köras asynkront. |
| cancellationToken | const CancellationToken\& | En avbokningstoken som kan användas för att avbryta arbetet om det ännu inte har startat. |

### ReturnValue

En [Task](../task/) som representerar arbetet som köats för att köras i trådpoolen.

## Se även

* Typedef [TaskPtr](../../system/taskptr/)
* Typedef [Action](../../system/action/)
* Class [CancellationToken](../../system.threading/cancellationtoken/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
## System::Threading::Tasks::Run(const Func\<TaskPtr\>\&) method


Köar det specificerade arbetet för att köras i trådpoolen och returnerar en proxy för den [Task](../task/) som returneras av funktionen.

```cpp
TaskPtr System::Threading::Tasks::Run(const Func<TaskPtr> &function)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| function | const Func\<TaskPtr\>\& | Arbetet som ska köras asynkront, vilket returnerar en [Task](../task/). |

### ReturnValue

En [Task](../task/) som representerar en proxy för den [Task](../task/) som returneras av funktionen.

## Se även

* Typedef [TaskPtr](../../system/taskptr/)
* Class [Func](../../system/func/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
## System::Threading::Tasks::Run(const Func\<TResult\>\&) method


Köar det specificerade arbetet för att köras i trådpoolen och returnerar ett [Task<TResult>](../task/) handtag för det arbetet.

```cpp
template<typename TResult> RTaskPtr<TResult> System::Threading::Tasks::Run(const Func<TResult> &function)
```


| Parameter | Beskrivning |
| --- | --- |
| TResult | Typen av resultatet som returneras av uppgiften. |

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| funktion | const Func\<TResult\>\& | Arbetet som ska köras asynkront. |

### ReturnValue

En [Task<TResult>](../task/) som representerar arbetet som köats för att köras i trådpoolen.

## Se även

* Typedef [RTaskPtr](../../system/rtaskptr/)
* Class [Func](../../system/func/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
