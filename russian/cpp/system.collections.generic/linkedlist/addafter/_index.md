---
title: "System::Collections::Generic::LinkedList::AddAfter метод"
linktitle: "AddAfter"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Collections::Generic::LinkedList::AddAfter метод. Добавляет newNode после узла списка в C++."
type: docs
weight: 300
url: /ru/cpp/system.collections.generic/linkedlist/addafter/
---
## LinkedList::AddAfter(const SharedPtr\<LinkedListNode\<T\>\>\&, const SharedPtr\<LinkedListNode\<T\>\>\&) method


Добавляет **newNode** после **node** в списке.

```cpp
void System::Collections::Generic::LinkedList<T>::AddAfter(const SharedPtr<LinkedListNode<T>> &node, const SharedPtr<LinkedListNode<T>> &newNode)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| узел | const SharedPtr\<LinkedListNode\<T\>\>\& | Узел, после которого вставлять |
| newNode | const SharedPtr\<LinkedListNode\<T\>\>\& | Новый узел для добавления |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [LinkedListNode](../../linkedlistnode/)
* Class [LinkedList](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## LinkedList::AddAfter(const SharedPtr\<LinkedListNode\<T\>\>\&, const T\&) method


Добавляет **element** после **node** в списке.

```cpp
SharedPtr<LinkedListNode<T>> System::Collections::Generic::LinkedList<T>::AddAfter(const SharedPtr<LinkedListNode<T>> &node, const T &element)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| узел | const SharedPtr\<LinkedListNode\<T\>\>\& | Узел, после которого вставлять |
| элемент | const T\& | Элемент для добавления |

### ReturnValue

Новый узел.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [LinkedListNode](../../linkedlistnode/)
* Class [LinkedList](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
