---
title: "System::Diagnostics::Stopwatch klass"
linktitle: "Stopwatch"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Diagnostics::Stopwatch klass. Tillåter tidsmätning. Objekt av denna klass bör endast allokeras med System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 700
url: /sv/cpp/system.diagnostics/stopwatch/
---
## Stopwatch class


Tillåter tidsmätning. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class Stopwatch : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Elapsed](./get_elapsed/)() const | Hämtar den totala förflutna tiden som mätts av den aktuella instansen. |
| [get_ElapsedMilliseconds](./get_elapsedmilliseconds/)() const | Hämtar den totala förflutna tiden som mätts av den aktuella instansen, i millisekunder. |
| [get_ElapsedTicks](./get_elapsedticks/)() const | Hämtar den totala förflutna tiden som mätts av den aktuella instansen, i timersteg. |
| [get_IsRunning](./get_isrunning/)() const | Kontrollerar om stoppuret körs. |
| [Reset](./reset/)() | Stoppar tidsmätning, sätter det uppmätta intervallet till noll. |
| [Restart](./restart/)() | Sätter det uppmätta intervallet till noll, och startar sedan tidsmätning. |
| [Start](./start/)() | Startar tidsmätning. |
| static [StartNew](./startnew/)() | Skapar ett nytt [Stopwatch](./)-objekt och startar mätning. |
| [Stop](./stop/)() | Stoppar tidsmätning. |
| [Stopwatch](./stopwatch/)() | RTTI-information. |
| virtual [~Stopwatch](./~stopwatch/)() | Destruktor. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Diagnostics](../)
* Library [Aspose.PDF for C++](../../)
