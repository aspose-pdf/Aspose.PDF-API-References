---
title: "System::Collections::Generic::Stack-klass"
linktitle: "Stack"
second_title: "Aspose.PDF för C++ API-referens"
description: "System::Collections::Generic::Stack-klass. Framåtredeklaration av Stack-klass i C++."
type: docs
weight: 4600
url: /sv/cpp/system.collections.generic/stack/
---
## Stack class


[Stack](./) class forward declaration.

```cpp
template<typename T>class Stack : public System::Collections::Generic::IEnumerable<T>
```


| Parameter | Beskrivning |
| --- | --- |
| T | Elementtyp. |
## Nested classes

* Class [Enumerator](./enumerator/)
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [AddRange](./addrange/)(IEnumerablePtr) | Lägger till element i stacken. |
| virtual [Clear](./clear/)() | Raderar alla element från stacken. |
| virtual [Contains](./contains/)(const T\&) const | Kontrollerar om ett specifikt objekt finns i behållaren; använder operator == för jämförelse. |
| [data](./data/)() | Intern åtkomst till datastruktur. |
| [data](./data/)() const | Intern åtkomst till datastruktur. |
| virtual [get_Count](./get_count/)() const | Hämtar antalet element i stacken. |
| [GetEnumerator](./getenumerator/)() override | Hämtar en enumerator för att iterera genom den aktuella stacken. |
| [Peek](./peek/)() | Hämtar elementet från stackens topp men behåller det i stacken. |
| [Pop](./pop/)() | Hämtar elementet från stackens topp. |
| [Push](./push/)(const T\&) | Lägger in elementet högst upp i stacken. |
| [Stack](./stack/)() | Skapar en tom stack. |
| [Stack](./stack/)(int) | Skapar en tom stack. |
| [Stack](./stack/)(IEnumerablePtr) | Kopieringskonstruktor. |
| virtual [ToArray](./toarray/)() | Konverterar stacken till en array. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Hämtar implementationen av begin const-iterator för den aktuella containern. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Hämtar implementationen av begin-iterator för den aktuella containern. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Hämtar implementationen av end const iterator för den aktuella behållaren. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Hämtar implementationen av end iterator för den aktuella behållaren. |
## Typedefs

| Typedef | Beskrivning |
| --- | --- |
| [IEnumerablePtr](./ienumerableptr/) | Samling som innehåller element av samma typ. |
| [IEnumeratorPtr](./ienumeratorptr/) | [Enumerator](./enumerator/) typ. |
| [stack_t](./stack_t/) | RTTI-information. |
| [ValueType](./valuetype/) | Värdetyp. |
## Anmärkningar


[Stack](./) class wrapping std::list. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.


```cpp
#include <system/collections/stack.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

void PrintItems(const SmartPtr<IEnumerable<int>> &stack)
{
  for (const auto item: stack)
  {
    std::cout << item << ' ';
  }
  std::cout << std::endl;
}

int main()
{
  // Skapa en instans av Stack-klassen.
  auto stack = MakeObject<Stack<int>>();

  // Fyll stacken.
  stack->Push(1);
  stack->Push(2);
  stack->Push(3);

  // Skriv ut det sista objektet i stacken. Peek‑metoden tar inte bort ett objekt från stacken.
  std::cout << stack->Peek() << std::endl;
  PrintItems(stack);

  // Skriv ut det sista objektet i stacken. Pop‑metoden tar bort ett objekt från stacken.
  std::cout << stack->Pop() << std::endl;
  PrintItems(stack);

  return 0;
}
/*
This code example produces the following output:
3
3 2 1
3
2 1
*/
```

## Se även

* Class [IEnumerable](../ienumerable/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
