---
title: "System::Globalization::TextElementEnumerator klass"
linktitle: "TextElementEnumerator"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Globalization::TextElementEnumerator-klass. Enumerator för att iterera genom teckenselement (tecken). Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 2700
url: /sv/cpp/system.globalization/textelementenumerator/
---
## TextElementEnumerator class


Enumerator för att iterera genom teckenselement (tecken). Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class TextElementEnumerator : public virtual System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Current](./get_current/)() const | Hämtar det aktuella teckenselementet. |
| [get_ElementIndex](./get_elementindex/)() const | Hämtar index för det aktuella teckenselementet. |
| [GetTextElement](./gettextelement/)() const | Hämtar aktuellt element. |
| [MoveNext](./movenext/)() | Flyttar till nästa element. |
| [operator=](./operator=/)(const TextElementEnumerator\&) |  |
| [Reset](./reset/)() | Sätter enumeratorn till startpositionen. |
| [TextElementEnumerator](./textelementenumerator/)(const TextElementEnumerator\&) |  |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Globalization](../)
* Library [Aspose.PDF for C++](../../)
