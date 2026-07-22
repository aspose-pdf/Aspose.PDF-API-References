---
title: "System::Threading::Tasks::ValueTask klass"
linktitle: "ValueTask"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Threading::Tasks::ValueTask klass. Tillhandahåller ett väntbart resultat av en asynkron operation i C++."
type: docs
weight: 800
url: /sv/cpp/system.threading.tasks/valuetask/
---
## ValueTask class


Tillhandahåller ett avvaktbart resultat av en asynkron operation.

```cpp
class ValueTask : public System::IEquatable<ValueTask>,
                  public System::Details::BoxableObjectBase
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [AsTask](./astask/)() const | Konverterar detta [ValueTask](./) till en delad pekare till [Task](../task/). |
| [ConfigureAwait](./configureawait/)(bool) const | Konfigurerar en väntare för denna uppgift. |
| [Equals](./equals/)(ValueTask) override | Avgör om detta objekt är lika med ett annat [ValueTask](./)-objekt. |
| [Equals](./equals/)(System::SharedPtr\<System::Object\>) override | Avgör om detta objekt är lika med ett annat objekt. |
| [get_IsCanceled](./get_iscanceled/)() const | Hämtar ett värde som indikerar om uppgiften avslutades på grund av avbokning. |
| [get_IsCompleted](./get_iscompleted/)() const | Hämtar ett värde som indikerar om uppgiften har avslutats. |
| [get_IsCompletedSuccessfully](./get_iscompletedsuccessfully/)() const | Hämtar ett värde som indikerar om uppgiften avslutades framgångsrikt. |
| [get_IsFaulted](./get_isfaulted/)() const | Hämtar ett värde som indikerar om uppgiften avslutades på grund av ett ohanterat undantag. |
| [GetAwaiter](./getawaiter/)() const | Hämtar en väntare för denna uppgift för att stödja await-uttryck. |
| [operator!=](./operator!=/)(const ValueTask\&) const | Icke‑likhetsoperator för [ValueTask](./). |
| [operator==](./operator==/)(const ValueTask\&) const | Likhetsoperator för [ValueTask](./). |
| [ValueTask](./valuetask/)() | Skapar en tom, oinitierad [ValueTask](./). |
| [ValueTask](./valuetask/)(const TaskPtr\&) | Skapar ett [ValueTask](./) från en delad pekare till en [Task](../task/). |
## Se även

* Class [IEquatable](../../system/iequatable/)
* Namespace [System::Threading::Tasks](../)
* Library [Aspose.PDF for C++](../../)
