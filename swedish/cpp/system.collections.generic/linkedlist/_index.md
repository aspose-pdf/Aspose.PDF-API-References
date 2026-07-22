---
title: "System::Collections::Generic::LinkedList klass"
linktitle: "LinkedList"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Collections::Generic::LinkedList klass. Framåtriktad deklaration av LinkedList i C++."
type: docs
weight: 3100
url: /sv/cpp/system.collections.generic/linkedlist/
---
## LinkedList class


[LinkedList](./) forward declaration.

```cpp
template<typename T>class LinkedList : public virtual System::Object,
                                       public System::Collections::Generic::ICollection<T>,
                                       private System::Collections::Invalidatable
```


| Parameter | Beskrivning |
| --- | --- |
| T | Innehållen värdetyp. |
## Nested classes

* Class [Enumerator](./enumerator/)
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [Add](./add/)(const T\&) override | Lägger till **element** i slutet av listan. |
| [AddAfter](./addafter/)(const SharedPtr\<LinkedListNode\<T\>\>\&, const T\&) | Lägger till **element** efter **node** i listan. |
| [AddAfter](./addafter/)(const SharedPtr\<LinkedListNode\<T\>\>\&, const SharedPtr\<LinkedListNode\<T\>\>\&) | Lägger till **newNode** efter **node** i listan. |
| [AddBefore](./addbefore/)(const SharedPtr\<LinkedListNode\<T\>\>\&, const T\&) | Lägger till **element** före **node** i listan. |
| [AddBefore](./addbefore/)(const SharedPtr\<LinkedListNode\<T\>\>\&, const SharedPtr\<LinkedListNode\<T\>\>\&) | Lägger till **newNode** före **node** i listan. |
| [AddFirst](./addfirst/)(const T\&) | Lägger till **element** i början av listan. |
| [AddFirst](./addfirst/)(const SharedPtr\<LinkedListNode\<T\>\>\&) | Lägger till **newNode** i början av listan. |
| [AddLast](./addlast/)(const T\&) | Lägger till **element** i slutet av listan. |
| [AddLast](./addlast/)(const SharedPtr\<LinkedListNode\<T\>\>\&) | Lägger till **newNode** i slutet av listan. |
| [begin](./begin/)() | Hämtar iterator till det första elementet i samlingen. |
| [begin](./begin/)() const | Hämtar iterator till det första elementet i den konstantkvalificerade samlingen. |
| [cbegin](./cbegin/)() const | Hämtar iterator till det första const‑kvalificerade elementet i samlingen. |
| [cend](./cend/)() const | Hämtar iterator för ett icke‑existerande const‑kvalificerat element bakom samlingens slut. |
| [Clear](./clear/)() override | Raderar alla element i listan. |
| [Contains](./contains/)(const T\&) const override | Kontrollerar om **element** finns i listan. |
| [CopyTo](./copyto/)(ArrayPtr\<T\>, int) override | Kopierar behållardata till befintliga arrayelement. |
| [crbegin](./crbegin/)() const | Hämtar en omvänd iterator till det sista const‑kvalificerade elementet i samlingen (första i omvänd ordning). |
| [crend](./crend/)() const | Hämtar en omvänd iterator för ett icke‑existerande const‑kvalificerat element före samlingens början. |
| [end](./end/)() | Hämtar iterator för ett icke‑existerande element bakom samlingens slut. |
| [end](./end/)() const | Hämtar iterator för ett icke‑existerande element bakom slutet av den const‑kvalificerade samlingen. |
| [Find](./find/)(const T\&) const | Utför sökning i framåtriktning av ett **element** i listan. |
| [FindLast](./findlast/)(const T\&) const | Utför sökning i omvänd riktning av ett **element** i listan. |
| [get_Count](./get_count/)() const override | Hämtar antalet element i listan. |
| [get_First](./get_first/)() const | Hämtar pekare till det första elementet i listan. |
| [get_Last](./get_last/)() const | Hämtar pekare till det sista elementet i listan. |
| [GetEnumerator](./getenumerator/)() override | Hämtar enumerator för att iterera genom aktuell [LinkedList](./). |
| [LinkedList](./linkedlist/)() | Skapar en tom [LinkedList](./). |
| [LinkedList](./linkedlist/)(const SharedPtr\<IEnumerable\<T\>\>\&) | Kopieringskonstruktor. |
| [rbegin](./rbegin/)() | Hämtar en omvänd iterator till det sista elementet i samlingen (första i omvänd ordning). |
| [rbegin](./rbegin/)() const | Hämtar en omvänd iterator till det sista elementet i den const‑kvalificerade samlingen (första i omvänd ordning). |
| [Remove](./remove/)(const T\&) override | Tar bort den första förekomsten av det specificerade **element** från listan. |
| [Remove](./remove/)(const SharedPtr\<LinkedListNode\<T\>\>\&) | Tar bort noden från listan. |
| [RemoveFirst](./removefirst/)() | Tar bort den första noden från listan. |
| [RemoveLast](./removelast/)() | Tar bort den sista noden från listan. |
| [rend](./rend/)() | Hämtar en omvänd iterator för ett icke‑existerande element före samlingens början. |
| [rend](./rend/)() const | Hämtar en omvänd iterator för ett icke‑existerande element före den const‑kvalificerade samlingens början. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Hämtar implementationen av begin const-iterator för den aktuella containern. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Hämtar implementationen av begin-iterator för den aktuella containern. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Hämtar implementationen av end const iterator för den aktuella behållaren. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Hämtar implementationen av end iterator för den aktuella behållaren. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [const_iterator](./const_iterator/) | Typ för konstant iterator. |
| [const_reverse_iterator](./const_reverse_iterator/) | Typ för konstant omvänd iterator. |
| [iterator](./iterator/) | Iterator-typ. |
| [list_t](./list_t/) | Underliggande datatyp. |
| [reverse_iterator](./reverse_iterator/) | Omvänd iterator-typ. |
## Anmärkningar


Linked list-behållare. Implementerar ett omslag över std::list. Objekt av denna klass bör endast allokeras med hjälp av funktionen [System::MakeObject()](../../system/makeobject/). Skapa aldrig en instans av denna typ på stacken eller med operator new, eftersom det kan leda till körfel och/eller påståendefel. Omslut alltid denna klass i en [System::SmartPtr](../../system/smartptr/) pekare och använd denna pekare för att skicka den till funktioner som argument.


```cpp
#include <system/collections/linkedlist.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  // Skapa en instans av LinkedList-klassen.
  auto list = MakeObject<LinkedList<int>>();

  // Fyll den länkade listan.
  list->AddFirst(1);
  list->AddLast(30);
  list->AddAfter(list->get_First(), 15);
  list->AddBefore(list->get_Last(), 25);

  // Skriv ut objekten i den länkade listan.
  for (const auto item: list)
  {
    std::cout << item << ' ';
  }

  return 0;
}
/*
This code example produces the following output:
1 15 25 30
*/
```

## Se även

* Class [Object](../../system/object/)
* Class [ICollection](../icollection/)
* Class [Invalidatable](../../system.collections/invalidatable/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
