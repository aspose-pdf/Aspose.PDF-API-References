---
title: "Aspose::Pdf::LogicalStructure::ListLIElement::AddRef метод"
linktitle: "AddRef"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::LogicalStructure::ListLIElement::AddRef метод. Добавляет ссылку на указанный StructureElement внутри этого элемента пункта оглавления (TOCI). Обычно используется, когда ListLIElement служит заголовком оглавления во вложенных таблицах содержания в C++."
type: docs
weight: 100
url: /ru/cpp/aspose.pdf.logicalstructure/listlielement/addref/
---
## ListLIElement::AddRef method


Добавляет ссылку на указанный [StructureElement](../../structureelement/) внутри этого элемента пункта [Table](../../../aspose.pdf/table/) содержания (TOCI). Обычно используется, когда **[ListLIElement](../)** служит заголовком оглавления во вложенных таблицах содержания.

```cpp
void Aspose::Pdf::LogicalStructure::ListLIElement::AddRef(const System::SharedPtr<StructureElement> &referencedStructureElement)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| referencedStructureElement | const System::SharedPtr\<StructureElement\>\& | Элемент [StructureElement](../../structureelement/), на который будет ссылаться этот элемент TOCI. |
## Примечания



Связывание структурного элемента, например заголовка или другого раздела содержимого, с элементом TOCI обеспечивает правильную логическую структуру и улучшает навигационное поведение в помеченных PDF.
## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [StructureElement](../../structureelement/)
* Class [ListLIElement](../)
* Namespace [Aspose::Pdf::LogicalStructure](../../)
* Library [Aspose.PDF for C++](../../../)
