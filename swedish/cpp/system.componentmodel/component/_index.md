---
title: "System::ComponentModel::Component class"
linktitle: "Component"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::ComponentModel::Component class. Dummy‑klass för att göra översatt kod som använder Component‑klassen kompilerbar. Objekt av denna klass bör endast allokeras med System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller assert‑fel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 400
url: /sv/cpp/system.componentmodel/component/
---
## Component class


Dummy-klass för att göra översatt kod som använder [Component](./)-klassen kompilerbar. Objekt av denna klass bör endast allokeras med hjälp av [System::MakeObject()](../../system/makeobject/)-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Wrappa alltid denna klass i en [System::SmartPtr](../../system/smartptr/)-pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
class Component : public System::MarshalByRefObject,
                  public System::ComponentModel::IComponent
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Component](./component/)() | RTTI-information. |
| [Dispose](./dispose/)(bool) | Stöd för disposable‑mönster; gör ingenting. |
| [get_DesignMode](./get_designmode/)() | Kontrollerar om komponenten är i designläge. |
## Se även

* Class [MarshalByRefObject](../../system/marshalbyrefobject/)
* Class [IComponent](../icomponent/)
* Namespace [System::ComponentModel](../)
* Library [Aspose.PDF for C++](../../)
