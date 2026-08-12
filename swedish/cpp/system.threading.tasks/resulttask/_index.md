---
title: "System::Threading::Tasks::ResultTask-klass"
linktitle: "ResultTask"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Threading::Tasks::ResultTask-klass. En Task-specialisering som returnerar ett resultatvärde vid slutförande i C++."
type: docs
weight: 400
url: /sv/cpp/system.threading.tasks/resulttask/
---
## ResultTask class


En [Task](../task/) specialisering som returnerar ett resultatvärde vid slutförande.

```cpp
template<typename T>class ResultTask : public System::Threading::Tasks::Task
```


| Parameter | Beskrivning |
| --- | --- |
| T | Typen av resultatvärdet som returneras av uppgiften |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Complete](./complete/)(const T\&) | Sätter resultatvärdet för uppgiften och slutför den. |
| [ConfigureAwait](./configureawait/)(bool) const | Konfigurerar hur väntningar på denna resultatuppgift ska bete sig avseende kontextfångst. |
| [ContinueWith](./continuewith/)(const Action\<RTaskPtr\<T\>\>\&) | Skapar en fortsättning som körs när resultatuppgiften är slutförd. |
| [ContinueWith](./continuewith/)(const Func\<RTaskPtr\<T\>, TNewResult\>\&) | Skapar en fortsättning som körs när resultatuppgiften är slutförd. |
| [ContinueWith](./continuewith/)(const Action\<TaskPtr\>\&) | Skapar en fortsättning som körs när uppgiften är slutförd. |
| [ContinueWith](./continuewith/)(const Func\<TaskPtr, TResult\>\&) | Skapar en fortsättning som körs när uppgiften är slutförd. |
| [get_Result](./get_result/)() | Hämtar resultatet av den asynkrona operationen. |
| [GetAwaiter](./getawaiter/)() const | Hämtar en awaiter för denna resultatuppgift för användning med Await. |
| [ResultTask](./resulttask/)(const Func\<T\>\&) | Konstruktor för en [ResultTask](./) med en funktion som returnerar ett värde. |
| [ResultTask](./resulttask/)() | Intern implementation. Inte för användarkod. |
| [ResultTask](./resulttask/)(const T\&) | Intern konstruktor för att skapa resultatuppgifter med specificerat resultat. |
| [set_Result](./set_result/)(const T\&) | Sätter resultatvärdet för uppgiften. |
## Anmärkningar



Representerar en asynkron operation som producerar ett resultat, liknande [System.Threading.Tasks.Task<TResult>](../task/) i .NET
## Se även

* Class [Task](../task/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
