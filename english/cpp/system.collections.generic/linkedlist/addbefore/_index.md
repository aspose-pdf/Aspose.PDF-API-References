---
title: System::Collections::Generic::LinkedList::AddBefore method
linktitle: AddBefore
second_title: Aspose.PDF for C++ API Reference
description: 'System::Collections::Generic::LinkedList::AddBefore method. Adds newNode before node of the list in C++.'
type: docs
weight: 400
url: /cpp/system.collections.generic/linkedlist/addbefore/
---
## LinkedList::AddBefore(const SharedPtr\<LinkedListNode\<T\>\>\&, const SharedPtr\<LinkedListNode\<T\>\>\&) method


Adds **newNode** before **node** of the list.

```cpp
void System::Collections::Generic::LinkedList<T>::AddBefore(const SharedPtr<LinkedListNode<T>> &node, const SharedPtr<LinkedListNode<T>> &newNode)
```


| Parameter | Type | Description |
| --- | --- | --- |
| node | const SharedPtr\<LinkedListNode\<T\>\>\& | Node before which to insert |
| newNode | const SharedPtr\<LinkedListNode\<T\>\>\& | New node to add |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [LinkedListNode](../../linkedlistnode/)
* Class [LinkedList](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## LinkedList::AddBefore(const SharedPtr\<LinkedListNode\<T\>\>\&, const T\&) method


Adds **element** before **node** of the list.

```cpp
SharedPtr<LinkedListNode<T>> System::Collections::Generic::LinkedList<T>::AddBefore(const SharedPtr<LinkedListNode<T>> &node, const T &element)
```


| Parameter | Type | Description |
| --- | --- | --- |
| node | const SharedPtr\<LinkedListNode\<T\>\>\& | Node before which to insert |
| element | const T\& | Element to add |

### ReturnValue

New node.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [LinkedListNode](../../linkedlistnode/)
* Class [LinkedList](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
