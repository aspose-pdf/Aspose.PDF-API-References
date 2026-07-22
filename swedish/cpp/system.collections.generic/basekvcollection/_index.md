---
title: "System::Collections::Generic::BaseKVCollection‑klass"
linktitle: "BaseKVCollection"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Collections::Generic::BaseKVCollection‑klass. Innehåller gemensam kod för samlingar av nycklar eller värden. Objekt av denna klass bör endast allokeras med System::MakeObject()‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd pekaren för att skicka den till funktioner som argument i C++."
type: docs
weight: 700
url: /sv/cpp/system.collections.generic/basekvcollection/
---
## BaseKVCollection class


Innehåller gemensam kod för samlingar av nycklar eller värden. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd pekaren för att skicka den till funktioner som argument.

```cpp
template<typename Dict,typename KV>class BaseKVCollection : public System::Collections::Generic::IKVCollection<KV>
```


| Parameter | Beskrivning |
| --- | --- |
| Dict | [Dictionary](../dictionary/) typ. |
| KV | Nyckel‑ eller värdetyp, beroende på vilket gränssnitt som används. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [BaseKVCollection](./basekvcollection/)(const typename Dict::Ptr\&) | Skapar samling. |
| [CopyTo](./copyto/)(ArrayPtr\<KV\>, int) override | Kopierar data till befintliga arrayelement. |
| [get_Count](./get_count/)() const override | Hämtar antalet element. |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Möjliggör kompilering, men gör egentligen ingenting eftersom denna struktur inte äger någon data. |

## Se även

* Class [IKVCollection](../ikvcollection/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
