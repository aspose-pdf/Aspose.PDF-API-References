---
title: "System::EventHandler typedef"
linktitle: "EventHandler"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::EventHandler typedef. Representerar en metod som reagerar på och bearbetar en händelse. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller referens. Använd aldrig System::SmartPtr-klassen för att hantera objekt av denna typ i C++."
type: docs
weight: 11800
url: /sv/cpp/system/eventhandler/
---
## EventHandler typedef


Representerar en metod som reagerar på och bearbetar en händelse. Denna typ bör allokeras på stacken och skickas till funktioner som värde eller referens. Använd aldrig [System::SmartPtr](../smartptr/) klassen för att hantera objekt av denna typ.

```cpp
using System::EventHandler =  MulticastDelegate<void(System::SharedPtr<Object>, TEventArgs)>
```


## Se även

* Namespace [System](../)
* Library [Aspose.PDF for C++](../../)
