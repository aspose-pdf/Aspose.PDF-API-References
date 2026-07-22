---
title: "System::Threading::Tasks::ResultTask::ResultTask constructor"
linktitle: "ResultTask"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Threading::Tasks::ResultTask::ResultTask constructor. Intern implementering. Inte för användarkod i C++."
type: docs
weight: 100
url: /sv/cpp/system.threading.tasks/resulttask/resulttask/
---
## ResultTask::ResultTask() constructor


Intern implementation. Inte för användarkod.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask()
```

## Anmärkningar


Intern konstruktor för att skapa oinitialiserade resultatuppgifter
## Se även

* Class [ResultTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
## ResultTask::ResultTask(const Func\<T\>\&) constructor


Skapar ett [ResultTask](../) med en funktion som returnerar ett värde.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask(const Func<T> &function)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| funktion | const Func\<T\>\& | Funktionen som ska köras asynkront och som returnerar ett resultat |

## Se även

* Class [Func](../../../system/func/)
* Class [ResultTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
## ResultTask::ResultTask(const T\&) constructor


Intern konstruktor för att skapa resultatuppgifter med specificerat resultat.

```cpp
System::Threading::Tasks::ResultTask<T>::ResultTask(const T &result)
```

## Se även

* Class [ResultTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
