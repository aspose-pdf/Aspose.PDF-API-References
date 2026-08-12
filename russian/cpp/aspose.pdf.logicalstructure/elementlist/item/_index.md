---
title: "Aspose::Pdf::LogicalStructure::ElementList::Item method"
linktitle: "Элемент"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::LogicalStructure::ElementList::Item method. Получает элемент по заданному индексу в C++."
type: docs
weight: 400
url: /ru/cpp/aspose.pdf.logicalstructure/elementlist/item/
---
## ElementList::Item method


Получает элемент по заданному индексу.

```cpp
virtual System::SharedPtr<Element> Aspose::Pdf::LogicalStructure::ElementList::Item(int32_t index)=0
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| индекс | int32_t | Индекс в списке элементов. |

### ReturnValue

Объект [T:/Aspose::Pdf::LogicalStructure::Element](../) с указанным индексом в коллекции. Если *index* больше или равен количеству элементов в списке, возвращается null.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Element](../../element/)
* Class [ElementList](../)
* Namespace [Aspose::Pdf::LogicalStructure](../../)
* Library [Aspose.PDF for C++](../../../)
