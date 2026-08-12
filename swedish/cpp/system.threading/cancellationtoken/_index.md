---
title: "System::Threading::CancellationToken class"
linktitle: "CancellationToken"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Threading::CancellationToken class. Sprider en notifikation om att operationer bör avbrytas. Denna klass tillhandahåller en mekanism för samarbetsavbrott mellan trådar, så att en tråd kan meddela andra att en operation bör avbrytas i C++."
type: docs
weight: 200
url: /sv/cpp/system.threading/cancellationtoken/
---
## CancellationToken class


Sprider en notifikation om att operationer bör avbrytas. Denna klass tillhandahåller en mekanism för samarbetsbaserad avbrytning mellan trådar, vilket gör att en tråd kan meddela andra att en operation bör avbrytas.

```cpp
class CancellationToken : public System::Details::BoxableObjectBase
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [CancellationToken](./cancellationtoken/)() | Standardkonstruktor. |
| [get_CanBeCanceled](./get_canbecanceled/)() const | Hämtar om denna token kan vara i avbrutet tillstånd. |
| [get_IsCancellationRequested](./get_iscancellationrequested/)() const | Hämtar om avbokning har begärts för denna token. |
| static [get_None](./get_none/)() | Returnerar ett tomt [System::Threading::CancellationToken](./)-värde. |
| [Register](./register/)(const Action<>\&) const | Registrerar en återuppringning som kommer att anropas när avbokning begärs. |
| [ThrowIfCancellationRequested](./throwifcancellationrequested/)() const | Kastar ett OperationCanceledException om avbokning har begärts. |
## Anmärkningar



En [CancellationToken](./) kan endast avbrytas via dess associerade [CancellationTokenSource](../cancellationtokensource/).

## Se även

* Namespace [System::Threading](../)
* Library [Aspose.PDF for C++](../../)
