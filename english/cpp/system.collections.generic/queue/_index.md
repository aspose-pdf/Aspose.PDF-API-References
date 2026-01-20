---
title: System::Collections::Generic::Queue class
linktitle: Queue
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Generic::Queue class. Queue class forward declaration in C++.'
type: docs
weight: 3600
url: /cpp/system.collections.generic/queue/
---
## Queue class


[Queue](./) class forward declaration.

```cpp
template<typename T>class Queue : public System::Collections::Generic::IEnumerable<T>
```


| Parameter | Description |
| --- | --- |
| T | Element type. |
## Nested classes

* Class [Enumerator](./enumerator/)
## Methods

| Method | Description |
| --- | --- |
| virtual [Clear](./clear/)() | Deletes all elements in queue. |
| virtual [Contains](./contains/)(const T\&) const | Checks if queue contains specific element using operator == to compare elements. |
| [data](./data/)() | Underlying data structure accessor. |
| [data](./data/)() const | Underlying data structure accessor. |
| [Dequeue](./dequeue/)() | Gets item from the beginning of the queue. |
| [Enqueue](./enqueue/)(const T\&) | Puts item to the end of the queue. |
| virtual [get_Count](./get_count/)() const | Gets number of elements in queue. |
| [GetEnumerator](./getenumerator/)() override | Gets enumerator to iterate through the queue. |
| [Peek](./peek/)() | Gets item from the beginning of the queue, but does not remove it from queue. |
| [Queue](./queue/)() | Constructs empty queue. |
| [Queue](./queue/)(int) | Constructs empty queue. |
| [Queue](./queue/)(const SharedPtr\<IEnumerable\<T\>\>\&) | Copy constructor. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Gets the implementation of begin const iterator for the current container. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Gets the implementation of begin iterator for the current container. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Gets the implementation of end const iterator for the current container. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Gets the implementation of end iterator for the current container. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [IEnumerablePtr](./ienumerableptr/) | Container of same type elements. |
| [IEnumeratorPtr](./ienumeratorptr/) | [Enumerator](./enumerator/) type. |
| [queue_t](./queue_t/) | RTTI information. |
| [ValueType](./valuetype/) | This type. |
## Remarks


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
  // Create the Queue-class instance.
  auto queue = MakeObject<Queue<int>>();

  // Fill the queue.
  queue->Enqueue(1);
  queue->Enqueue(2);
  queue->Enqueue(3);

  // Print the first queue item. The Peek method doesn't remove an item from the queue.
  std::cout << queue->Peek() << std::endl;
  // Print the queue items.
  PrintItems(queue);

  // Print the first queue item. The Dequeue method removes an item from the queue.
  std::cout << queue->Dequeue() << std::endl;
  // Print the queue items.
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

## See Also

* Class [IEnumerable](../ienumerable/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
