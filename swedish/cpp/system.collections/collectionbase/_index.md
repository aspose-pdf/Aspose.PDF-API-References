---
title: "System::Collections::CollectionBase klass"
linktitle: "CollectionBase"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Collections::CollectionBase klass. Tillhandahåller en abstrakt basklass för en starkt typad samling i C++."
type: docs
weight: 300
url: /sv/cpp/system.collections/collectionbase/
---
## CollectionBase class


Tillhandahåller en abstrakt basklass för en starkt typad samling.

```cpp
template<typename T>class CollectionBase : public virtual System::Collections::Generic::IEnumerable<T>
```


| Parameter | Beskrivning |
| --- | --- |
| T | Typ av element i samlingen |
## Nested classes

* Class [ListImpl](./listimpl/)
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Clear](./clear/)() | Tar bort alla objekt från samlingsinstansen. Denna metod kan inte åsidosättas. |
| [get_Capacity](./get_capacity/)() | Returnerar antalet element som samlingen kan innehålla. |
| [get_Count](./get_count/)() | Returnerar antalet element som finns i samlingsinstansen. Denna metod kan inte åsidosättas. |
| [GetEnumerator](./getenumerator/)() override | Returnerar en enumerator som itererar genom samlingsinstansen. |
| [RemoveAt](./removeat/)(int32_t) | Tar bort elementet på det angivna indexet i samlingsinstansen. Denna metod är inte åsidosättningsbar. |
| [set_Capacity](./set_capacity/)(int32_t) | Ställer in antalet element som samlingen kan innehålla. |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Ställ in n'te mallargument till en svag pekare (istället för delad). Tillåter att byta pekare i behållare till svagt läge. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [Ptr](./ptr/) | Ett alias för en delad pekare till en instans av denna klass. |

## Se även

* Class [IEnumerable](../../system.collections.generic/ienumerable/)
* Namespace [System::Collections](../)
* Library [Aspose.PDF for C++](../../)
