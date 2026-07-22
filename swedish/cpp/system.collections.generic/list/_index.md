---
title: "System::Collections::Generic::List-klass"
linktitle: "List"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Collections::Generic::List-klass. Framåtdeklaration av List i C++."
type: docs
weight: 3300
url: /sv/cpp/system.collections.generic/list/
---
## List class


[List](./) forward declaration.

```cpp
template<typename T>class List : public virtual System::Object,
                                 public System::Collections::Generic::IList<T>
```


| Parameter | Beskrivning |
| --- | --- |
| T | Elementtyp. |
## Nested classes

* Class [Enumerator](./enumerator/)
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [_add_range](./_add_range/)(std::initializer_list\<T\>) | C++-specifik. |
| [Add](./add/)(const T\&) override | Lägger till element i slutet av listan. |
| [AddInitializer](./addinitializer/)(int, const T *) | Lägger till element i listan; används vid översättning av initialiserare. |
| [AddRange](./addrange/)(IEnumerablePtr) | Lägger till alla element från samlingen (eller sig själv) i slutet av den aktuella listan. |
| [AsReadOnly](./asreadonly/)() | Hämtar skrivskyddad referens till denna samling. |
| [begin](./begin/)() | Hämtar iterator till det första elementet i samlingen. |
| [begin](./begin/)() const | Hämtar iterator till det första elementet i den konstantkvalificerade samlingen. |
| [BinarySearch](./binarysearch/)(const T\&) const | Söker efter objekt i en sorterad lista. |
| [BinarySearch](./binarysearch/)(const T\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) const | Söker efter objekt i en sorterad lista. |
| [BinarySearch](./binarysearch/)(int, int, const T\&, const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) const | Söker efter objekt i en sorterad lista. |
| [cbegin](./cbegin/)() const | Hämtar iterator till det första const‑kvalificerade elementet i samlingen. |
| [cend](./cend/)() const | Hämtar iterator för ett icke‑existerande const‑kvalificerat element bakom samlingens slut. |
| [Clear](./clear/)() override | Raderar alla element. |
| [Contains](./contains/)(const T\&) const override | Kontrollerar om objektet finns i listan. |
| [ConvertAll](./convertall/)(Converter\<T, OutputType\>) | Skapar en lista med element konverterade till en annan typ. |
| [CopyTo](./copyto/)(System::ArrayPtr\<T\>, int) override | Kopierar listelement till befintliga array‑element. |
| [CopyTo](./copyto/)(const System::ArrayPtr\<T\>\&) | Kopierar alla element till befintliga array‑element. |
| [CopyTo](./copyto/)(int, const System::ArrayPtr\<T\>\&, int, int) | Kopierar element med start från det angivna indexet till befintliga array‑element. |
| [crbegin](./crbegin/)() const | Hämtar en omvänd iterator till det sista const‑kvalificerade elementet i samlingen (första i omvänd ordning). |
| [crend](./crend/)() const | Hämtar en omvänd iterator för ett icke‑existerande const‑kvalificerat element före samlingens början. |
| [data](./data/)() | Underliggande datastrukturs åtkomstfunktion. |
| [data](./data/)() const | Underliggande datastrukturs åtkomstfunktion. |
| [end](./end/)() | Hämtar iterator för ett icke‑existerande element bakom samlingens slut. |
| [end](./end/)() const | Hämtar iterator för ett icke‑existerande element bakom slutet av den const‑kvalificerade samlingen. |
| [Exists](./exists/)(System::Predicate\<T\>) | Kontrollerar om ett element som uppfyller ett specifikt predikat finns i listan. |
| [Find](./find/)(System::Predicate\<T\>) | Söker efter element som uppfyller ett specifikt predikat. |
| [FindAll](./findall/)(System::Predicate\<T\>) | Söker efter element som uppfyller ett specifikt predikat. |
| [FindIndex](./findindex/)(System::Predicate\<T\>) | Söker efter element som uppfyller ett specifikt predikat. |
| [FindIndex](./findindex/)(int, System::Predicate\<T\>) | Söker efter element som uppfyller ett specifikt predikat. |
| [FindIndex](./findindex/)(int, int, System::Predicate\<T\>) | Söker efter element som uppfyller ett specifikt predikat. |
| [FindLast](./findlast/)(System::Predicate\<T\>) | Söker efter det sista elementet som uppfyller ett specifikt predikat. |
| [ForEach](./foreach/)(System::Action\<T\>) | Tillämpar åtgärd på alla element i listan. |
| [get_Capacity](./get_capacity/)() const | Hämtar aktuell listkapacitet. |
| [get_Count](./get_count/)() const override | Hämtar antalet element i den aktuella listan. |
| [GetEnumerator](./getenumerator/)() override | Hämtar enumerator för att iterera genom listans element. |
| [GetRange](./getrange/)(int, int) | Skapar en skiva av listan. |
| [idx_get](./idx_get/)(int) const override | Hämtar element på en specifik position. |
| [idx_set](./idx_set/)(int, T) override | Sätter element på en specifik position. |
| [IndexOf](./indexof/)(const T\&) const override | Hämtar första indexet för ett specifikt objekt. |
| [IndexOf](./indexof/)(const T\&, int) const | Söker efter ett specifikt objekt i listan. |
| [Insert](./insert/)(int, const T\&) override | Infogar objekt på angiven position. |
| [InsertRange](./insertrange/)(int, IEnumerablePtr) | Infogar dataintervall på en specifik position. |
| [LastIndexOf](./lastindexof/)(const T\&) const | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den sista förekomsten i hela listan. |
| [LastIndexOf](./lastindexof/)(const T\&, int32_t) const | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den sista förekomsten inom intervallet av element i [List](./) som sträcker sig från det första elementet till det angivna indexet. |
| [LastIndexOf](./lastindexof/)(const T\&, int32_t, int32_t) const | Söker efter det angivna objektet och returnerar det nollbaserade indexet för den sista förekomsten inom intervallet av element i [List](./) som innehåller det angivna antalet element och slutar vid det angivna indexet. |
| [List](./list/)() | Skapar en tom lista. |
| [List](./list/)(int) | Skapar en lista med fördefinierad kapacitet. |
| [List](./list/)(IEnumerablePtr) | Kopieringskonstruktor. |
| [operator[]](./operator[]/)(int) | Åtkomstfunktion. |
| [operator[]](./operator[]/)(int) const | Åtkomstfunktion. |
| [rbegin](./rbegin/)() | Hämtar en omvänd iterator till det sista elementet i samlingen (första i omvänd ordning). |
| [rbegin](./rbegin/)() const | Hämtar en omvänd iterator till det sista elementet i den const‑kvalificerade samlingen (första i omvänd ordning). |
| [Remove](./remove/)(const T\&) override | Tar bort den första instansen av ett specifikt objekt från listan. |
| [RemoveAll](./removeall/)(Predicate\<T\>) | Tar bort alla element som matchar ett specifikt predikat. |
| [RemoveAt](./removeat/)(int) override | Tar bort objektet på angiven position. |
| [RemoveRange](./removerange/)(int, int) | Tar bort ett segment av listan. |
| [rend](./rend/)() | Hämtar en omvänd iterator för ett icke‑existerande element före samlingens början. |
| [rend](./rend/)() const | Hämtar en omvänd iterator för ett icke‑existerande element före den const‑kvalificerade samlingens början. |
| [Reverse](./reverse/)() | Vänder på elementordningen för hela listan. |
| [Reverse](./reverse/)(int, int) | Vänder på elementordningen för listsegmentet. |
| [set_Capacity](./set_capacity/)(int) | Ställer in listans kapacitet. |
| [Sort](./sort/)(const SharedPtr\<System::Collections::Generic::IComparer\<T\>\>\&) | Sorterar element i listan. |
| [Sort](./sort/)() | Sorterar element i listan med standardjämförare. |
| [Sort](./sort/)(int, int, SharedPtr\<System::Collections::Generic::IComparer\<T\>\>) | Sorterar element i listsegmentet. |
| [Sort](./sort/)(Comparison\<T\>, bool) | Sorterar element i listan. |
| [ToArray](./toarray/)() const | Konverterar lista till array. |
| [TrimExcess](./trimexcess/)() | Justerar listans kapacitet så att den passar dess storlek. |
| [TrueForAll](./trueforall/)(System::Predicate\<T\>) | Bestämmer om varje element i samlingen matchar villkoren som definieras av det angivna predikatet. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Hämtar implementationen av begin const-iterator för den aktuella containern. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Hämtar implementationen av begin-iterator för den aktuella containern. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Hämtar implementationen av end const iterator för den aktuella behållaren. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Hämtar implementationen av end iterator för den aktuella behållaren. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [BaseType](./basetype/) | Gränssnittstyp. |
| [const_iterator](./const_iterator/) | Typ för konstant iterator. |
| [const_reverse_iterator](./const_reverse_iterator/) | Typ för konstant omvänd iterator. |
| [IEnumerablePtr](./ienumerableptr/) | Behållare som håller element av samma typ som vi har. |
| [IEnumeratorPtr](./ienumeratorptr/) | [Enumerator](./enumerator/) typ. |
| [iterator](./iterator/) | Iterator-typ. |
| [reverse_iterator](./reverse_iterator/) | Omvänd iterator-typ. |
| [ValueType](./valuetype/) | Denna typ. |
| [vector_t](./vector_t/) | RTTI-information. |
## Anmärkningar


[List](./) - wrapper around std::vector to be used in translated code. Requires operator == to be impemented for element type. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.


```cpp
#include <system/collections/list.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  // Skapa den första listan.
  auto list1 = MakeObject<List<int>>();

  // Fyll den första listan.
  list1->Add(3);
  list1->Add(1);
  list1->Add(-5);
  list1->Add(8);

  // Sortera den första listan.
  // De första listobjekten kommer att vara: {-5, 1, 3, 8}
  list1->Sort();

  // Ta bort objektet på index 2.
  // De första listobjekten kommer att vara: {-5, 1, 8}
  list1->RemoveAt(2);

  // Infoga objektet på index 1.
  // De första listobjekten kommer att vara: {-5, 15, 1, 8}
  list1->Insert(1, 15);

  // Skapa den andra listan.
  auto list2 = MakeObject<List<int>>();

  // Fyll i den andra listan.
  list2->Add(10);
  list2->Add(20);
  list2->Add(30);

  // Lägg till element från den andra listan till den första.
  list1->AddRange(list2);

  // Skriv ut elementen i den första listan.
  for (const auto item: list1)
  {
    std::cout << item << ' ';
  }

  return 0;
}
/*
This code example produces the following output:
-5 15 1 8 10 20 30
*/
```

## Se även

* Class [Object](../../system/object/)
* Class [IList](../ilist/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
