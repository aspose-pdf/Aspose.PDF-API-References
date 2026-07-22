---
title: "System::Collections::Generic::Queue klass"
linktitle: "Queue"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Collections::Generic::Queue klass. Köklass framåtriktad deklaration i C++."
type: docs
weight: 3600
url: /sv/cpp/system.collections.generic/queue/
---
## Queue class


[Queue](./) class forward declaration.

```cpp
template<typename T>class Queue : public System::Collections::Generic::IEnumerable<T>
```


| Parameter | Beskrivning |
| --- | --- |
| T | Elementtyp. |
## Nested classes

* Class [Enumerator](./enumerator/)
## Metoder

| Metod | Beskrivning |
| --- | --- |
| virtual [Clear](./clear/)() | Tar bort alla element i kön. |
| virtual [Contains](./contains/)(const T\&) const | Kontrollerar om kön innehåller ett specifikt element med operatorn == för att jämföra element. |
| [data](./data/)() | Åtkomst till underliggande datastruktur. |
| [data](./data/)() const | Åtkomst till underliggande datastruktur. |
| [Dequeue](./dequeue/)() | Hämtar objekt från början av kön. |
| [Enqueue](./enqueue/)(const T\&) | Lägger till objekt i slutet av kön. |
| virtual [get_Count](./get_count/)() const | Hämtar antalet element i kön. |
| [GetEnumerator](./getenumerator/)() override | Hämtar enumerator för att iterera genom kön. |
| [Peek](./peek/)() | Hämtar objekt från början av kön, men tar inte bort det från kön. |
| [Queue](./queue/)() | Skapar en tom kö. |
| [Queue](./queue/)(int) | Skapar en tom kö. |
| [Queue](./queue/)(const SharedPtr\<IEnumerable\<T\>\>\&) | Kopieringskonstruktor. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Hämtar implementationen av begin const-iterator för den aktuella containern. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Hämtar implementationen av begin-iterator för den aktuella containern. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Hämtar implementationen av end const iterator för den aktuella behållaren. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Hämtar implementationen av end iterator för den aktuella behållaren. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [IEnumerablePtr](./ienumerableptr/) | Behållare med element av samma typ. |
| [IEnumeratorPtr](./ienumeratorptr/) | [Enumerator](./enumerator/) typ. |
| [queue_t](./queue_t/) | RTTI-information. |
| [ValueType](./valuetype/) | Denna typ. |
## Anmärkningar


[Queue](./) container wrapping STL list. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.


```cpp
#include <system/collections/queue.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

void PrintItems(const SmartPtr<IEnumerable<int>> &queue)
{
  for (const int item: queue)
  {
    std::cout << item << ' ';
  }
  std::cout << std::endl;
}

int main()
{
  // Skapa en instans av Queue-klassen.
  auto queue = MakeObject<Queue<int>>();

  // Fyll kön.
  queue->Enqueue(1);
  queue->Enqueue(2);
  queue->Enqueue(3);

  // Skriv ut det första köobjektet. Peek-metoden tar inte bort ett objekt från kön.
  std::cout << queue->Peek() << std::endl;
  // Skriv ut köobjekten.
  PrintItems(queue);

  // Skriv ut det första köobjektet. Dequeue-metoden tar bort ett objekt från kön.
  std::cout << queue->Dequeue() << std::endl;
  // Skriv ut köobjekten.
  PrintItems(queue);

  return 0;
}
/*
This code example produces the following output:
1
1 2 3
1
2 3
*/
```

## Se även

* Class [IEnumerable](../ienumerable/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
