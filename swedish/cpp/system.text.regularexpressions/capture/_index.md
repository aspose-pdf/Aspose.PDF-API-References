---
title: "System::Text::RegularExpressions::Capture klass"
linktitle: "Capture"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Text::RegularExpressions::Capture klass. Resultat av en enstaka deluttrycks‑matchning. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller assertionsfel. Omslut alltid denna klass med en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 100
url: /sv/cpp/system.text.regularexpressions/capture/
---
## Capture class


Resultat av en enstaka deluttrycks‑matchning. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller assertionsfel. Omslut alltid denna klass med en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class Capture : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Capture](./capture/)(const UStringPtr\&, int, int) | Konstruktor. |
| [get_Index](./get_index/)() const | Hämtar index för fångad delsträng. |
| [get_Length](./get_length/)() const | Hämtar längden på den fångade delsträngen. |
| [get_Value](./get_value/)() const | Hämtar den fångade delsträngen. |
| [ToString](./tostring/)() const override | Hämtar den fångade delsträngen. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Text::RegularExpressions](../)
* Library [Aspose.PDF for C++](../../)
