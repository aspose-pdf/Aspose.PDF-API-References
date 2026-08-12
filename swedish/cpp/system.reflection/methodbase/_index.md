---
title: "System::Reflection::MethodBase klass"
linktitle: "MethodBase"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Reflection::MethodBase klass. Grundläggande information om metoden. Objekt av denna klass bör endast allokeras med System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 800
url: /sv/cpp/system.reflection/methodbase/
---
## MethodBase class


Grundläggande information om metoden. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)‑pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class MethodBase : public System::Reflection::MemberInfo
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_MemberType](./get_membertype/)() const override | Anger medlemmens typ – metod, konstruktor, händelse osv. |
| static [GetCurrentMethod](./getcurrentmethod/)(const String\&) | Denna metod möjliggör att hämta det aktuella metodnamnet. Översättaren ersätter automatiskt ASPOSE_CURRENT_FUNCTION som parameter. |
| [MEMBER_FUNCTION_MAKE_OBJECT](./member_function_make_object/)(MethodBase, CODEPORTING_ARGS(const String\&full_name), CODEPORTING_ARGS(full_name)) |  |
| [MethodBase](./methodbase/)() | Initierar en ny instans av [MethodBase](./)‑klassen. |
## Se även

* Class [MemberInfo](../memberinfo/)
* Namespace [System::Reflection](../)
* Library [Aspose.PDF for C++](../../)
