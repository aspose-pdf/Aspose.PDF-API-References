---
title: "System::Text::RegularExpressions::Group class"
linktitle: "Group"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Text::RegularExpressions::Group class. Resultat av matchning utförd av en enda fångstgrupp. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller assertionsfel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 300
url: /sv/cpp/system.text.regularexpressions/group/
---
## Group class


Resultat av matchning utförd av en enda fångstgrupp. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller assertionsfel. Omslut alltid denna klass i [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class Group : public System::Text::RegularExpressions::Capture
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [AddCapture](./addcapture/)(const CapturePtr\&) | Lägger till fångst i gruppen. |
| [get_Captures](./get_captures/)() | Hämtar tillgängliga fångster. |
| [get_Success](./get_success/)() | Kontrollerar om fångst lyckades för denna grupp. |
| [Group](./group/)(const UStringPtr\&, int, int) | Konstruktor. |
| [Group](./group/)() | Konstruktor för tom grupp. |
## Se även

* Class [Capture](../capture/)
* Namespace [System::Text::RegularExpressions](../)
* Library [Aspose.PDF for C++](../../)
