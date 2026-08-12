---
title: "System::Collections::ObjectModel::ReadOnlyCollection-klass"
linktitle: "ReadOnlyCollection"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Collections::ObjectModel::ReadOnlyCollection-klass. Omsluter en specifik behållare för att komma åt den i skrivskyddat läge. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller assertionfel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 300
url: /sv/cpp/system.collections.objectmodel/readonlycollection/
---
## ReadOnlyCollection class


Omsluter en specifik behållare för att komma åt den i skrivskyddat läge. Objekt av denna klass bör endast allokeras med hjälp av funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller assertionfel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
template<typename T>class ReadOnlyCollection : public virtual System::Object,
                                               public System::Collections::Generic::IList<T>
```


| Parameter | Beskrivning |
| --- | --- |
| T | Elementtyp. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Contains](./contains/)(const T\&) const override | Kontrollerar om behållaren innehåller ett specifikt objekt. |
| [CopyTo](./copyto/)(System::ArrayPtr\<T\>, int) override | Kopierar behållarelement till befintliga arrayelement. |
| [get_Count](./get_count/)() const override | Hämtar antalet element i behållaren. |
| [get_IsReadOnly](./get_isreadonly/)() const override | Kontrollerar om samlingen är skrivskyddad. |
| [GetEnumerator](./getenumerator/)() override | Hämtar samlingens enumerator. |
| [idx_get](./idx_get/)(int) const override | Hämtar objektet på en specifik position. |
| [IndexOf](./indexof/)(const T\&) const override | Söker efter ett specifikt objekt i samlingen. |
| [ReadOnlyCollection](./readonlycollection/)(const SharedPtr\<Generic::IList\<T\>\>\&) | Omsluter en skrivskyddad samling runt en specifik samling. |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Gör ingenting eftersom en skrivskyddad samling bara omsluter data och lagrar inget. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Hämtar implementationen av begin const-iterator för den aktuella containern. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Hämtar implementationen av begin-iterator för den aktuella containern. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Hämtar implementationen av end const iterator för den aktuella behållaren. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Hämtar implementationen av end iterator för den aktuella behållaren. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [BaseType](./basetype/) | Implementerat gränssnitt. |
| [IEnumeratorPtr](./ienumeratorptr/) | Behållare av samma element. |
| [ValueType](./valuetype/) | Värdetyp. |

## Se även

* Class [Object](../../system/object/)
* Class [IList](../../system.collections.generic/ilist/)
* Namespace [System::Collections::ObjectModel](../)
* Library [Aspose.PDF for C++](../../)
