---
title: "System::Collections::BitArray-klass"
linktitle: "BitArray"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Collections::BitArray-klass. En array av bitar som kan adresseras via index. Objekt av denna klass bör endast allokeras med hjälp av System::MakeObject()-funktionen. Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller assert-fel. Omslut alltid denna klass i en System::SmartPtr-pekare och använd denna pekare för att skicka den till funktioner som argument i C++."
type: docs
weight: 100
url: /sv/cpp/system.collections/bitarray/
---
## BitArray class


[Array](../../system/array/) of bits which can be addressed by index. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class BitArray : public virtual System::Object,
                 public System::Collections::Generic::ICollection<bool>
```

## Nested classes

* Class [Enumerator](./enumerator/)
* Class [Reference](./reference/)
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Add](./add/)(const bool\&) override | Lägger till värde i slutet av behållaren. |
| [And](./and/)(const BitArrayPtr\&) | Beräknar bitvis 'and' mellan två BitSets. |
| [BitArray](./bitarray/)(const bitset\&) | Kopieringskonstruktor. |
| [BitArray](./bitarray/)(const BitArray\&) | Kopieringskonstruktor. |
| [BitArray](./bitarray/)(const BitArrayPtr\&) | Kopieringskonstruktor. |
| [BitArray](./bitarray/)(const System::ArrayPtr\<bool\>\&) | Kopieringskonstruktor. |
| [BitArray](./bitarray/)(const System::ArrayPtr\<uint8_t\>\&) | Kopieringskonstruktor. |
| [BitArray](./bitarray/)(const System::ArrayPtr\<int\>\&) | Kopieringskonstruktor. |
| [BitArray](./bitarray/)(int, bool) | Fyllkonstruktor. |
| [Clear](./clear/)() override | Raderar alla element. |
| [Contains](./contains/)(const bool\&) const override | Kontrollerar om ett specifikt värde finns i behållaren. Inte implementerat. |
| [CopyTo](./copyto/)(System::ArrayPtr\<bool\>, int) override | Kopierar data till befintliga arrayelement. |
| [data](./data/)() | Åtkomst till underliggande datastruktur. |
| [data](./data/)() const | Åtkomst till underliggande datastruktur. |
| [Get](./get/)(int) const | Hämtar [BitArray](./) element. |
| [get_Count](./get_count/)() const override | Hämtar behållarens storlek. |
| [get_Length](./get_length/)() const | Hämtar behållarens storlek. |
| [GetEnumerator](./getenumerator/)() override | Skapar enumeratorobjekt. |
| [idx_get](./idx_get/)(int) const | Getter-funktion. |
| [idx_set](./idx_set/)(int, bool) | Setter-funktion. |
| [Not](./not/)() | Negerar BitSet. |
| [operator!=](./operator!=/)(const BitArray\&) const | Bitvis jämförelseoperator. |
| [operator==](./operator==/)(const BitArray\&) const | Bitvis jämförelseoperator. |
| [operator[]](./operator[]/)(int) | Åtkomstfunktion. |
| [Or](./or/)(const BitArrayPtr\&) | Beräknar bitvis 'or' mellan två BitSets. |
| [Remove](./remove/)(const bool\&) override | Returnerar första förekomsten av angivet värde. Ej implementerad. |
| [Set](./set/)(int, bool) | Sätter [BitArray](./) element. |
| [SetAll](./setall/)(bool) | Sätter alla element till ett specifikt värde. |
| [SetTemplateWeakPtr](./settemplateweakptr/)(uint32_t) override | Formell implementation av svag mallargumentmekanism; ej tillämplig för denna klass. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Hämtar implementationen av begin const-iterator för den aktuella containern. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Hämtar implementationen av begin-iterator för den aktuella containern. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Hämtar implementationen av end const iterator för den aktuella behållaren. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Hämtar implementationen av end iterator för den aktuella behållaren. |
| [Xor](./xor/)(const BitArrayPtr\&) | Beräknar bitvis 'xor' mellan två BitSets. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [bitset](./bitset/) | RTTI-information. |
## Anmärkningar



```cpp
#include <system/collections/bitarray.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

void Print(const System::SmartPtr<System::Collections::Generic::IEnumerable<bool>> &bitArray)
{
  for (const auto item: bitArray)
  {
    std::cout << item << ' ';
  }
  std::cout << std::endl;
}

int main()
{
  // Skapar en ny instans av BitArray-klassen.
  auto bitArray = MakeObject<System::Collections::BitArray>(3);

  // Skriv ut värden.
  Print(bitArray);

  return 0;
}
/*
This code example produces the following output:
0 0 0
*/
```

## Se även

* Class [Object](../../system/object/)
* Class [ICollection](../../system.collections.generic/icollection/)
* Namespace [System::Collections](../)
* Library [Aspose.PDF for C++](../../)
