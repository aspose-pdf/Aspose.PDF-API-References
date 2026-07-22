---
title: "System::Threading::Tasks::ResultValueTask::ResultValueTask konstruktor"
linktitle: "ResultValueTask"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Threading::Tasks::ResultValueTask::ResultValueTask konstruktor. Skapar ett tomt, oinitierat ResultValueTask i C++."
type: docs
weight: 100
url: /sv/cpp/system.threading.tasks/resultvaluetask/resultvaluetask/
---
## ResultValueTask::ResultValueTask() constructor


Skapar ett tomt, oinitierat [ResultValueTask](../).

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask()
```

## Anmärkningar



Uppgiften är inte slutförd och innehåller inget resultat. Försök att hämta resultatet kommer att kasta ett undantag.

## Se även

* Class [ResultValueTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
## ResultValueTask::ResultValueTask(const RTaskPtr\<T\>\&) constructor


Skapar ett [ResultValueTask](../) från en delad pekare till en [ResultTask<T>](../../resulttask/).

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask(const RTaskPtr<T> &task)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| task | const RTaskPtr\<T\>\& | Uppgiften att omsluta. Kan vara null för en tom uppgift. |
## Anmärkningar



Det [ResultValueTask](../) kommer att representera tillståndet och resultatet för den angivna uppgiften.

## Se även

* Typedef [RTaskPtr](../../../system/rtaskptr/)
* Class [ResultValueTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
## ResultValueTask::ResultValueTask(const T\&) constructor


Skapar ett slutfört [ResultValueTask](../) med det angivna resultatet.

```cpp
System::Threading::Tasks::ResultValueTask<T>::ResultValueTask(const T &result)
```


| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| result | const T\& | Resultatvärdet att omsluta i en slutförd uppgift. |
## Anmärkningar



Detta skapar en framgångsrikt slutförd uppgift som omedelbart returnerar värdet.

## Se även

* Class [ResultValueTask](../)
* Namespace [System::Threading::Tasks](../../)
* Library [Aspose.PDF for C++](../../../)
