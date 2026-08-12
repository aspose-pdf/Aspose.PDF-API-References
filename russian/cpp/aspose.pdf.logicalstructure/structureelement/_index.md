---
title: "Класс Aspose::Pdf::LogicalStructure::StructureElement"
linktitle: "StructureElement"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::LogicalStructure::StructureElement. Представляет базовый класс для элементов структуры в логической структуре на C++."
type: docs
weight: 5500
url: /ru/cpp/aspose.pdf.logicalstructure/structureelement/
---
## StructureElement class


Представляет базовый класс для элементов структуры в логической структуре.

```cpp
class StructureElement : public Aspose::Pdf::LogicalStructure::Element
```

## Методы

| Метод | Описание |
| --- | --- |
| [ChangeParentElement](./changeparentelement/)(const System::SharedPtr\<StructureElement\>\&, bool) | Изменить родительский элемент для текущего элемента структуры. |
| [ClearId](./clearid/)() | Очистить идентификатор элемента структуры. |
| [GenerateId](./generateid/)() | Сгенерировать идентификатор для элемента структуры. |
| [get_ActualText](./get_actualtext/)() | Получает фактический текст элемента структуры. |
| [get_AlternativeText](./get_alternativetext/)() | Получает альтернативный текст элемента структуры. |
| [get_Attributes](./get_attributes/)() const | Получает объект [T:/Aspose::Pdf::LogicalStructure::StructureAttributeCollection](../). |
| [get_DefaultAttributeOwner](./get_defaultattributeowner/)() const | Получает объект [T:/Aspose::Pdf::LogicalStructure::AttributeOwnerStandard](../). |
| [get_ExpansionText](./get_expansiontext/)() | Получает расширенный текст элемента структуры. |
| [get_ID](./get_id/)() | Получает идентификатор элемента структуры. |
| [get_Language](./get_language/)() | Получает язык элемента структуры. |
| [get_Page](./get_page/)() | Получает страницу, на которой будет отображаться часть или все дочерние элементы. |
| [get_StructureType](./get_structuretype/)() const | Получает тип элемента структуры. |
| [get_Title](./get_title/)() | Получает заголовок элемента структуры. |
| [Remove](./remove/)() | Удаляет: элемент из структуры, ссылку на него из родительского объекта, ссылки на него из дочерних объектов, соответствующий объект из документа. |
| [RemoveAndMoveItsChildObjectsToItsParent](./removeandmoveitschildobjectstoitsparent/)(bool) | Удаляет элемент из структуры, ссылку на него из родительского объекта, ссылки на него из дочерних объектов и соответствующий объект из документа. Вставляет дочерние объекты удалённого объекта в прежнюю коллекцию дочерних объектов родителя, начиная с индекса удалённого объекта. |
| [set_ActualText](./set_actualtext/)(const System::String\&) | Устанавливает фактический текст элемента структуры. |
| [set_AlternativeText](./set_alternativetext/)(const System::String\&) | Устанавливает альтернативный текст элемента структуры. |
| [set_ExpansionText](./set_expansiontext/)(const System::String\&) | Устанавливает расширенный текст элемента структуры. |
| [set_Language](./set_language/)(const System::String\&) | Устанавливает язык элемента структуры. |
| [set_Title](./set_title/)(const System::String\&) | Устанавливает заголовок элемента структуры. |
| [SetId](./setid/)(const System::String\&) | Устанавливает идентификатор элемента структуры. |
| [SetTag](./settag/)(const System::String\&) | Устанавливает пользовательский тег элемента структуры. |
| [Tag](./tag/)(System::SharedPtr\<Operators::BDC\>) override | Привязать элемент структуры к оператору BDC потока содержимого. |
| [Tag](./tag/)(System::SharedPtr\<XForm\>) override | Привязать элемент структуры к потоку содержимого [XForm](../../aspose.pdf/xform/). |
| [Tag](./tag/)(System::SharedPtr\<XImage\>) override | Привязать элемент структуры к [XImage](../../aspose.pdf/ximage/). |
| [Tag](./tag/)(System::SharedPtr\<Artifact\>) override | Привязать элемент структуры к [Artifact](../../aspose.pdf/artifact/). |
| [Tag](./tag/)(System::SharedPtr\<Annotations::Annotation\>) override | Привязать элемент структуры к аннотации. |
| [ToString](./tostring/)() const override | Возвращает строку, представляющую текущий объект. |
## См. также

* Class [Element](../element/)
* Namespace [Aspose::Pdf::LogicalStructure](../)
* Library [Aspose.PDF for C++](../../)
