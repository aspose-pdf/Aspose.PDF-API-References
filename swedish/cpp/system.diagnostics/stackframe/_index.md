---
title: "System::Diagnostics::StackFrame class"
linktitle: "StackFrame"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Diagnostics::StackFrame klass. Hämtar information om en enskild stackram. Endast MSVS. Objekt av denna klass bör endast allokeras med System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 500
url: /sv/cpp/system.diagnostics/stackframe/
---
## StackFrame class


Hämtar information om en enskild stackram. Endast MSVS. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class StackFrame : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [GetFileColumnNumber](./getfilecolumnnumber/)() | Hämtar kolumnnumret. |
| virtual [GetFileLineNumber](./getfilelinenumber/)() | Hämtar radnumret. |
| virtual [GetFileName](./getfilename/)() | Hämtar filnamnet. |
| [GetMethod](./getmethod/)() | Hämtar metodinformation. |
| [operator=](./operator=/)(const StackFrame\&) const | Ingen ändring. |
| [StackFrame](./stackframe/)(int) | Skapar stackram på aktuell stackoffset. |
| [StackFrame](./stackframe/)(const StackFrame\&) | Ingen kopiering. |
| virtual [~StackFrame](./~stackframe/)() | Destruktor. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Diagnostics](../)
* Library [Aspose.PDF for C++](../../)
