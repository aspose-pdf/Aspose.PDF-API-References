---
title: System::Collections::Generic::Stack class
linktitle: Stack
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Generic::Stack class. Stack class forward declaration in C++.'
type: docs
weight: 4600
url: /cpp/system.collections.generic/stack/
---
## Stack class


[Stack](./) class forward declaration.

```cpp
template<typename T>class Stack : public System::Collections::Generic::IEnumerable<T>
```


| Parameter | Description |
| --- | --- |
| T | Element type. |
## Nested classes

* Class [Enumerator](./enumerator/)
## Methods

| Method | Description |
| --- | --- |
| [AddRange](./addrange/)(IEnumerablePtr) | Puts elements into stack. |
| virtual [Clear](./clear/)() | Deletes all elements from stack. |
| virtual [Contains](./contains/)(const T\&) const | Checks if specific item is present in container; uses operator == for comparison. |
| [data](./data/)() | Internal data structure accessor. |
| [data](./data/)() const | Internal data structure accessor. |
| virtual [get_Count](./get_count/)() const | Gets number of elements in stack. |
| [GetEnumerator](./getenumerator/)() override | Gets enumerator to iterate through current stack. |
| [Peek](./peek/)() | Gets element from stack top, but keeps it in stack. |
| [Pop](./pop/)() | Gets element from top of the stack. |
| [Push](./push/)(const T\&) | Puts element of top of the stack. |
| [Stack](./stack/)() | Constructs empty stack. |
| [Stack](./stack/)(int) | Constructs empty stack. |
| [Stack](./stack/)(IEnumerablePtr) | Copy constructor. |
| virtual [ToArray](./toarray/)() | Converts stack to array. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Gets the implementation of begin const iterator for the current container. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Gets the implementation of begin iterator for the current container. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Gets the implementation of end const iterator for the current container. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Gets the implementation of end iterator for the current container. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [IEnumerablePtr](./ienumerableptr/) | Collection containing elements of same type. |
| [IEnumeratorPtr](./ienumeratorptr/) | [Enumerator](./enumerator/) type. |
| [stack_t](./stack_t/) | RTTI information. |
| [ValueType](./valuetype/) | Value type. |
## Remarks


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
  // Create the Stack-class instance.
  auto stack = MakeObject<Stack<int>>();

  // Fill the stack.
  stack->Push(1);
  stack->Push(2);
  stack->Push(3);

  // Print the last item of the stack. The Peek method doesn't remove an item from the stack.
  std::cout << stack->Peek() << std::endl;
  PrintItems(stack);

  // Print the last item of the stack. The Pop method removes an item from the stack.
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

## See Also

* Class [IEnumerable](../ienumerable/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
