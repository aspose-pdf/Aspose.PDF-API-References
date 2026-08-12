---
title: "System::Threading::CancellationTokenRegistration class"
linktitle: "CancellationTokenRegistration"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Threading::CancellationTokenRegistration class. Representerar en registrering för en avbokningstoken‑callback i C++."
type: docs
weight: 300
url: /sv/cpp/system.threading/cancellationtokenregistration/
---
## CancellationTokenRegistration class


Representerar en registrering för en avbokningstoken-återuppringning.

```cpp
class CancellationTokenRegistration
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Dispose](./dispose/)() | Avslutar registreringen och tar bort callbacken från den associerade [CancellationTokenSource](../cancellationtokensource/). Efter att ha anropat denna metod kommer den registrerade callbacken inte längre att anropas när den associerade [CancellationTokenSource](../cancellationtokensource/) avbryts. |
## Anmärkningar


Denna klass möjliggör avregistrering av en callback från en avbokningstoken. När den avslutas tar den bort callbacken från den associerade [CancellationTokenSource](../cancellationtokensource/).
Denna klass bör inte skapas direkt – den returneras av registreringsmetoderna i [CancellationToken](../cancellationtoken/).

## Se även

* Namespace [System::Threading](../)
* Library [Aspose.PDF for C++](../../)
