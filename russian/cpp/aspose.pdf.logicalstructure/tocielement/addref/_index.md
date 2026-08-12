---
title: "Aspose::Pdf::LogicalStructure::TOCIElement::AddRef метод"
linktitle: "AddRef"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::LogicalStructure::TOCIElement::AddRef method. Добавляет ссылку на указанный структурный элемент внутри элемента пункта оглавления (TOCI) в C++."
type: docs
weight: 100
url: /ru/cpp/aspose.pdf.logicalstructure/tocielement/addref/
---
## TOCIElement::AddRef method


Добавляет ссылку на указанный структурный элемент внутри [Table](../../../aspose.pdf/table/) пункта оглавления (TOCI).

```cpp
void Aspose::Pdf::LogicalStructure::TOCIElement::AddRef(const System::SharedPtr<StructureElement> &referencedStructureElement)
```


| Параметр | Тип | Описание |
| --- | --- | --- |
| referencedStructureElement | const System::SharedPtr\<StructureElement\>\& | Элемент [StructureElement](../../structureelement/), на который будет ссылаться этот элемент TOCI. |
## Примечания



Связывание структурного элемента, например заголовка или другого раздела содержимого, с элементом TOCI обеспечивает правильную логическую структуру и улучшает навигационное поведение в помеченных PDF.
## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [StructureElement](../../structureelement/)
* Class [TOCIElement](../)
* Namespace [Aspose::Pdf::LogicalStructure](../../)
* Library [Aspose.PDF for C++](../../../)
