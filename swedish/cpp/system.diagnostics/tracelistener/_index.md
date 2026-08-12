---
title: "System::Diagnostics::TraceListener klass"
linktitle: "TraceListener"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Diagnostics::TraceListener klass. Gränssnitt för att reagera på debug- och spårningsinformation. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 800
url: /sv/cpp/system.diagnostics/tracelistener/
---
## TraceListener class


Gränssnitt för att reagera på debug- och spårningsinformation. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
class TraceListener : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [Fail](./fail/)(System::String) | Skriver felmeddelande till debuggern. |
| virtual [Fail](./fail/)(System::String, System::String) | Skriver felmeddelande till debuggern. |
| virtual [Write](./write/)(System::String) | RTTI-information. |
| virtual [WriteLine](./writeline/)(System::String) | Skriver rad till debuggern. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Diagnostics](../)
* Library [Aspose.PDF for C++](../../)
