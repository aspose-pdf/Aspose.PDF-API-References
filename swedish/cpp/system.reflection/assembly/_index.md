---
title: "System::Reflection::Assembly-klass"
linktitle: "Assembly"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Reflection::Assembly-klass. Reflektionsklass som beskriver en assembly. Stödet är begränsat eftersom reglerna skiljer sig mycket mellan C# och C++. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kommer att leda till körfel och/eller assertionsfel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 100
url: /sv/cpp/system.reflection/assembly/
---
## Assembly class


[Reflection](../) class describing assembly. Support is limited as the rules are quite different between C# and C++. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Assembly : public System::Object
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Assembly](./assembly/)() | Konstruktor. |
| virtual [get_CodeBase](./get_codebase/)() const | Hämtar katalogen för aktuell assembly. Stödet är begränsat. |
| virtual [get_FullName](./get_fullname/)() const | Hämtar assemblyns fullständiga namn. |
| virtual [get_Location](./get_location/)() const | Hämtar assemblyns plats. Inte implementerad. |
| static [GetAssembly](./getassembly/)(const TypeInfo\&) | Hämtar assemblyn som definierar en specifik typ. |
| static [GetCallingAssembly](./getcallingassembly/)() | Hämtar den anropande assemblyn. |
| static [GetEntryAssembly](./getentryassembly/)() | Hämtar start‑assemblyn. |
| static [GetExecutingAssembly](./getexecutingassembly/)() | Hämtar den körande assemblyn. |
| virtual [GetManifestResourceNames](./getmanifestresourcenames/)() const | Hämtar namn på manifestresurser. |
| virtual [GetManifestResourceStream](./getmanifestresourcestream/)(String) const | Hämtar ström som är ansluten till manifestresursen. |
| virtual [GetName](./getname/)() const | Hämtar assembly‑namn. |
| virtual [GetTypes](./gettypes/)() const | Hämtar typer som deklarerats av assemblyn. |
## Se även

* Class [Object](../../system/object/)
* Namespace [System::Reflection](../)
* Library [Aspose.PDF for C++](../../)
