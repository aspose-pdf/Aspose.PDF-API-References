---
title: "System::Collections::Concurrent::ConcurrentDictionary klass"
linktitle: "ConcurrentDictionary"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Collections::Concurrent::ConcurrentDictionary-klass. Trådsäker ordboksimplementation. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller assert-fel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 100
url: /sv/cpp/system.collections.concurrent/concurrentdictionary/
---
## ConcurrentDictionary class


Trådsäker ordboksimplementation. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/)‑funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller assert-fel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/)‑pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
template<class TKey,class TValue>class ConcurrentDictionary : public System::Collections::Generic::Dictionary<TKey, TValue>
```


| Parameter | Beskrivning |
| --- | --- |
| TKey | Nyckeltyp. |
| TValue | Värdetyp. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Add](./add/)(const TKey\&, const TValue\&) override | Lägger till värde i ordboken. |
| [Clear](./clear/)() override | Raderar alla element i behållaren. |
| [CopyTo](./copyto/)(ArrayPtr\<System::Collections::Generic::KeyValuePair\<TKey, TValue\>\>, int) override | Kopierar behållarelement till befintliga arrayelement. |
| [get_KeysInternal](./get_keysinternal/)() const override | Hämtar omslagskollektion för att komma åt ordbokens nycklar. |
| [idx_set](./idx_set/)(const TKey\&, TValue) override | RTTI-information. |
| [Remove](./remove/)(const TKey\&) override | Tar bort element från behållaren. |
| [TryAdd](./tryadd/)(const TKey\&, const TValue\&) | Försöker lägga till nyckel/värde-par i ordboken. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [BaseType](./basetype/) | Implementationstyp. |
| [ThisType](./thistype/) | Denna typ. |
## Anmärkningar



```cpp
#include <system/collections/concurrent/concurrent_dictionary.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  const int itemsCount = 32;

  // Skapa en instans av ConcurrentDictionary-klassen.
  auto concurrentDictionary = MakeObject<ConcurrentDictionary<int, int>>();

  // Fyll den samtidiga ordboken.
  for (auto i = 0; i < itemsCount; ++i)
  {
    concurrentDictionary->Add(i, i * i);
  }

  Console::WriteLine(concurrentDictionary->idx_get(3));

  return 0;
}
/*
This code example produces the following output:
9
*/
```

## Se även

* Class [Dictionary](../../system.collections.generic/dictionary/)
* Namespace [System::Collections::Concurrent](../)
* Library [Aspose.PDF for C++](../../)
