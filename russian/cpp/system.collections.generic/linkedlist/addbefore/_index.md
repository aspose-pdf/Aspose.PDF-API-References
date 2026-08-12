---
title: "System::Collections::Generic::LinkedList::AddBefore метод"
linktitle: "AddBefore"
second_title: "Справочник API Aspose.PDF для C++"
description: "System::Collections::Generic::LinkedList::AddBefore метод. Добавляет newNode перед узлом списка в C++."
type: docs
weight: 400
url: /ru/cpp/system.collections.generic/linkedlist/addbefore/
---
## LinkedList::AddBefore(const SharedPtr\<LinkedListNode\<T\>\>\&, const SharedPtr\<LinkedListNode\<T\>\>\&) method


Добавляет **newNode** перед **node** в списке.

```cpp
void System::Collections::Generic::LinkedList<T>::AddBefore(const SharedPtr<LinkedListNode<T>> &node, const SharedPtr<LinkedListNode<T>> &newNode)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| узел | const SharedPtr\<LinkedListNode\<T\>\>\& | Узел, перед которым вставлять |
| newNode | const SharedPtr\<LinkedListNode\<T\>\>\& | Новый узел для добавления |

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [LinkedListNode](../../linkedlistnode/)
* Class [LinkedList](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
## LinkedList::AddBefore(const SharedPtr\<LinkedListNode\<T\>\>\&, const T\&) method


Добавляет **element** перед **node** в списке.

```cpp
SharedPtr<LinkedListNode<T>> System::Collections::Generic::LinkedList<T>::AddBefore(const SharedPtr<LinkedListNode<T>> &node, const T &element)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| узел | const SharedPtr\<LinkedListNode\<T\>\>\& | Узел, перед которым вставлять |
| элемент | const T\& | Элемент для добавления |

### ReturnValue

Новый узел.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [LinkedListNode](../../linkedlistnode/)
* Class [LinkedList](../)
* Namespace [System::Collections::Generic](../../)
* Library [Aspose.PDF for C++](../../../)
