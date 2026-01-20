---
title: System::Collections::Generic::LinkedList class
linktitle: LinkedList
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Generic::LinkedList class. LinkedList forward declaration in C++.'
type: docs
weight: 3100
url: /cpp/system.collections.generic/linkedlist/
---
## LinkedList class


[LinkedList](./) forward declaration.

```cpp
template<typename T>class LinkedList : public virtual System::Object,
                                       public System::Collections::Generic::ICollection<T>,
                                       private System::Collections::Invalidatable
```


| Parameter | Description |
| --- | --- |
| T | Contained value type. |
## Nested classes

* Class [Enumerator](./enumerator/)
## Methods

| Method | Description |
| --- | --- |
| [Add](./add/)(const T\&) override | Adds **element** to the end of the list. |
| [AddAfter](./addafter/)(const SharedPtr\<LinkedListNode\<T\>\>\&, const T\&) | Adds **element** after **node** of the list. |
| [AddAfter](./addafter/)(const SharedPtr\<LinkedListNode\<T\>\>\&, const SharedPtr\<LinkedListNode\<T\>\>\&) | Adds **newNode** after **node** of the list. |
| [AddBefore](./addbefore/)(const SharedPtr\<LinkedListNode\<T\>\>\&, const T\&) | Adds **element** before **node** of the list. |
| [AddBefore](./addbefore/)(const SharedPtr\<LinkedListNode\<T\>\>\&, const SharedPtr\<LinkedListNode\<T\>\>\&) | Adds **newNode** before **node** of the list. |
| [AddFirst](./addfirst/)(const T\&) | Adds **element** to the beginning of the list. |
| [AddFirst](./addfirst/)(const SharedPtr\<LinkedListNode\<T\>\>\&) | Adds **newNode** to the beginning of the list. |
| [AddLast](./addlast/)(const T\&) | Adds **element** to the end of the list. |
| [AddLast](./addlast/)(const SharedPtr\<LinkedListNode\<T\>\>\&) | Adds **newNode** to the end of the list. |
| [begin](./begin/)() | Gets iterator to the first element of collection. |
| [begin](./begin/)() const | Gets iterator to the first element of the const-qualified collection. |
| [cbegin](./cbegin/)() const | Gets iterator to the first const-qualified element of collection. |
| [cend](./cend/)() const | Gets iterator for a non-existent const-qualified element behind the end of the collection. |
| [Clear](./clear/)() override | Deletes all elements in list. |
| [Contains](./contains/)(const T\&) const override | Checks if **element** is present in list. |
| [CopyTo](./copyto/)(ArrayPtr\<T\>, int) override | Copies container data into existing array elements. |
| [crbegin](./crbegin/)() const | Gets a reverse iterator to the last const-qualified element of collection (first in reverse). |
| [crend](./crend/)() const | Gets a reverse iterator for a non-existent const-qualified element before the start of the collection. |
| [end](./end/)() | Gets iterator for a non-existent element behind the end of the collection. |
| [end](./end/)() const | Gets iterator for a non-existent element behind the end of the const-qualified collection. |
| [Find](./find/)(const T\&) const | Performs forward direction find of an **element** in the list. |
| [FindLast](./findlast/)(const T\&) const | Performs reverse direction find of an **element** in the list. |
| [get_Count](./get_count/)() const override | Gets number of elements in list. |
| [get_First](./get_first/)() const | Gets pointer to the first element in the list. |
| [get_Last](./get_last/)() const | Gets pointer to the last element in the list. |
| [GetEnumerator](./getenumerator/)() override | Gets enumerator to iterate through current [LinkedList](./). |
| [LinkedList](./linkedlist/)() | Creates empty [LinkedList](./). |
| [LinkedList](./linkedlist/)(const SharedPtr\<IEnumerable\<T\>\>\&) | Copy constructor. |
| [rbegin](./rbegin/)() | Gets a reverse iterator to the last element of collection (first in reverse). |
| [rbegin](./rbegin/)() const | Gets a reverse iterator to the last element of the const-qualified collection (first in reverse). |
| [Remove](./remove/)(const T\&) override | Removes first occurance of the specified **element** from list. |
| [Remove](./remove/)(const SharedPtr\<LinkedListNode\<T\>\>\&) | Removes node from list. |
| [RemoveFirst](./removefirst/)() | Removes first node from list. |
| [RemoveLast](./removelast/)() | Removes last node from list. |
| [rend](./rend/)() | Gets a reverse iterator for a non-existent element before the start of the collection. |
| [rend](./rend/)() const | Gets a reverse iterator for a non-existent element before the start of the const-qualified collection. |
| [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Gets the implementation of begin const iterator for the current container. |
| [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Gets the implementation of begin iterator for the current container. |
| [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Gets the implementation of end const iterator for the current container. |
| [virtualizeEndIterator](./virtualizeenditerator/)() override | Gets the implementation of end iterator for the current container. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [const_iterator](./const_iterator/) | Const iterator type. |
| [const_reverse_iterator](./const_reverse_iterator/) | Const reverse iterator type. |
| [iterator](./iterator/) | Iterator type. |
| [list_t](./list_t/) | Underlying data type. |
| [reverse_iterator](./reverse_iterator/) | Reverse iterator type. |
## Remarks


Linked list container. Implements a wrapper over std::list. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.


```cpp
#include <system/collections/linkedlist.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  // Create an instance of the LinkedList class.
  auto list = MakeObject<LinkedList<int>>();

  // Fill the linked list.
  list->AddFirst(1);
  list->AddLast(30);
  list->AddAfter(list->get_First(), 15);
  list->AddBefore(list->get_Last(), 25);

  // Print the linked list items.
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

## See Also

* Class [Object](../../system/object/)
* Class [ICollection](../icollection/)
* Class [Invalidatable](../../system.collections/invalidatable/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.PDF for C++](../../)
