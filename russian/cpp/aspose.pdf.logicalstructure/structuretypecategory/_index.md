---
title: "Класс Aspose::Pdf::LogicalStructure::StructureTypeCategory"
linktitle: "StructureTypeCategory"
second_title: "Справочник API Aspose.PDF для C++"
description: "Класс Aspose::Pdf::LogicalStructure::StructureTypeCategory. Представляет категории стандартных типов структуры на C++."
type: docs
weight: 5800
url: /ru/cpp/aspose.pdf.logicalstructure/structuretypecategory/
---
## StructureTypeCategory class


Представляет категории стандартных типов [Structure](../../aspose.pdf.structure/).

```cpp
class StructureTypeCategory : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| static [BLSEs](./blses/)() | Элементы структуры уровня блока (BLSEs) описывают общую компоновку содержимого на странице, продвигаясь в направлении блочного прогрессирования. |
| static [GroupingElements](./groupingelements/)() | Группирующие элементы объединяют другие элементы в последовательности или иерархии, но не содержат контент напрямую и не влияют непосредственно на компоновку. |
| static [IllustrationElements](./illustrationelements/)() | Элементы иллюстрации — это компактные последовательности контента в порядке расположения на странице, которые рассматриваются как единые объекты относительно компоновки страницы. Иллюстрацию можно рассматривать как BLSE или ILSE. |
| static [ILSEs](./ilses/)() | Элементы структуры уровня строки (ILSEs) описывают расположение контента внутри BLSE, продвигаясь в направлении строкового прогрессирования. |
| static [to_StructureTypeCategory](./to_structuretypecategory/)(const System::String\&) | Выполняет явное преобразование из [System::String](../../system/string/) в [Aspose::Pdf::LogicalStructure::StructureTypeCategory](./). |
| [ToString](./tostring/)() const override | Возвращает строку, представляющую текущий объект. |
## См. также

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::LogicalStructure](../)
* Library [Aspose.PDF for C++](../../)
