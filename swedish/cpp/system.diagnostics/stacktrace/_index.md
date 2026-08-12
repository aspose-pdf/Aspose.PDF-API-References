---
title: "System::Diagnostics::StackTrace klass"
linktitle: "StackTrace"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Diagnostics::StackTrace klass. Samling av stackramar. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass med en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 600
url: /sv/cpp/system.diagnostics/stacktrace/
---
## StackTrace class


Samling av stackramar. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass med en [System::SmartPtr](../../system/smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class StackTrace : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_FrameCount](./get_framecount/)() const | Hämtar antalet ramar i stackspåret. |
| virtual [GetFrame](./getframe/)(uint32_t) | Hämtar stackram. |
| [operator=](./operator=/)(const StackTrace\&) const | Ingen tilldelning. |
| [StackTrace](./stacktrace/)() | Skapar ett stackspår som beskriver det aktuella stacktillståndet. |
| [StackTrace](./stacktrace/)(bool) | Skapar ett stackspår som beskriver det aktuella stacktillståndet. |
| [StackTrace](./stacktrace/)(const StackTrace\&) | Ingen kopiering. |
| virtual [~StackTrace](./~stacktrace/)() | Destruktor. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Diagnostics](../)
* Library [Aspose.PDF for C++](../../)
