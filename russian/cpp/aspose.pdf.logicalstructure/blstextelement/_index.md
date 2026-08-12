---
title: "Aspose::Pdf::LogicalStructure::BLSTextElement класс"
linktitle: "BLSTextElement"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::LogicalStructure::BLSTextElement класс. Представляет базовый класс для блочных текстовых элементов структуры в логической структуре на C++."
type: docs
weight: 1000
url: /ru/cpp/aspose.pdf.logicalstructure/blstextelement/
---
## BLSTextElement class


Представляет базовый класс для текстовых элементов структуры уровня блока в логической структуре.

```cpp
class BLSTextElement : public Aspose::Pdf::LogicalStructure::BLSElement,
                       public Aspose::Pdf::LogicalStructure::ITextElement,
                       public Aspose::Pdf::Tagged::IAdjustPosition
```

## Методы

| Метод | Описание |
| --- | --- |
| [AdjustPosition](./adjustposition/)(System::SharedPtr\<Tagged::PositionSettings\>) override |  |
| [get_StructureTextState](./get_structuretextstate/)() override | Получает объект [T:/Aspose::Pdf::LogicalStructure::StructureTextState](../) для текущего элемента. |
| [SetText](./settext/)(System::String) override | Добавляет текстовое содержимое к текущему текстовому элементу. |
## См. также

* Class [BLSElement](../blselement/)
* Class [ITextElement](../itextelement/)
* Class [IAdjustPosition](../../aspose.pdf.tagged/iadjustposition/)
* Namespace [Aspose::Pdf::LogicalStructure](../)
* Library [Aspose.PDF for C++](../../)
