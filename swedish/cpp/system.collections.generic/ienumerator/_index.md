---
title: "System::Collections::Generic::IEnumerator class"
linktitle: "IEnumerator"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Collections::Generic::IEnumerator-klass. Gränssnitt för en enumerator som kan användas för att iterera genom vissa element. Objekt av denna klass bör endast allokeras med System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en System::SmartPtr‑pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 2300
url: /sv/cpp/system.collections.generic/ienumerator/
---
## IEnumerator class


Gränssnitt för enumerator som kan användas för att iterera genom vissa element. Objekt av denna klass bör endast allokeras med [System::MakeObject()](../../system/makeobject/) funktionen. Skapa aldrig en instans av denna typ på stacken eller med operatorn new, eftersom det kommer att leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.

```cpp
template<typename T>class IEnumerator : public virtual System::IDisposable,
                                        public System::Details::EnumeratorBasedIterator<T>,
                                        protected System::Details::IteratorPointerUpdater<T, false>
```


| Parameter | Beskrivning |
| --- | --- |
| T | Elementtyp. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [AsVirtualizedIterator](./asvirtualizediterator/)() | Förbereder iteratorn för att användas av VirtualizedIterator-klassen. |
| [CloneIterator](./cloneiterator/)() const override | Klonar aktuell iterator. |
| virtual [Current](./current/)() const | Hämtar aktuellt element. |
| virtual [get_Current](./get_current/)() const | Hämtar aktuellt element. |
| [IEnumerator](./ienumerator/)() |  |
| [IncrementIterator](./incrementiterator/)() override | Flyttar iteratorn ett steg framåt. |
| [InitializeIterator](./initializeiterator/)() override | Utför det första [MoveNext()](./movenext/)‑anropet och förbereder enumeratorobjektet för att användas av VirtualizedIterator. |
| [MarkOwnedByVirtualizedIterator](./markownedbyvirtualizediterator/)() | Markerar enumeratorn som ägs av den virtualiserade iteratorn. |
| virtual [MoveNext](./movenext/)() | Flyttar enumerator till nästa element. Om inget element har refererats tidigare, sätts referensen till det första tillgängliga elementet. Om behållarens slut har nåtts, görs inget. |
| virtual [Reset](./reset/)() | Återställer enumeratorn till positionen före det första elementet. |
| virtual [~IEnumerator](./~ienumerator/)() |  |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [ValueType](./valuetype/) | Värdetyp. |
## Anmärkningar



```cpp
#include <system/collections/list.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  // Skapa en instans av List-klassen.
  auto collection = MakeObject<List<int>>();

  // Fyll listan.
  collection->Add(1);
  collection->Add(2);
  collection->Add(3);

  // Hämta enumeratorn för listan.
  auto enumerator = collection->GetEnumerator();

  while (enumerator->MoveNext())
  {
    // Hämta det aktuella elementet och skriv ut det.
    std::cout << enumerator->get_Current() << ' ';
  }

  // Återställ enumeratorn.
  enumerator->Reset();

  return 0;
}
/*
This code example produces the following output:
1 2 3
*/
```

## Se även

* Class [IDisposable](../../system/idisposable/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
