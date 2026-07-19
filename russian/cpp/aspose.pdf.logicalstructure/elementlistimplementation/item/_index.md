---
title: "Aspose::Pdf::LogicalStructure::ElementListImplementation::Item метод"
linktitle: "Элемент"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::LogicalStructure::ElementListImplementation::Item метод. Получает элемент по заданному индексу в C++."
type: docs
weight: 600
url: /ru/cpp/aspose.pdf.logicalstructure/elementlistimplementation/item/
---
## ElementListImplementation::Item method


Получает элемент по заданному индексу.

```cpp
System::SharedPtr<Element> Aspose::Pdf::LogicalStructure::ElementListImplementation::Item(int32_t index) override
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| индекс | int32_t | Индекс в списке элементов. |

### ReturnValue

Объект [T:/Aspose::Pdf::LogicalStructure::Element](../) с указанным индексом в коллекции. Если *index* больше или равен количеству элементов в списке, возвращается null.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Element](../../element/)
* Class [ElementListImplementation](../)
* Namespace [Aspose::Pdf::LogicalStructure](../../)
* Library [Aspose.PDF for C++](../../../)
