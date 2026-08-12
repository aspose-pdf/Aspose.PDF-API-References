---
title: "Aspose::Pdf::LogicalStructure::ILSTextElement класс"
linktitle: "ILSTextElement"
second_title: "Справочник API Aspose.PDF для C++"
description: "Aspose::Pdf::LogicalStructure::ILSTextElement класс. Представляет базовый класс для элементов структуры текста уровня inline в логической структуре на C++."
type: docs
weight: 2500
url: /ru/cpp/aspose.pdf.logicalstructure/ilstextelement/
---
## ILSTextElement class


Представляет базовый класс для текстовых элементов структуры уровня inline в логической структуре.

```cpp
class ILSTextElement : public Aspose::Pdf::LogicalStructure::ILSElement,
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

* Class [ILSElement](../ilselement/)
* Class [ITextElement](../itextelement/)
* Class [IAdjustPosition](../../aspose.pdf.tagged/iadjustposition/)
* Namespace [Aspose::Pdf::LogicalStructure](../)
* Library [Aspose.PDF for C++](../../)
